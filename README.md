# face_recognition

Captures real-time webcam feed.
Detects faces and compares them with stored images using pixel-wise difference.
If recognized, shows "Access Granted: Name (ID)" (Green box).
If unknown, shows "Access Denied" (Red box).
Logs attendance to attendance.csv with Employee ID, Name, Date, Time.press "q" to  exit the terminal

 press "q" to exit the camera

why its better???
-No face_recognition, face, or LBPH modules used— its just pure OpenCV.
-Simple image comparison method instead of ML-based recognition.
-Works without training, just saves faces and compares them.
-Threshold-based matching to handle variations.
-Logs employee attendance in CSV.
