stereo_rig
==========

This repository contains all software that runs on the stereo diving rig.

See the [wiki](https://github.com/UCSD-E4E/stereo_rig/wiki) for complete documentation of the rig.

### Onboard Sensors

* DVL
* IMU
* Compass
* Pressure sensor
* Stereo See3CAMs
* Stereo QX100 cameras

### Repository Contents


#### QX100_Servo_Trigger

Arduino code for triggering the QX100s (shutter and on/off button) via servo

#### qx100_interfacing

idk wireless?

#### see3cam

Binary for running driver included with See3CAM (not ROS package)

#### src

ROS code for running DVL, IMU, compass/pressure sensor, and cameras

ROS Packages:

* dvl_driver: ROS driver for Teledyne Explorer DVL
* os5000: ROS driver for OceanServer pressure sensor and compass
* microstrain_3dmgx2_imu: ROS driver for Microstrain IMU
* see3cam: ROS driver built on uvc_camera for See3CAM machine vision cameras
