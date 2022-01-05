# FaceAttendance
This is a program that automatically detects the faces of participants using their webcams and from a database containing the images and names of all the attendees, it creates a CSV file where a list of the names of the attendees along with the first time they were detected is noted.

## Properties:
1. It uses OpenCV library to detect the faces and create a boundary box in real time to mention the names of the attendees.
2. Multiple faces in a single frame can also be detected with this program.
3. Attendance is given only once when the face is detected initially.
4. The program does not require any manual inputs, only an image of the attendee is required to be stored with the image name as for example "Attendee.jpg".

## Used Technologies:
1. OpenCV
2. Face-Recognition Library
3. Numpy

## How to run the program
Simply clone the repository and replace the images in the directory named "ImagesAttendance" with images of the attendees. Please make sure to rename the images as the name wanted in the attendance sheet (CSV file).
