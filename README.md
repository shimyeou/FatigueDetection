# Background

Babcock is a global defence and engineering company that provides critical services to civil and military
sectors, including a range of maritime sustainment services. Worker fatigue within these fast-paced
environments poses a significant risk in decision making capability, and resultant worker safety. While
training exists, there’s no effective way to monitor fatigue in real time. This project proposes a
proof-of-concept tool using computer vision and machine learning to address this gap.

# Problem
Workplace fatigue poses a safety, productivity and operational
risk for workers within a maritime maintenance environment.
Although training is provided, there is no reliable way to monitor
fatigue in real time. This project develops a proof-of-concept tool
using computer vision and machine learning to detect early
signs of fatigue at fixed workstations, aiming to enhance safety,
reduce errors, and support proactive wellbeing measures.

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
  
