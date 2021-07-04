# Traffic Signal Detection

## Procedure for RealSense D435i
```bash
$ ~/catkin_ws
$ source devel/setup.bash
$ roslaunch realsense2_camera rs_camera.launch
```
```bash
$ ~/catkin_ws/src/signal_detection
$ python signal_publisher.py
```
```bash
$ ~/catkin_ws/src/signal_detection
$ python signal_subscriber.py
```

