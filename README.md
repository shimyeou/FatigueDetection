# FatigueDetection

A uni project/Proof of concept
This is a also a space to document the progress i've made on the project and learning Github at the same time

# Fatigue detection 
current model is based on https://github.com/raja434/driver-fatigue-detection-system where i used his code as foundation
to build upon. The current model detects drowsiness using Eye aspect ratio calculation (EAR) in real-time using a webcam feed.
If the EAR ration went below the thresh hold (0.3) it will play a alarm sound dispaly an warning message as well.

# Funtions/ideas to be addded 
1. yawning detection
2. logging events
3. produce visuals


# Modification history 
* removed the alarm sound
* removed dlib's facial detect
* added face_recognition package from dlib due to requiring addtional file ("68 face landmarks.dat")
* added Mouth Aspect Ratio(MAR) which works the same as EAR
* fixed camera not closing even after "q" key is pressed
* alerts can now be displayed simultaneously
* added face_boundd to scale with the face
* added frame skip to reduce fps
* switched out face_recognition to MediaPipe 
* added logging function
* added visuals function
  
