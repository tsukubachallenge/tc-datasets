# `<YOUR DATASET NAME>`

Give a significative title to your dataset. 


## Authors
Please provide the list of authors and contact information.

## Description
Please provide a general description of your dataset, you may add images and other resources to make your README.md file more descriptive.

## Copyright/License
PLEASE INDICATE WHO OWNS THE COPY RIGHTS AND/OR WHAT IS THE LICENSE MODEL OF YOUR DATASET. SOME STANDARD LICENSES ARE: **GLP 3, BSD, MIT, Apache 2.0, CC BY-NC-SA 4.0**, etc.

## Citation
PLEASE PROVIDE THE BIBTEX OR PLAIN CITATION OF ANY OF YOUR PAPERS RELATED TO THIS DATASET.

### Sensor Data
Please describe the sensor data in your dataset, as follows:

- **Short Name:** `<SIMPLE NAME>`
- **Description:** `<BRIEF DESCRIPTION OF THE FILE(S) AND HOW DATA WAS CAPTURED>`
- **Location:** `<WHERE WAS THIS DATA CAPTURED>`
- **File:** `<LINK TO THE FILE(S) IN MARKDOWN FORMAT [LINK NAME](URL)>`
- **Size:** `<SIZE OF YOUR DATASET>`
- **Format:** `<DISTRIBUTION FORMAT: ROSBAG/KITTI/CSV/ETC>`
- **Date:** `<DATE/TIME WHEN YOU CREATED THIS DATASET>`
- **Duration:** `<TOTAL TIME>`
- **Sensors:** `<PLEASE DESCRIBE THE SENSORS IN THIS DATASET, HERE ARE A FEW COMMON SENSORS>`
    - **3D LiDAR:** `<MODEL NAME AND DATATYPE, NO IF NOT AVAILABLE>`
    - **2D LRF:** `<MODEL NAME AND DATATYPE, NO IF NOT AVAILABLE>`
    - **RGB Camera:** `<MODEL NAME, LENS TYPE AND DATATYPE, NO IF NOT AVAILABLE>`
    - **IR Camera:** `<IR/THERMO CAMERA MODEL AND DATATYPE, NO IF NOT AVAILABLE>`
    - **RGB-D/Flash Camera:** `<MODEL NAME AND DATATYPE, NO IF NOT AVAILABLE>`
    - **Event/DVS Camera:** `<MODEL NAME AND DATATYPE, NO IF NOT AVAILABLE>`
    - **Radar:** `<MODEL NAME AND DATATYPE, NO IF NOT AVAILABLE>`
    - **IMU:** `<MODEL NAME AND DATATYPE, NO IF NOT AVAILABLE>`
    - **GNSS:** `<MODEL NAME AND DATATYPE, NO IF NOT AVAILABLE>`
    - **Wheel Encoders (Odometry):** `<DESCRIPTION AND DATATYPE, NO IF NOT AVAILABLE>`
    - **Ultrasonic:** `<MODEL NAME AND DATATYPE, NO IF NOT AVAILABLE>`
    - **Microphone:** `<DESCRIPTION AND DATATYPE, NO IF NOT AVAILABLE>`
    - **Temperature:** `<MODEL NAME AND DATATYPE, NO IF NOT AVAILABLE>`
    - **Others:** `<DESCRIPTION AND DATATYPE, NO IF NOT AVAILABLE>`

FEEL FREE TO ADD MORE SENSORS TYPES. IF YOU HAVE MORE THAN ONE SENSOR OF THE SAME TYPE PLEASE LIST THEM.


### Coordinate System
- **Units:** Please state the distance measurement units (meters, centimeters, milimeters, inches), and rotation units (degrees, radians)
- **Robot:** Please provide the robot dimensions [width, lenght, height]
- **Baselink/centert:** Please provide the coordinates of the baselink [X, Y, Z] relative to the robot body.
- **Sensors:** For each sensor, Please describe the relative pose and posture [X, Y, Z, Yaw, Pitch, Roll] of all the sensors with respect to the robot center or baselink.

You can also contribute the extrinsics information via calibration files. The intrisics calibration files of the cameras are also appretiated. 

### Map Data
If you are contributing also the map(s), please describe it as follows:

- **Short Name:** `<SIMPLE NAME>`
- **Description:** `<BRIEF DESCRIPTION OF THE MAP, WHAT IT INCLUDES, ISSUES, ETC.>`
- **File:** `<LINK TO THE MAP FILE(S) IN MARKDOWN FORMAT [LINK NAME](URL)>`
- **Size:** `<SIZE OF THE MAP>`
- **Format:** `<FORMAT OF THE MAP: ASCII PCD/BINARY PCD/PLY/VTK/OBJ/3DS/XML/PNG/PGM/YAML>`
- **Date:** `<DATE/TIME WHEN YOU CREATED THIS MAP>`
- **Number of Points:** `<NUMBER OF POINTS IN THE MAP>`
- **Point Type:** `<PLEASE DESCRIBE THE MAP POINTS>`
    - **XY:** `<ONLY 2D COORDINATES INCLUDED>`
    - **XYZ:** `<3D COORDINATES INCLUDED>`
    - **Intensity:** `<LIDAR INTENSITY INFORMATION INCLUDED>`
    - **RGB:** `<CAMERA COLOR INFORMATION INCLUDED>`
    - **Normal:** `<NORMAL VECTOR INCLUDED>`
    - **Other:** `<PLEASE DESCRIBE FIELD TYPES>`
- **SLAM Method:** `<WHICH SLAM METHOD WAS USED TO CREATE THE MAP: NDT2D/NDT3D/Cartographer/GMapping/Octomap/LOAM/OpenVSLAM/Litamin/SuMa++/ETC.>`
- **GNSS:** `<WHETHER COORDINATES USE GNSS OR NOT>`
- **OTHER INFO:** `<PLEASE PROVIDE OTHER INFORMATION NECESSARY>`

In case the map is split into several submaps, please provide instead the tar/tar.gz/tar.bz2/zip/7z/etc.

### Annotation
If your dataset has annotations (labels) corresponding to ground truth, please provide a description of the labels.
