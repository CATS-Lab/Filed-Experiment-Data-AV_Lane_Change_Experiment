# Filed Experiment Data-AV_Lane_Change_Experiment_Data
Autonomous Vehicle (AV) technologies can significantly improve traffic safety and reduce traffic congestion, and have attracted much attention in recent years. Some companies have already begun AV testing on highways, such as Waymo, Tesla and Ford. For AV, lane change is a fundamental part which could comprises path planning and path following control.
![](https://github.com/sgzzgit/Autonomous-Vehicle-Lane-Change-Experiment-Data/blob/master/Lane%20Change.JPG)
This folder contains data of all vehicle particpiated in the lane change experiment.
The data set contains two main floders, namely AV Lane Change Data and HV Lane Change Data. AV lane change data means the vehicle 3 is driven by computer commands, and HV means vehicle 3 is driven by human driver.
The data is originzed as standard NMEA GPS message. 

Global Positioning System Fix Data  

Name									Example Data	Description  
1. Sentence Identifier						$GPGGA			Global Positioning System Fix Data  
2. Time(Just for reference)				170834			17:08:34 Z  
3. Latitude								4124.8963, N  	  
4. Longitude								08151.6838, W  	
5. Fix Quality:  
6. Number of Satellites					05				5 Satellites are in view  
7. Horizontal Dilution of Precision (HDOP)	1.5				Relative accuracy of horizontal position  
8. Altitude								280.2, M		280.2 meters above mean sea level  
9. Height of geoid above WGS84 ellipsoid	-34.0, M		-34.0 meters  
10. Time since last DGPS update	blank		No 	last update  
11. DGPS reference station id	blank	No station id  
12. Checksum								*75				Used by program to check for transmission errors  


## Please cite the following papers when using this dataset
Li, Q., Li, X., Huang, Z., Halkias, J., McHale, G., & James, R. (2021). Simulation of mixed traffic with cooperative lane changes. Computer‐Aided Civil and Infrastructure Engineering.

Wang, Z., Zhao, X., Xu, Z., Li, X., Qu, X. (2021). Modeling and field experiments on lane changing of an autonomous vehicle in mixed traffic. Computer-Aided Civil and Infrastructure Engineering, 36(7), 877-889. https://doi.org/10.1111/mice.12540
