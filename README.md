# Attendance System Using Webcam

This project is an attendance system that utilizes a webcam to detect and recognize faces. It employs the following technologies:

- **OpenCV**: For image and video processing
- **Face Recognition**: For face detection and recognition
- **Pickle**: For storing and retrieving face data
- **Streamlit**: For creating a user-friendly web interface
#### Project Overview Video: https://www.linkedin.com/posts/ac-gupta-dev_computervision-facialrecognition-attendancesystem-activity-7182259366824230912-WkTV?utm_source=share&utm_medium=member_desktop
## Screenshots
##### i. Attendence window
![1  Attendence](https://github.com/anoopgupta112/Attendence_System/blob/master/Screenshots/krish_sir.png)
(![Screenshots\darshan_sir.png](https://github.com/anoopgupta112/Attendence_System/blob/master/Screenshots/darshan_sir.png))

#### ii. CSV File
![2  CSV file](https://github.com/anoopgupta112/Attendence_System/blob/master/Screenshots/csv_file.png)


## Getting Started

1. **Install Dependencies**
  Make sure you have the following Python libraries installed:
  - NumPy
  - Pandas
  - OpenCV
  - Face Recognition
  - Pickle
  - Streamlit

2. **Data Preparation**
  Run the `faces_data.py` file to create or update the pickle file containing face data and names. If the pickle file already exists, it will append new face data and names to the existing file. The face detection is performed using the Haar Cascade classifier.

3. **Take Attendance**
  Run the `take_attendance.py` file to open the webcam and start the attendance process. Press the 'O' key to record the attendance of the recognized person. The system will provide an audio feedback saying "Attendance taken".

4. **View Attendance Records**
  To view the attendance records, run the `app.py` file using the following command:

# streamlit run app.py

This will launch a Streamlit application in your default web browser, displaying the attendance records.

## Project Structure

- `faces_data.py`: Script to create or update the pickle file with face data and names.
- `take_attendance.py`: Script to open the webcam, detect faces, and record attendance.
- `app.py`: Streamlit application to display attendance records.
- `haarcascade_frontalface_default.xml`: Haar Cascade classifier for face detection.
- `data.pickle` : Pickle file containing face data and names.

## Usage

1. Run `faces_data.py` to create or update the face data pickle file.
2. Run `take_attendance.py` to start the attendance system.
3. Press 'O' to record the attendance of recognized faces.
4. Run `streamlit run app.py` to view the attendance records in a web interface.

Please note that this project requires a webcam to be connected to your system for face detection and attendance recording.





