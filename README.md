# Gesture-based-Desktop-Automation
As part of the SmartBridge externship my team was assigned a project "A Gesture based Tool for Sterile browsing of Radiology images using CNN and openCV"

In this project we have used a Convolutional Neural Netowork, First the model is trained on the images of different hand gestures, such as a showing numbers with fingers as 0,1,2,3,4,5. 
This model uses the integrated webcam to capture the video frame. The image of the gesture captured in the video frame is compared with the Pre-trained model and the gesture is identified.
If the gesture predicts is 0 - then images is converted into rectangle, 1 - image is Resized into (200,200), 2 - image is rotated by -45॰, 3 - image is blurred , 4 - image is Resized into (400,400) , 5 - image is converted into grayscale.

PRESENTATION VIDEO LINK:-
https://drive.google.com/file/d/1yoS3R2Io53CBQ_b-hCUoq5W0uexbszB-/view?usp=sharing

FEEDBACK LINKS:-
1.https://drive.google.com/file/d/137qjwJcx1DdhZdCVrRHSkltF-vOTHW5g/view?usp=sharing
2.https://drive.google.com/file/d/1HJU1baFQ0d1u33F98RjboaJcvhWD_hJ_/view?usp=sharing

DATASET AND FLASK FOLDER LINK(model size is 39MB so cant upload in git):-
https://drive.google.com/drive/folders/1n2yQAfDlPoroL2JmdWov7uPiZnh5UOE_?usp=sharing



