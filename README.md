本项目为ROS1-noetic的gazebo的仿真小车（diff差速）项目：


1、文件launch中，gmapping.launch可以建图按键盘的i k , j k l即可实现方向的控制，并通过q和z,加减速度的大小。

2、建图后保存地图，rosrun map_sever map_saver ~/catkin_ws/src/maps/gmap

3、导航先启动仿真环境：roslaunch robo_sim robot_sim.launch

4、再启动路径规划：roslaunch robo_sim wnavigation.launch

5、其他的launch文件可能不能用，仅供测试使用。

