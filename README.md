# Kinect Graffiti

![kinect-graffiti](https://user-images.githubusercontent.com/25073305/162198695-cbc96762-548e-4fe5-90ea-6c0785bcf558.jpg)

Version : 1.0.2
Date : 2011/02/19

Description :

Kinect Graffiti is a digital graffiti tool using "Microsoft Kinect" camera.

Idea behind this project is to use the kinect to track the motion behind graffiti. Visualizing the body and drawing trough different angles in realtime, Understanding surrounding space, pausing the time, etc...

Kinect Graffiti is a tool built in processing & openGL, SimpleOpenNI, openNI and primeSense libraries.


Example of use : http://vimeo.com/24665893


Requirements :

* Windows 7 32 or 64 bit.
* Minimum resolution : 1024x768.
* Latest Java Machine
  > http://www.java.com/getjava/
* OpenNI (v.1.3.2) and Nite MiddleWare.
  > For easy & auto installation :
    Brekel OpenNI Kinect Auto Installer - Developer Edition v1.3.2.3.exe
* Microsoft Visual C++ 2010 Redistributable Package.
  > http://www.microsoft.com/download/en/details.aspx?id=5555

How to use it :

* No Calibration is needed, just wave your hand in front of the Kinect camera.
* Activate/desactivate "POINT_CLOUD" to see your detected body or everything else.
* Use the testing presets P0...P5. or Change the "PARAMETERS" values to update the Brush style.
* Edit "VIEWPORT" to setup the camera, grid, etc...
* Use the mouse on the main stage to change the view and zoom.


Hotkeys

* C        : Next brush.
* SPACEBAR : Play/Pause. 
* ESCAPE   : Quit program.
