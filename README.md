# Tsukuba Challenge Datasets

**Real World Datasets for Autonomous Navigation**

| Name                                                                       | Provider          | Type   | Format | Location                      | Date       |
|----------------------------------------------------------------------------|-------------------|--------|--------|-------------------------------|------------|
| [map_tc19_gnss+ins_furo](#tc2019-furo-gnssins-map-data)                    | fuRo              | Map    | pcd    | Tsukuba                       | 2020-08-29 |
| [tc19_furo](#tc2019-furo-sensor-data)                                      | fuRo              | Sensor | rosbag | Tsukuba                       | 2019-09-14 |
| [map_tc19_furo](#tc2019-furo-map-data)                                     | fuRo              | Map    | pcd    | Tsukuba                       | 2019       |
| [tc19_tsuchiuraPJ](#tc2019-tsuchiura-project-sensor-data)                  | Tsuchiura Project | Sensor | rosbag | Tsukuba                       | 2019-11-10 |
| [tc18_furo](#tsukuba-challenge-2018-course)                                | fuRo              | Sensor | rosbag | Tsukuba                       | 2018-09-15 |
| [map_tc18_furo](#tc2018-furo-map-data)                                     | fuRo              | Map    | pcd    | Tsukuba                       | 2018       |
| [CIT_Tsudanuma](#tsudanuma-2020-chiba-institute-of-technology-sensor-data) | CIT               | Sensor | rosbag | Chiba Institute of Technology | 2020-08-27 |
| [map_tsudanuma](#tsudanuma-2020-chiba-institute-of-technology-map-data)    | CIT               | Map    | pcd    | Chiba Institute of Technology | 2020       |

## Tsukuba Challenge 2019 Course

### TC2019, fuRo, GNSS+INS Map Data

- **Short Name:** map_tc19_gnss+ins_furo
- **File:** [map_tc19_gnss+ins_furo.pcd](http://www.taroz.net/span/data/map_tc19_gnss+ins_furo.pcd)
- **Size:** 1.95 GB
- **Format:** pcd
- **Number of Points:** 83,178,268
- **Point Type:**
  - **XYZ:** Yes
  - **Intensity:** Yes
  - **Color:** No
  - **Normal:** No
- **SLAM Method:** No SLAM (GNSS+INS, using NovAtel SPAN-CPT7 + Velodyne VLP-16)
- **Description:** [Web viewer](http://www.taroz.net/span/span_tc_vlp16_100m_5cm.html),  [LT PPT slide](http://www.taroz.net/span/data/LT_2020.pdf). The lidar measurement of more than 100 meters is cut off. We ran the Tsukuba Challenge 2019 course, excluding the forest in the park. Latitude, longitude, and ellipsoid height of the origin: 36.08254144, 140.07642281, 66.9479.
- **License:** [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

### TC2019, fuRo, Sensor Data

- **Short Name:** tc19_furo
- **File:** [tc19_js_2019-09-14-14-12-15.bag (56 GB)](https://drive.google.com/file/d/1_ZFxcYRgKpX0MLZ5_dPTrm9Fq4p1TFH1/view?usp=sharing), [tc19_js_2019-09-14-14-12-15.bag.7z (22 GB)](https://drive.google.com/file/d/1ETDRXmVyWI_kCDog2He02jrOfarEABt5/view?usp=sharing)
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
- **Description:** Low cost 3D-Lidar. Low accuracy wheel odometry.
- **License:** [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

If you use our dataset in your academic work, please cite the following paper [[DOI](https://doi.org/10.1080/01691864.2020.1717375)]:
> Yoshitaka Hara and Masahiro Tomono: "Moving Object Removal and Surface Mesh Mapping for Path Planning on 3D Terrain", Advanced Robotics, vol. 34, no. 6, pp. 375--387, 2020.


### TC2019, fuRo, Map Data

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
- **Description:** Moving objects have been removed.
- **License:** [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

If you use our dataset in your academic work, please cite the following paper [[DOI](https://doi.org/10.1080/01691864.2020.1717375)]:
> Yoshitaka Hara and Masahiro Tomono: "Moving Object Removal and Surface Mesh Mapping for Path Planning on 3D Terrain", Advanced Robotics, vol. 34, no. 6, pp. 375--387, 2020.


### TC2019, Tsuchiura Project, Sensor Data

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

### TC2018, fuRo, Sensor Data

- **Short Name:** tc18_furo
- **File:** [tc18_js_2018-09-15-14-31-29.bag (41 GB)](https://drive.google.com/file/d/1vZB_1gKLWW6cypC9W9ZlNIKxIWb1-Z9p/view?usp=sharing), [tc18_js_2018-09-15-14-31-29.bag.7z (12 GB)](https://drive.google.com/file/d/10Dh1cEg0U_MEjiDxlg6He8xEYoTIAgk4/view?usp=sharing)
- **Size:** 40.8 GB
- **Format:** rosbag
- **Date:** 2018-09-15 14:31:29 (Converted to rosbag on 2018-09-20)
- **Duration:** 1hr 31:43s
- **Setup:** Differential Wheeled Robot (Joystick Operation)
- **Sensors:**
  - **Lidar:** Velodyne VLP-16
  - **Camera:** No
  - **Radar:** No
  - **GNSS:** No
  - **IMU:** Xsens MTi-3
  - **Motor Encoders (Wheel Odometry):** Yes
- **Description:** High accuracy wheel odometry.
- **License:** [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

If you use our dataset in your academic work, please cite the following paper [[DOI](https://doi.org/10.1080/01691864.2020.1717375)]:
> Yoshitaka Hara and Masahiro Tomono: "Moving Object Removal and Surface Mesh Mapping for Path Planning on 3D Terrain", Advanced Robotics, vol. 34, no. 6, pp. 375--387, 2020.


### TC2018, fuRo, Map Data

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
- **Description:** Moving objects have been removed.
- **License:** [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

If you use our dataset in your academic work, please cite the following paper [[DOI](https://doi.org/10.1080/01691864.2020.1717375)]:
> Yoshitaka Hara and Masahiro Tomono: "Moving Object Removal and Surface Mesh Mapping for Path Planning on 3D Terrain", Advanced Robotics, vol. 34, no. 6, pp. 375--387, 2020.


## Other Courses

### [WIP] Tsudanuma 2020, fuRo, Sensor Data


### Tsudanuma 2020, Chiba Institute of Technology, Sensor Data

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


### Tsudanuma 2020, Chiba Institute of Technology, Map Data

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

### Course Name, Team Name, Sensor Data / Map Data


# [WIP] Related Datasets
