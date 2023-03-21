# CommaBodyStream
An addition to openpilot to allow for teleoperation

Clone this repo to a commabody/comma3 device running standard openpilot. This is tested and works on the most current version of OpenPilot as of
3/21/23. 

### How to Use

After cloning this repo, cd into the folder and run the flask app doing `python ./app.py`. This will start a flask app on port 8080 at the ip 
address you use to ssh into your comma3.

You can use the joystick server on a smartphone at the same ip address but port 5000 to control the body. This software will be updated to allow
for different control options (working on keyboard now).
