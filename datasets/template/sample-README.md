# TC2018-ABC-TEAM

## Authors
Dennis Ritchie <dmr@bell-labs.com>

Linus Torvalds <torvalds@osdl.org>

Guido van Rossum <guido@python.org>

Eric Berger <berger@willowgarage.com>

## Description
This is our dataset captured during Tsukuba Challenge 2018. It consists of 2km long trajectory with several pedestrians and different illumination conditions.

## Copyright/License
Copyright 2015-2019 ABC TEAM, licensed under Apache 2.0

## Citation
```
@INPROCEEDINGS { linux-python-ros,
  author = {Ritchie, Dennis and Torvalds, Linux and van Rossum, Guido and Berger, Eric},
  title = { We are the authors of {C}, {Linux}, {Python} and {ROS} },
  booktitle = { Proceedings of Some Important Conference },
  year = { 2020 },
  month = { August }
}
```

### Sensor Data
Please describe the sensor data in your dataset, as follows:

- **Short Name:** TC2018-ABC-TEAM
- **Description:** This file contents our captured data during Tsukuba Challenge 2018
- **Location:** Around Tsukuba City Hall
- **File:** [tc2018-abc-team.bag](https://)
- **Size:** 20 GB
- **Format:** ROSBAG
- **Date:** 2018/11/11 10:30am
- **Duration:** 1h22min
- **Sensors:** 
    - **3D LiDAR:** VELODYNE VLP16, sensor_msgs/PointCloud2, velodyne_msgs/VelodyneScan
    - **3D LiDAR:** VELODYNE VLP32, sensor_msgs/PointCloud2, velodyne_msgs/VelodyneScan
    - **2D LRF:** Hokuyo UST-20LX, sensor_msgs/LaserScan
    - **RGB Camera:** FLIR Grasshopper, sensor_msgs/Image
    - **IR Camera:** FLIR ADK, sensor_msgs/Image
    - **RGB-D/Flash Camera:** Microsoft Kinect2, sensor_msgs/PointCloud2, sensor_msgs/Image
    - **Event/DVS Camera:** No
    - **Radar:** No
    - **IMU:** XSens MTi-300, sensor_msgs/Imu
    - **GNSS:** No
    - **Wheel Encoders (Odometry):** nav_msgs/Odometry
    - **Ultrasonic:** No
    - **Microphone:** No
    - **Temperature:** No
    - **Others:** Joystick commands, sensor_msgs/Joy


### Coordinate System
- **Units:** all distances are expressed in meters, all rotations in degrees.
- **Robot:** Robot dimensions [width, lenght, height] = [0.6, 0.4, 0.6]
- **Baselink/centert:** Baselink at [0.3, 0.2, 0.15]
- **Sensors:** 
    * VLP16 to baselink [X, Y, Z, Yaw, Pitch, Roll] = [0, 0, 0.5, 0, 0, 0]
    * VLP32 to baselink [X, Y, Z, Yaw, Pitch, Roll] = [0.3, 0, 0.3, 0, 0, 0]
    * UST-20LX to baselink [X, Y, Z, Yaw, Pitch, Roll] = [0.3, 0, 0, 0, 0, 0]
    * Grasshopper to baselink [X, Y, Z, Yaw, Pitch, Roll] = [0, 0, 0.6, 0, 0, 0]
    * ADK to baselink [X, Y, Z, Yaw, Pitch, Roll] = [0, 0, 0.4, 0, 0, 0]
    * Kinect2 to baselink [X, Y, Z, Yaw, Pitch, Roll] = [0, 0, 0.5, 0, -10, 0]
    * MTi-300 to baselink [X, Y, Z, Yaw, Pitch, Roll] = [0, 0, 0, 0, 0, 0]

Grasshopper calibration file is at [grasshopper.yaml](calib/grasshopper.yaml)

VLP16 to Grasshopper extrinsics calibration file is at [vlp16-grasshopper.yaml](calib/vlp16-grasshopper.yaml)

VLP32 to Grasshopper extrinsics calibration file is at [vlp32-grasshopper.yaml](calib/vlp32-grasshopper.yaml)


### Map Data

- **Short Name:** map_tc2018-abc-team
- **Description:** Map of TC2018 course, includes moving objects
- **File:** [map_tc2018-abc-team.pcd](https://)
- **Size:** 500 MB
- **Format:** pcd
- **Date:** 2018/08/05 15:30am
- **Number of Points:** 30,000,000
- **Point Type:**
    - **XYZ:** Yes
    - **Intensity:** Yes
    - **RGB:** No
    - **Normal:** No
    - **Other:** No
- **SLAM Method:** NDT 3D
- **GNSS:** No
- **OTHER INFO:** No


### Annotation
No annotation.
