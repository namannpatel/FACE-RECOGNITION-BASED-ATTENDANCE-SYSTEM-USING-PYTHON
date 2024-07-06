# FACE-RECOGNITION-BASED-ATTENDANCE-SYSTEM-USING-PYTHON
<h1>INTRODUCTION</h1>
#Face Recognition Based Attendance Marking System is based on the identification of face recognition to solve the previous attendance system’s issues. This system uses camera to capture the images of the employee to do face detection and recognition. The captured image is compared one by one with the face database to search for the worker’s face where attendance will be marked when a result is found in the face database. The main advantage of this system is where attendance is marked on the server which is highly secure where no one can mark the attendance of other. Moreover, in this proposed system, the face detection algorithm is improved by using the skin classification technique to increase the accuracy of the detection process. Although more efforts are invested in the accuracy of the face detection algorithm, the system is yet not portable. This system requires a standalone computer which will need a constant power supply that makes it not portable. This type of system is only suitable for marking staff’s attendance as they only need to report their presence once a day, unlike students which require to report their attendance at every class on a particular day, it will be inconvenient if the attendance marking system is not portable. Thus, to solve this issue, the whole attendance management system can be developed on a portable module so that it can be work just by executing the python program. 
#
#The main purpose of this project is to build a face recognition-based attendance monitoring system for educational institution to enhance and upgrade the current attendance system into more efficient and effective as compared to before. The current old system has a lot of ambiguity that caused inaccurate and inefficient of attendance taking. Many problems arise when the authority is unable to enforce the regulation that exist in the old system. The technology working behind will be the face recognition system. The human face is one of the natural traits that can uniquely identify an individual. Therefore, it is used to trace identity as the possibilities for a face to deviate or being duplicated is low. In this project, face databases will be created to pump data into the recognizer algorithm. Then, during the attendance taking session, faces will be compared against the database to seek for identity. When an individual is identified, its attendance will be taken down automatically saving necessary information into a excel sheet.
#
Install python 3.10.4.

Download VS IDE community version with C++ desktop development.

Open command prompt.

Change directory to your python script

cd C:\Users\HP\AppData\Local\Programs\Python\Python310\Scripts

Install following dependencies using ‘pip’ command.

pip install opencv-python==4.5.5.64

pip install numpy==1.22.3

pip install os-sys

pip install face-recognition==1.3.0

pip install face-recognition-models==0.3.0

pip install cmake==3.22.4

pip install tk==0.1.0

pip install datetime

Download and install dlib library using the following link

http://dlib.net/files/dlib-19.24.zip

Open Visual Studio Code.

Create a new folder.

Write the code ‘attendance.py’ in a file and save it with an extension ‘.py’ .

Create a new file named ‘Attendance sheet.csv’ .

Save all the files.

Create a folder named ‘image_dataset’ and save photos of all the students with their respective names.
