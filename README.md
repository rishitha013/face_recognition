# face_recognition

Captures real-time webcam feed.
Detects faces and compares them with stored images using pixel-wise difference.
If recognized:
  Displays "Access Granted: Name (ID)" with a Green box.
  Logs attendance to attendance.csv with Employee ID, Name, Date, and Time.
If unknown, it:
  Displays "Access Denied" with a Red box.


Press "q" to exit the camera feed.


 Why This is Better?
  ✔ No ML-based libraries like face_recognition, face, or LBPH.
  ✔ Uses only OpenCV for face detection and image comparison.
  ✔ Simple threshold-based image matching (no training required).
  ✔ Lightweight & efficient compared to deep-learning models.
  ✔ CSV-based logging ensures easy attendance tracking.
