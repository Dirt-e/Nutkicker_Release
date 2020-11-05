### Nutkicker_Motion_Controller

Motion cueing software to read motion data out of flightsims, or really ANY sim for that matter. The processed data can be used to drive a 6DOF Stewart-type platform.

Beginners:
1. Copy LUA\Nutkicker_Export.lua to the [UserName]\Saved Games\DCS\Scripts\Hooks folder. Create the folders if they don't exist yet.
2. Go to ..\Nutkicker_Motion_Controller\Nutkicker Motion Control Software\Builds\NMC_Development_Build and run "Nutkicker Motion Control Software".
3. Click "Start Server" in the "Sim Connect" Window. The indicator will turn yellow.
4. Re-start DCS, start a mission and unpause. The motion data should flow but the platform will not be moving yet. It is still parked.
5. You will be able to see the platform moving only after you go into the "Platform Control" window and click on [Park-->Pause] and then on [Pause --> Motion]


The software sends the motion commands out to a MotionController via serial:
https://www.tindie.com/products/tronicgr/amc-aasd15a-servo-motion-controller/


Let me know if you run in to problems.

Dirt-e :-)
