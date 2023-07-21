# ddrobot_src
>. ddrobot is stand for Differential Drive Robot
**Reference: Lino Robot**
https://linorobot.org/
https://github.com/linorobot/linorobot
# 1. arduino_node
Code loaded on Arduino to control motor speed and read data from accelerometer MPU-6050
# 2. ddrobot_bringup
1. Initialization of the robot description (URDF) and publishing of joint state.
2. Setting up a serial communication port.
3. Configuration and launch of the IMU relay and filter.
4. Configuration and launch of the LIDAR sensor.
5. Publishing of robot odometry.
6. Using the Extended Kalman Filter (EKF) to fuse sensor and estimate position for the robot.
7. Visualization robot in the RViz interface.
# 3. ddrobot_description
# 4. ddrobot_navigation
