# Matlab ROS Interface Demo
Control your robot under ROS by Matlab



For demonstration, you can use simulation robot, navigation stack and mapping stack,
For instance you can use Jackal robot simulation in Gazebo.
Please visit following pages to see how to install and run jackal robot simulation as well as navigation and mapping stacks:

http://www.clearpathrobotics.com/guides/jackal/simulation.html
http://www.clearpathrobotics.com/guides/jackal/navigation.html

After all necessary installation completed you should type the following commands in seperate terminals: 

Terminal 1:
```
$ roslaunch jackal_gazebo jackal_world.launch config:=front_laser
```
Terminal 2:
```
$ roslaunch jackal_navigation odom_navigation_demo.launch
```
Terminal3:

```
$ roslaunch jackal_navigation gmapping_demo.launch
```

Finally, you should open Matlab and set your current directory as the one containing source matlab files and run the main matlab file provided :

```
>> YILDIZ_MATLAB_ROS_DEMO
```



