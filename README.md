# m5stack_msgs

m5stack_msgsは[ROSではじめるホビーロボット番外編](https://koso2-dan.booth.pm/items/2026421)で紹介する[ros2arduino](https://github.com/ROBOTIS-GIT/ros2arduino)とM5StackでROS2の学習を行うためのサンプルコードです。

## 動作環境
ROS2 Dashing Diademata  
Ubuntu 18.04  

## インストール方法
ROS2のワークスペースにcloneしてbuildすることで使用できます。

```
$ mkdir -p ~/ros2_ws/src
$ cd ~/ros2_ws/src
~/ros2_ws/src$ git clone https://github.com/nomumu/m5stack_msgs.git
~/ros2_ws/src$ cd ..
~/ros2_ws$ colcon build
　〜ビルド成功した後〜
~/ros2_ws$ source install/setup.bash
```

## 使用方法
このメッセージを使用するコードが[公開](https://github.com/nomumu/m5stack_example)されていますのでそちらを確認して下さい。
