### Nutkicker_Motion_Controller

Motion cueing software to read motion data out of simulators. The processed data can be used to drive a 6DOF Stewart-type platform.

Instructions:
Download the .ZIP archive and extract it somwhere on your machine. Inside it you will find three folders:
1. "MAC" and "WIN32" contain the software for your operating system of choice.
2. "Plugins" to read data out of the simulators.

DCS:
1. Go to Plugins\DCS and copy the file "Nutkicker_Export.lua" to [UserName]\Saved Games\DCS\Scripts\Hooks folder. Create the Hooks folder if it doesn't exist yet.
2. Go to the folder for your operating system and run "Nutkicker Motion Control Software" (Windows) or Nutkicker_Mac.app(MacOS).
3. Click "Start Server" in the "Sim Connect" Window. The indicator will turn yellow.
4. Re-start DCS for the changes to take effect. Start a mission and unpause. The motion data should flow but the platform will not be moving yet. It is still parked.

X-Plane:
1. Go to Plugins\X-Plane and copy the "XPlaneGetter" folder into [your X-Plane installation Folder]\resources\plugins
2. Go to the folder for your operating system and run "Nutkicker Motion Control Software" (Windows) or Nutkicker_Mac.app(MacOS).
3. Click "Start Server" in the "Sim Connect" Window. The indicator will turn yellow.
4. Re-start X-Plane for the changes to take effect. Start a flight and unpause. The motion data should flow but the platform will not be moving yet. It is still parked.


You will be able to see the platform moving only after you go into the "Platform Control" window and click on [Park-->Pause] and then on [Pause --> Motion]


The software sends the motion commands out to a MotionController via serial:
https://www.tindie.com/products/tronicgr/amc-aasd15a-servo-motion-controller/


Let me know if you run in to problems.

Dirt-e :-)
