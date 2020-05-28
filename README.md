# emotion_detection_app
Deep learning based emotion detection for video conferencing applications 


Steps to reproduce working version of app (FaceEMR):
1. clone the directory
2. Install android studio 
3. In Android studio, go to open project and choose the given directory in pop up window.
3. Connect the device and build+run the app on device.


tflite file has been converted and added to the repo. (converted_model.tflite)

The current version of working app which captures the image and displays the emotion for captured image is using pb model (not tflite). 

pb model is stored in src/java/assets folder of FaceEMR app. 

TFLITE functionality for the current code needs to be added.



##Dependencies:

Android studio (Other dependencies will be automatically downloaded through gradle when you load project in the Android studio).

#3 Current isssues:

- Interfacing WebRTC with deep learning module.

