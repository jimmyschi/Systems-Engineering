Video demonstration:

[![Watch the video](https://img.youtube.com/vi/1jkhfLrP9SM/0.jpg)](https://www.youtube.com/watch?v=1jkhfLrP9SM)

North Shore Extension Model 1 User Manual

Safety Consideration:

If any errors occur with the track, the trains on that section are stopped and other trains are not allowed to enter.
If any errors occur within a train, the train immediately stops until the errors are cleared.
Run from Windows 10 or above


How to - install/Start up:

Download NSE.zip from: https://tinyurl.com/yc79z428

Extract NSE.zip

Install python 3.10 or newer: https://www.python.org/downloads/release/python-3100/

Install pyqt5, numpy, and pandas by running “pip install“ in a terminal

Open a terminal to the ECE1140 directory

Run “python NSE.py”


How to configure:

CTC Schedule:

Open CTC ui through main window

Select manual mode 

Click add schedule

Add excel schedule from files

Track Controller PLC programs:

Run the simulation

Type in the number of the track controller corresponding to the section of the track (found in the track.xlsx excel sheet)

Open the track controller

Click Upload PLC Program and select a new text file containing the plc program

If a plc program must be modified, click Edit PLC Program

After making changes in the text editor, click File->Save

Track:

Open the track.xlsx file in excel

Modify fields as needed

Save the file, ensuring the name is track.xlsx

Train Controller:

Click Stop/Run Simulation to run the simulation
