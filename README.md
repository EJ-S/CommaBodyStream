# CommaBodyStream
An addition to openpilot to allow for teleoperation

Clone this repo to a commabody/comma3 device running standard openpilot. This is tested and works on the most current version of OpenPilot as of
3/21/23. You will clone it to the base of the directoy structure (/data/openpilot).

### How to Use

After cloning this repo, cd into the folder and run the flask app doing `python ./app.py`. This will start a flask app on port 8080 at the ip 
address you use to ssh into your comma3.

You can use the joystick server on a smartphone at the same ip address but port 5000 to control the body. This software will be updated to allow
for different control options (working on keyboard now).

### Issues and Future Work

Currently the stream is in black and white due to processing limitations. We hope to get a color stream in the future, but for now black and
white is what we are stuck with.

The website itself is ugly and not the most informative. We will be making it look a little nicer and hopefully give a better user experience.

Controls are not integrated into the website like we would like. We will try and change this in the future to make this site a one stop place
for doing teleoperations of the commabody. 

We are also looking at making some modifications to the stand and balance of the body to make movement more smooth.
