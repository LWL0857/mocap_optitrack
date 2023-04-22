# 1.使用环境：

ubuntu20.04 ros2 foxy



```
git clone  https://github.com/LWL0857/mocap_optitrack.git
```

建立工作空间，在工作空间建src文件夹，把功能包放在src下

修改功能包中的mocap.yaml文件

![微信截图_20230422191323](image/%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20230422191323.png)

在src文件夹同级目录下打开终端

```
colcon build

//警告不用理会

source install/setup.bash

ros2 launch mocap_optitrack mocap.launch.py
```

打开新的终端

运行

```
ros2 topic list

ros2 topic echo topic name 
```

![微信截图_20230422191538](image/%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20230422191538.png)