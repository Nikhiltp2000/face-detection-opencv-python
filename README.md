# face-detection-opencv-python

Face Detection
Face detection is a technique that identifies or locates human faces in digital images. A typical example of face detection occurs when we take photographs through our smartphones, and it instantly detects faces in the picture. Face detection is different from Face recognition. Face detection detects merely the presence of faces in an image while facial recognition involves identifying whose face it is.




Attendance for each student will be automatically update in an excel sheet by analyzing the faces in the image Install the following packages to work on this script 1.OpenCV 2.Cmake 3.Dlib 4.Face Recognition




How it Works.

Face is detected by Hog algorithm
Face detected is encoded by 128 measurements & saved for recognition
When program is initiated User's face is similar detected & encoded by 128 measurements
Later these encoded measurements are compared for recognizing face from Database
If encodings are matched, Attendance is written in Csv File with Name & Time
