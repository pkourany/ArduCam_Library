ArduCAM Library
---------------

  ArduCAM.cpp - Arduino library support for CMOS Image Sensor
  Copyright (C)2011-2013 ArduCAM.com. All right reserved
  
  Basic functionality of this library are based on the demo-code provided by
  ArduCAM.com. You can find the latest version of the library at
  http://www.ArduCAM.com
  
  !!! Adapted for Spark Core by Paul Kourany, Jan 21, 2015
  
Spark Core
----------
The devices uses the hardware SPI and I2C to communicate with the camera.

The included example, ArduCAM_OV7670_Camera_Playback.ino, requires the
Spark SD library files to compile.  The code originally output the captured
image to a UTFT compatible display but that was removed for the Core.
