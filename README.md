In this little project I used OpenCV library for doing face recognition in real time.Project consists of 3 very distinct phases:Face Detection and Data Gathering; Training the Recognizer; and Face Recognition. The most common way to detect a face (or any objects), is using the “Haar Cascade classifier”
Object Detection using Haar feature-based cascade classifiers is an effective object detection method proposed by Paul Viola and Michael Jones in their paper, “Rapid Object Detection using a Boosted Cascade of Simple Features” in 2001. It is a machine learning based approach where a cascade function is trained from a lot of positive and negative images. It is then used to detect objects in other images, in this case from a webcam. In the last phase if the recognizer could predict a face, we put a text over the image with the probable id and how much is the “probability” in % that the match is correct (“probability” = 100 — confidence index). If not, an “unknow” label is put on the face.
