# Introduction
Drones can be used to monitor places where human monitoring is not possible. But in closed environments finding GPS is very hard. In such cases, navigation of UAV is not possible.

InNDrone is a completely autonomous drone which can navigate itself in indoor environment without using GPS. To navigate in such environment, it maps the local environment by using depth camera and localize itself in that map simultaneously which is known as SLAM. It plans its own path in map which it maps previously using SLAM, it even avoids the obstacles in its vicinity and plans path accordingly.

To perform these tasks, it needs so many sensors and onboard computer. To simplify our task by integrating all the sensor data and doing work accordingly, we are using ROS(Robotic Operating System), since it contains prebuilt packages which is useful for us to not build everything from scratch.
