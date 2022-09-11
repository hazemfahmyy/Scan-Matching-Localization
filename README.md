# Scan-Matching-Localization
The purpose of this project is to implement, use and compare two localisation algorithms (ICP and NDT) in case of a car equipped with a lidar. The target of the application is to keep the max pose error below 1.2m for 170 travelled meters. For testing our algorithms, we use CARLA Simulator to provide lidar scan at regular intervals.

Using ICP resulted into a 0.95 max pose error:
![img1](ICP.png)

While using NDT resulted into a 0.77 max pose error:
![img2](NDT.png)
