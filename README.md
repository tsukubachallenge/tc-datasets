# Tsukuba Challenge Datasets

**Real World Datasets for Autonomous Navigation**


## Tsukuba Challenge 2019 Course

### fuRo

#### Sensor Data

- **Short Name:** tc19_furo
- **File:** [tc19_js_2019-09-14-14-12-15.bag](https://)
- **Size:** 55.8 GB
- **Format:** rosbag
- **Date:** 2019-09-14 14:12:15
- **Duration:** 1hr 47:31s
- **Setup:** Differential Wheeled Robot (Joystick Operation)
- **Sensors:**
  - **Lidar:** SureStar R-Fans-16M
  - **Camera:** No
  - **Radar:** No
  - **GNSS:** No
  - **IMU:** Xsens MTi-3
  - **Motor Encoders (Wheel Odometry):** Yes
- **Description:** Low cost 3D-Lidar, Less accurate wheel odometry.
- **License:** [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

If you use our dataset in your academic work, please cite the following paper [[DOI](https://doi.org/10.1080/01691864.2020.1717375)]:
> Yoshitaka Hara and Masahiro Tomono: "Moving Object Removal and Surface Mesh Mapping for Path Planning on 3D Terrain", Advanced Robotics, vol. 34, no. 6, pp. 375--387, 2020.


#### Map Data

- **Short Name:** map_tc19_furo
- **File:** [map_tc19_o085_f-04_t05.pcd](https://drive.google.com/file/d/1mH20dXpnBBlQ6hMKJZqdVhphrffsvWK_/view?usp=sharing)
- **Size:** 683 MB
- **Format:** pcd
- **Number of Points:** 22,356,688
- **Point Type:**
  - **XYZ:** Yes
  - **Intensity:** Yes
  - **Color:** No
  - **Normal:** Yes
- **SLAM Method:** Occupancy Voxel Mapping using 3D Cartographer
- **Description:** Moving objects has been removed.
- **License:** [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

If you use our dataset in your academic work, please cite the following paper [[DOI](https://doi.org/10.1080/01691864.2020.1717375)]:
> Yoshitaka Hara and Masahiro Tomono: "Moving Object Removal and Surface Mesh Mapping for Path Planning on 3D Terrain", Advanced Robotics, vol. 34, no. 6, pp. 375--387, 2020.


### Tsuchiura Project

#### Sensor Data

- **Short Name:** tc19_tsuchiuraPJ
- **File:** [2019-11-10-13-37-16.bag](https://doog-cloud.com/index.php/s/yByYgFkodOUHkkJ)
- **Size:** 12.8 GB
- **Format:** rosbag
- **Date:** 2019-11-10 13:37:16
- **Duration:** 53:18s
- **Setup:** Mobile Robot (Autonomous Operation)
- **Sensors:**
  - **Lidar:** Hokuyo YVT-X002, UTM-30LX-EW, URM-40LC-EW
  - **Camera:** Ricoh Theta S, logicool C920
  - **Radar:** No
  - **GNSS:** u-blox NEO-M8T
  - **IMU:** No
  - **Motor Encoders (Wheel Odometry):** Yes
- **Description:** This bag file is compressed with 7z.
- **License:** TBD


## Tsukuba Challenge 2018 Course

### fuRo

#### Map Data

- **Short Name:** map_tc18_furo
- **File:** [map_tc18_o085_f-04_t30.pcd](https://drive.google.com/file/d/1c7Vd4vkMudAHyxc0ZOZCbTgx8ZFZ_Slx/view?usp=sharing)
- **Size:** 519 MB
- **Format:** pcd
- **Number of Points:** 17,002,094
- **Point Type:**
  - **XYZ:** Yes
  - **Intensity:** Yes
  - **Color:** No
  - **Normal:** Yes
- **SLAM Method:** Occupancy Voxel Mapping using 3D Cartographer
- **Description:** Moving objects has been removed.
- **License:** [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

If you use our dataset in your academic work, please cite the following paper [[DOI](https://doi.org/10.1080/01691864.2020.1717375)]:
> Yoshitaka Hara and Masahiro Tomono: "Moving Object Removal and Surface Mesh Mapping for Path Planning on 3D Terrain", Advanced Robotics, vol. 34, no. 6, pp. 375--387, 2020.


## Other Courses

### [WIP] fuRo, Tsudanuma

### Chiba Institute of Technology, Tsudanuma

#### Sensor Data

- **Short Name:** CIT_Tsudanuma
- **File:** [CIT_2020_compressed.bag](https://drive.google.com/file/d/1SBKNJ2NDwQlhbN75WJcMppTSwlJu1s4g/view?usp=sharing)
- **Size:** 57 GB
- **Format:** rosbag
- **Date:** 2020-08-27 17:43:12
- **Duration:** 56:12s
- **Setup:** Mobile Robot (Joystick Operation)
- **Sensors:**
  - **Lidar:** Velodyne VLP-16
  - **Camera:** Intel Realsense d435i (without depth)
  - **Radar:** No
  - **GNSS:** Drogger DG-PRO1RW (Independent Positioning)
  - **IMU:** Analog Devices ADIS16465
  - **Motor Encoders (Wheel Odometry):** Yes
- **Description:** This bag file is compressed with a command `rosbag compress`.
- **License:** TBD


#### Map Data

- **Short Name:** map_tsudanuma
- **File:** [map_tsudanuma.pcd](https://drive.google.com/file/d/19HeoDbAmwfxLW40NhZFPQGvRZKuip62B/view?usp=sharing)
- **Size:** 490.8 MB
- **Format:** pcd
- **Number of Points:** 13,583,284
- **Point Type:**
  - **XYZ:** Yes
  - **Intensity:** Yes
  - **Color:** No
  - **Normal:** Yes
- **SLAM Method:** Occupancy Voxel Mapping using LIO-SAM.
- **Description:** Tsudanuma Campus of Chiba Institute of Technology.
- **License:** TBD


## Example Course Template

### Team (and Course) Name in English


#### Sensor Data (optional)


#### Map Data (optional)


# [WIP] Related Datasets
