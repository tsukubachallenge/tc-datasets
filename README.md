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
- **Setup:** Mobile Robot (Joystick Operation)
- **Sensors:**
  - **Lidar:** SureStar R-Fans-16M
  - **Camera:** No
  - **Radar:** No
  - **GNSS:** No
  - **IMU:** Xsens MTi-3
  - **Wheel Encoders (Odometry):** Yes
- **Description:** Low cost 3D-Lidar, Less accurate wheel odometry.
- **License:** TBD

If you use our dataset in your academic work, please cite the following paper [[DOI](https://doi.org/10.1080/01691864.2020.1717375)]:
```
Yoshitaka Hara and Masahiro Tomono: "Moving Object Removal and Surface Mesh Mapping for Path Planning on 3D Terrain", Advanced Robotics, vol. 34, no. 6, pp. 375--387, 2020.
```


#### Map Data

- **Short Name:** map_tc19_furo
- **File:** [map_tc19_o085_f-04_t05.pcd](https://)
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
- **License:** TBD

If you use our dataset in your academic work, please cite the following paper [[DOI](https://doi.org/10.1080/01691864.2020.1717375)]:
```
Yoshitaka Hara and Masahiro Tomono: "Moving Object Removal and Surface Mesh Mapping for Path Planning on 3D Terrain", Advanced Robotics, vol. 34, no. 6, pp. 375--387, 2020.
```


## Tsukuba Challenge 2018 Course

### [WIP] fuRo


## Other Courses

### [WIP] fuRo Tsudanuma

### Tsudanuma Campus Course of Chiba Institute of Technology
### Advanced Robotics Department Team of Chiba Institute of Technology 
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
  - **Wheel Encoders (Odometry):** Yes
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
