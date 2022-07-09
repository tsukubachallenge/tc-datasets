# Tsukuba Challenge Datasets

**Real World Datasets for Autonomous Navigation**

| Name                                                                          | Provider (Team)               | Type   | Location                      |
|-------------------------------------------------------------------------------|-------------------------------|--------|-------------------------------|
| [map_tc21_mapiv](#tc2021-mapiv-slam-map-data)                                  | MapIV                         | Map    | Tsukuba Challenge 2021 Course |
| [map_tc19_gnss+ins_furo](#tc2019-furo-gnssins-map-data)                       | fuRo                          | Map    | Tsukuba Challenge 2019 Course |
| [tc19_furo](#tc2019-furo-sensor-data)                                         | fuRo                          | Sensor | Tsukuba Challenge 2019 Course |
| [map_tc19_furo](#tc2019-furo-map-data)                                        | fuRo                          | Map    | Tsukuba Challenge 2019 Course |
| [tc19_tsuchiura-pj](#tc2019-tsuchiura-project-sensor-data)                    | Tsuchiura Project             | Sensor | Tsukuba Challenge 2019 Course |
| [tc18_furo](#tsukuba-challenge-2018-course)                                   | fuRo                          | Sensor | Tsukuba Challenge 2018 Course |
| [map_tc18_furo](#tc2018-furo-map-data)                                        | fuRo                          | Map    | Tsukuba Challenge 2018 Course |
| [tsudanuma20_cit](#tsudanuma-2020-chiba-institute-of-technology-sensor-data)  | Chiba Institute of Technology | Sensor | Tsudanuma 2020                |
| [map_tsudanuma20_cit](#tsudanuma-2020-chiba-institute-of-technology-map-data) | Chiba Institute of Technology | Map    | Tsudanuma 2020                |
| [utsukuba22_university_of_tsukuba](#utsukuba-2022-university-of-tsukuba-sensor-data)                     | University of Tsukuba                       | Sensor    | Tsukuba campus 2022           |
| [map_utsukuba22_university_of_tsukuba](#utsukuba-2022-university-of-tsukuba-map-data)                     | University of Tsukuba                       | Map    | Tsukuba campus 2022           |

```
## Example Course Template

### Course Name, Team Name, Sensor Data / Map Data
```

## Tsukuba Challenge 2021 Course

### TC2021, MapIV, SLAM Map Data

- **Short Name:** map_tc21_mapiv
- **Provider (Team):** MapIV
- **Type:** Map
- **Location:** Tsukuba Challenge 2021 Course
- **File:** [0.15_map_all.pcd (505 MB)](https://www.dropbox.com/sh/5gel5pvjm6wh8xn/AABPHDa7t4U8v7X2Jb6EM9Mia?dl=0), [map_converted*.pcd (10.9 GB)](https://www.dropbox.com/sh/hfb36jgk1km15xk/AABpmYx1JDr5wIVdkFU9rrnfa?dl=0)
- **Size:** 505 MB, 10.9GB
- **Format:** pcd
- **Number of Points:** 31,559,485, 682,377,762
- **Point Type:**
  - **XYZ:** Yes
  - **Intensity:** Yes
  - **Color:** No
  - **Normal:** No
- **SLAM Method:** [MapIV Engine](https://www.map4.jp/technology) (HESAI PandarXT-32 + Septentrio mosaic)
- **Description:** The LiDAR measurement of more than 70 meters is cut off. "map_converted*.pcd" are raw point cloud maps, and "0.15_map_all.pcd" is a downsampled and concatenated map of them. We used Voxel Grid Filter for downsamapling. Map coordinate system is the Japan Plane Rectangular CS IXj, and its height is orthometric height.
- **License:** [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)


## Tsukuba Challenge 2019 Course

### TC2019, fuRo, GNSS+INS Map Data

- **Short Name:** map_tc19_gnss+ins_furo
- **Provider (Team):** fuRo
- **Type:** Map 
- **Location:** Tsukuba Challenge 2019 Course 
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
- **Description:** [Web viewer](http://www.taroz.net/span/span_tc_vlp16_100m_5cm.html). [Lightning talk slide](http://www.taroz.net/span/data/LT_2020.pdf). The lidar measurement of more than 100 meters is cut off. We ran the Tsukuba Challenge 2019 course, excluding the forest in the park. Latitude, longitude, and ellipsoid height of the origin: 36.08254144, 140.07642281, 66.9479.
- **License:** [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)


### TC2019, fuRo, Sensor Data

- **Short Name:** tc19_furo
- **Provider (Team):** fuRo
- **Type:** Sensor 
- **Location:** Tsukuba Challenge 2019 Course 
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
- **Provider (Team):** fuRo
- **Type:** Map 
- **Location:** Tsukuba Challenge 2019 Course 
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

- **Short Name:** tc19_tsuchiura-pj
- **Provider (Team):** Tsuchiura Project
- **Type:** Sensor 
- **Location:** Tsukuba Challenge 2019 Course 
- **File:** [2019-11-10-13-37-16.bag](https://doog-cloud.com/index.php/s/yByYgFkodOUHkkJ)
- **Size:** 12.8 GB
- **Format:** rosbag
- **Date:** 2019-11-10 13:37:16
- **Duration:** 53:18s
- **Setup:** Mobile Robot (Autonomous Operation)
- **Sensors:**
  - **Lidar:** Hokuyo YVT-X002, UTM-30LX-EW, URM-40LC-EW
  - **Camera:** Ricoh Theta S, Logicool C920
  - **Radar:** No
  - **GNSS:** u-blox NEO-M8T
  - **IMU:** No
  - **Motor Encoders (Wheel Odometry):** Yes
- **Description:** This bag file is compressed with 7z.
- **License:** [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)


## Tsukuba Challenge 2018 Course

### TC2018, fuRo, Sensor Data

- **Short Name:** tc18_furo
- **Provider (Team):** fuRo
- **Type:** Sensor 
- **Location:** Tsukuba Challenge 2018 Course 
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
- **Provider (Team):** fuRo
- **Type:** Map 
- **Location:** Tsukuba Challenge 2018 Course 
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

- **Short Name:** tsudanuma20_cit
- **Provider (Team):** Chiba Institute of Technology
- **Type:** Sensor 
- **Location:** Tsudanuma 2020
- **File:** [tsudanuma20_cit_compressed.bag](https://drive.google.com/file/d/1SBKNJ2NDwQlhbN75WJcMppTSwlJu1s4g/view?usp=sharing)
- **Size:** 57 GB
- **Format:** rosbag
- **Date:** 2020-08-27 17:43:12
- **Duration:** 56:12s
- **Setup:** Mobile Robot (Joystick Operation)
- **Sensors:**
  - **Lidar:** Velodyne VLP-16
  - **Camera:** Intel RealSense D435i (without depth)
  - **Radar:** No
  - **GNSS:** Drogger DG-PRO1RW (Independent Positioning)
  - **IMU:** Analog Devices ADIS16465
  - **Motor Encoders (Wheel Odometry):** Yes
- **Description:** This bag file is compressed with a command `rosbag compress`.
- **License:** TBD


### Tsudanuma 2020, Chiba Institute of Technology, Map Data

- **Short Name:** map_tsudanuma20_cit
- **Provider (Team):** Chiba Institute of Technology
- **Location:** Tsudanuma 2020
- **Type:** Map
- **File:** [map_tsudanuma20_cit.pcd](https://drive.google.com/file/d/19HeoDbAmwfxLW40NhZFPQGvRZKuip62B/view?usp=sharing)
- **Size:** 490.8 MB
- **Format:** pcd
- **Number of Points:** 13,583,284
- **Point Type:**
  - **XYZ:** Yes
  - **Intensity:** Yes
  - **Color:** No
  - **Normal:** Yes
- **SLAM Method:** LIO-SAM
- **Description:** Tsudanuma Campus of Chiba Institute of Technology.
- **License:** TBD

### UTsukuba 2022, University of Tsukuba, Sensor Data

- **Short Name:** utsukuba22_university_of_tsukuba
- **Provider (Team):** University of Tsukuba
- **Type:** Sensor 
- **Location:** Tsukuba campus 2022
- **File:** [utsukuba22_university_of_tsukuba.bag.zst](https://drive.google.com/file/d/1AdCAw6NiVh2lg-FVPgSw6jdtMDTxHpUZ/view?usp=sharing)
- **Size:** 8 GB
- **Format:** rosbag
- **Date:** 2022-07-09 10:34:13
- **Duration:** 47:02s
- **Setup:** Mobile Robot (Joystick Operation)
- **Sensors:**
  - **Lidar:** Velodyne VLP-16
  - **Camera:** No
  - **Radar:** No
  - **GNSS:** No
  - **IMU:** LOAD MicroStrain 3DM-GX5-25
  - **Motor Encoders (Wheel Odometry):** Yes
- **Description:** This bag file is compressed with a command `zstd`. You can decompress with the command `zstd -d utsukuba22_university_of_tsukuba.bag.zst`
- **License:** [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

### UTsukuba 2022, University of Tsukuba, Map Data

- **Short Name:** map_utsukuba22_university_of_tsukuba
- **Provider (Team):** University of Tsukuba
- **Location:** Tsukuba campus 2022
- **Type:** Map
- **File:** [map_utsukuba22_university_of_tsukuba.pcd](https://drive.google.com/file/d/1mSi6OP2p4jFwK3vVgvFIbCdxPmN4UcVg/view?usp=sharing)
- **Size:** 224 MB
- **Format:** pcd
- **Number of Points:** 14,656,120
- **Point Type:**
  - **XYZ:** Yes
  - **Intensity:** Yes
  - **Color:** No
  - **Normal:** Yes
- **SLAM Method:** LIO-SAM
- **Description:** Tsukuba Campus of University of Tsukuba.
- **License:**  [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

# [WIP] Related Datasets

