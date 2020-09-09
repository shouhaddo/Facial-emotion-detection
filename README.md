# Facial-emotion-detection
here we detect facial emotion by a live web cam using cnn model .

<b>What is facial emotion recognition?</b>
Facial emotion recognition is the process of detecting human emotions from facial expressions. The human brain recognizes emotions automatically, and software has now been developed that can recognize emotions as well. This technology is becoming more accurate all the time, and will eventually be able to read emotions as well as our brains do. 

AI can detect emotions by learning what each facial expression means and applying that knowledge to the new information presented to it. Emotional artificial intelligence, or emotion AI, is a technology that is capable of reading, imitating, interpreting, and responding to human facial expressions and emotions.<br>

 <b>Dataset Description </b><br>
 
The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centred and occupies about the same amount of space in each image.

The task is to categorize each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). The training set consists of 28,709 examples and the public test set consists of 3,589 examples.

<b>Face detection</b><br>
Images are already cropped and just facial area are focused on in the train set. This is not a must but we should detect faces of the custom testing images and feed just facial areas to the neural networks model. This will increase the accuracy dramatically.

There are several face detection solutions. OpenCV offers haar cascade and single shot multibox detector (SSD). Dlib offers Histogram of Oriented Gradients (HOG) and Max-Margin Object Detection (MMOD). Finally Multi-task Cascaded Convolutional Networks (MTCNN) is a common solution for face detection. Herein, haar cascade and HoG are legacy methods whereas SSD, MMOD and MTCNN are deep learning based modern solutions

<b>#Conclusion</b><br>
<br>
So, we’ve constructed a deep CNN model to recognize facial expressions of human beings. Model produces <b>67.6% accuracy on test set</b>. That can be acceptable because winner of kaggle challenge has got <b>71% accuracy</b>.

