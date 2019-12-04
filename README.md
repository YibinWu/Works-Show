# Works Show
The author of this repo is a master candidate in Navigation, Guidance and Control in GNSS Research Center at Wuhan University, supervised by professor Xiaoji Niu. 
<br/>
This repository is about his research works in his master years. If you are interesting in anything of or have any question about it, please feel free to contact him <ybwu@whu.edu.cn>. 
<br/>


## 1. Wheel-INS 
The experiments were carried out using a self-build wheel robot which was controled by a smartphone through WiFi.

<img src="https://github.com/Sanduo007/Works-Show/blob/master/img/WMRobot.png" width = 30% height = 30% div align=left />

<br/>

Positioning results on the horizontal plane and the heading error along with time for small loop trajectory in one test. 

<img src="https://github.com/Sanduo007/Works-Show/blob/master/img/0701DR.png" width = 30% height = 30% div align=left />
<img src="https://github.com/Sanduo007/Works-Show/blob/master/img/0701poserr.png" width = 30% height = 30% div align=center />
<img src="https://github.com/Sanduo007/Works-Show/blob/master/img/0701headingerr.png" width = 60% height = 60% />

Positioning results on the horizontal plane and the heading error along with time for large polyline trajectory in one test. 
<br/>

<img src="https://github.com/Sanduo007/Works-Show/blob/master/img/0720DR.png" width = 30% height = 30% div align=left />
<img src="https://github.com/Sanduo007/Works-Show/blob/master/img/0720poserr.png" width = 30% height = 30% div align=center />
<img src="https://github.com/Sanduo007/Works-Show/blob/master/img/0720headingerr.png" width = 60% height = 60% />

## 2. Pose estimation for UAV landing 

The idea for this work is to fuse the UAV pose retrieved by detecting the landing marker with the MEMS IMU data to achieve precision and continuous positioning for UAV landing.
The positioning and attitude error of the proposed system in one test.
<img src="https://github.com/Sanduo007/Works-Show/blob/master/img/UAVposerr.png" width = 60% height = 60% div align=left />
<img src="https://github.com/Sanduo007/Works-Show/blob/master/img/UAVatterr.png" width = 60% height = 60% div align=center />

## 3. Express UAV 

The drone was designed for freighting which could takeoff automatically and fly to the destination by GNSS/INS positioning with obstacle avoidance by ultrasonic, and then land on the pad by detecting the previously placed marker through an onboard camera. 

https://youtu.be/mQtUiN1oKXY
<a href="https://youtu.be/mQtUiN1oKXY" target="_blank"><img src="https://github.com/Sanduo007/Works-Show/blob/master/img/ExpressUAV.png" 
alt="ExpressUAV" width="320" height="240" border="10" /></a>

<br/>

## 4. Some competetion awards
4.1 **First prize** and  **"Best Paper Award"** in the 14th China Graduate Electronic Design Competition (*based on the work of Collaborative Precision Positioning and Navigation System of Robot*)(Aug.2019)

In this work, we built an autonomous driving. The self-developed GNSS/MEMS IMU module was used to obtain real-time localization results, lidar to detect obstacles, camera to detect the laneline and aid the INS and odometer was also used to provide velocity observation to correct INS error. The arpngicial potential field method was intrioduced for path planning.

<img src="https://github.com/Sanduo007/Works-Show/blob/master/img/EDcomment.png" width = 30% height = 30% div align=left />
<img src="https://github.com/Sanduo007/Works-Show/blob/master/img/ElectronicDesignRobot.png" width = 30% height = 30% div align=center />

<br/>

4.2 **Third prize** in the 6th China Graduate Contest on Smart-city Technology and Creative Design (*based on the work of express UAV*)(Aug.2019)

<img src="https://github.com/Sanduo007/Works-Show/blob/master/img/SmartCity.JPG" width = 30% height = 30% div align=left />
<img src="https://github.com/Sanduo007/Works-Show/blob/master/img/ExpressUAV.png" width = 30% height = 30% div align=center />

## 5. Learning SLAM

***Introduction of EPnP*** is an introduction of the EPnP algorithm with detailed equations derivation which is proposed by Computer Vision Laboratory at EPFL.
<br/>

***Equations Derivation of VINS-Mono*** is an analysis of the [VINS-Mono](https://github.com/HKUST-Aerial-Robotics/VINS-Mono) (a monocular VIO system) with detailed equations derivation which is proposed by Aerial Robotics Group at HKUST.