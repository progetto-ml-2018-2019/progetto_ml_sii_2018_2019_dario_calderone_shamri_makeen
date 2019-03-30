# Project for Roma Tre ML/SII courses: Facenet Application


## Dependencies
* Tensorflow 1.13.1
* Python 3.6.3
* Same as [requirement.txt](https://github.com/davidsandberg/facenet/blob/master/requirements.txt) in [davidsandberg](https://github.com/davidsandberg/facenet) repository.
## Pre-trained models
* [20170511-185253](https://drive.google.com/file/d/0B5MzpY9kBtDVOTVnU3NIaUdySFE/edit)
## How to use
* If you decide to use another dataset, simply add or remove the images in the "images" folder. The images related to one
certain person must be placed in a folder with its name.
* Use command “python make_aligndata_git.py” to perform the alignment.
* Use command “python make_classifier_git.py” to start the training process.
* Use command “python identify_face_image.py” to use the face-recognition function for an image named "abd.jpg" in the project folder.
* Use command “python identify_face_video.py” to use the face-recognition function for a video file named named "video.mp4" in the project folder.
* Use command “python realtime_facenet_git.py“ to use the real time face-recognition function through the webcam
