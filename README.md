# GNSS-LiDAR-Localization
Localization using GNSS and LiDAR-Odometry, to achieve a high frequency pose estimates and compare it against the ground truth

## Methodology
We set up an automated driving localization stack in ROS2, using KISS-ICP for LIDAR Odometry and extending the problem by combining low-frequency GNSS measurements for improved pose estimation. 

The fundamental principle is to use GNSS periodically to correct the global vehicle pose and Odometry to propogate vehicle pose between corrections. Overall, we have two sources of localization:

**GNSS:** Absolute Geographical Position & Heading

**LiDAR-Odometry:** Relative motion between consecutive measurements


## KISS-ICP

<img width="800" height="450" alt="kissicp-ezgif com-video-to-gif-converter" src="https://github.com/user-attachments/assets/4cc543df-4699-4260-b5a6-6436a41ab8c7" />



## GNSS + LIDAR



https://github.com/user-attachments/assets/8542c0bc-c814-408a-abb2-18ced01558f4

