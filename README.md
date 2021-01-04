# Works Show
<img src="https://s1.ax1x.com/2020/10/09/0rTNcV.jpg" width = 30% height = 30% />
My name is Yibin Wu. I completed my M.Eng. in Navigation, Guidance and Control in GNSS Research Center at Wuhan University in May. 2020, supervised by Prof. Xiaoji Niu. I received my B.Eng. (with honors) in Navigation Engineering in school of geodesy and geomatic at the same University in Jun. 2017. 

<br/>

If you are interested in anything of it or have any questions about my research, please feel free to contact me <ybwu@whu.edu.cn>. 
<br/>

## 1. Wheel-INS 
In this study, a MEMS IMU was mounted on the wheel of wheeled robot to take advantages of rotation modulation and obtain the vehicle velocity, so as to suppress the error drift of INS. In addition, the single wheel-mounted IMU was extended to multi-IMU placed at different locations of the vehicle to enhance the localization performance. Each IMU maintains its own localization system and exchange information at a constant frequency. The spatial constraint between the IMUs are also exploited to limit the error accumulation. The absolute positioning error drift rate of the proposed system is less than **1%**. Please click [here](https://github.com/i2Nav-WHU/Wheel-INS) for public code and data.

<img src="https://s1.ax1x.com/2020/10/09/0rgjJO.png" width = 40% height = 40% div align=left />
<img src="https://s1.ax1x.com/2020/10/09/0rgTy9.png" width = 40% height = 40% div align=center />
    
<br/>

Positioning results and the pose error of the single Wheel-INS on the horizontal plane  in one test with a **polyline trajectory** are shown as following. 

<img src="https://s1.ax1x.com/2020/10/09/0rgyss.png" width = 30% height = 30% div align=left />
<img src="https://s1.ax1x.com/2020/10/09/0rggZq.png" width = 30% height = 30% div align=center />              

<br/>

Positioning results and the pose error of the single Wheel-INS on the horizontal plane in one test with a **large-scale loop closure trajectory**  are shown as following. 

<br/>

<img src="https://s1.ax1x.com/2020/10/09/0rgbe1.png" width = 30% height = 30% div align=left />
<img src="https://s1.ax1x.com/2020/10/09/0rgqdx.png" width = 30% height = 30% div align=center />


### Papers (under review)
**Y. Wu**, X. Niu, and J. Kuang. "Wheel-INS2: Multiple MEMS IMU-based Dead Reckoning System for Wheeled Robots with Evaluation of Different IMU Configurations." [*arXiv*](https://arxiv.org/pdf/2012.10593.pdf)
<br/>
**Y. Wu**, X. Niu, and J. Kuang. "A Comparison of Three Measurement Models for the Wheel-mounted MEMS IMU-based Dead Reckoning System." [*arXiv*](https://arxiv.org/ftp/arxiv/papers/2012/2012.10589.pdf)
<br/>
X. Niu, **Y. Wu**, and J. Kuang. "Wheel-INS: A Wheel-mounted MEMS IMU-based Dead Reckoning System." [*arXiv*](https://arxiv.org/ftp/arxiv/papers/1912/1912.07805.pdf)

## 2. GNSS RTK/MEMS IMU/Odometer Integrated Navigation System
 This figure shows the positioning results of the designed GNSS RTK/MEMS IMU/odometer integrated navigation system comparing with GNSS/INS and GNSS/INS/NHC integrated navigation. The experiment was conducted at Wuhan city. The enlarged part of the trajectory in the figure is the end of a tunnel. It can be observed that the vehicle velocity along with non-holonomic constraints (NHCs) contribute significantly to suppressing the position error drift in GNSS-denied environments.
<br/>

<img src="https://s1.ax1x.com/2020/10/09/0rgfiT.png" width = 50% height = 50% />

<br/>

## 3. Pose estimation for UAV landing 

The idea of this study is to fuse the UAV pose retrieved by detecting the landing marker with the MEMS IMU data to obtain more precise, continuous and high-rate pose estimation for UAV landing. The related paper was published in [*Sensors*](https://doi.org/10.3390/s19245428). We also applied a patent based on this technique.
<br/>

## 4. GNSS/Visual/Inertial integrated navigation system

During my internship in Momenta, a startup focusing on self-driving technologies, I implemented a co-initialization algorithm for GNSS/Visual/Inertial integrated navigation. 

## 5. SLAM Learning

[***Formula Derivation and Analysis of the VINS-Mono***](https://arxiv.org/ftp/arxiv/papers/1912/1912.11986.pdf) is a study note of the [VINS-Mono](https://github.com/HKUST-Aerial-Robotics/VINS-Mono) (a state-of-the-art monocular VIO system ) with detailed formula derivation and analysis, which is completed by me independently.

[***Introduction of EPnP***](https://github.com/YibinWu/Works-Show/blob/master/Introduction%20of%20EPnP.pdf) in this repo is an introduction to the EPnP algorithm with detailed formula derivation.
<br/>

## 6. Some competition awards
6.1 **First prize (1.97%)** and  **Best Paper Award** in the 14th China Graduate Electronic Design Competition (*based on the work of Collaborative Precision Positioning and Navigation System of Robot*) (Aug.2019)

In this study, we built an autonomous-driving robot. A self-developed GNSS/MEMS IMU/odometer integrated navigation module was used to obtain real-time localization results. A 2D LiDAR was used to detect obstacles. And a camera was utilized to detect the lane line and markers to fuse with INS, so as to enhance the positioning performance. The artificial potential field method was introduced for path planning.

Here is a video illustrating our work. 

<a href="https://www.youtube.com/embed/3vmfz4duIoE" target="_blank"><img src="https://s1.ax1x.com/2020/10/09/0rgzSe.png" 
alt="robot" width = 40% height = 40% border="10" /></a>

<br/>

6.2 **Third prize** in the 6th China Graduate Contest on Smart-city Technology and Creative Design (*based on the work of express UAV*) (Aug.2019)

In this work, a drone was designed and developed for expressing delivery. It can automatically takeoff and fly to the previously set destination by GNSS/INS integrated positioning with collision avoidance by ultrasonic sensors, and then land on the pad by detecting the previously placed marker using onboard camera and IMU. The video shows the key technologies. 

<a href="https://www.youtube.com/embed/mQtUiN1oKXY" target="_blank"><img src="https://github.com/YibinWu/Works-Show/blob/master/img/ExpressUAV.png" 
alt="robot" width = 40% height = 40% border="10" /></a>