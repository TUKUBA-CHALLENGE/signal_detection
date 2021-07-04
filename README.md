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

## Terminal Result
- python signal_publisher.py
```bash
[INFO] [1625416640.373839]: 0 is published.
[INFO] [1625416640.922890]: 0 is published.
[INFO] [1625416641.494582]: 0 is published.
[INFO] [1625416642.069678]: 0 is published.
[INFO] [1625416642.610867]: 0 is published.
[INFO] [1625416643.186649]: 0 is published.
[INFO] [1625416643.742852]: 0 is published.
[INFO] [1625416644.313239]: 0 is published.
[INFO] [1625416644.872419]: 0 is published.
[INFO] [1625416645.444112]: 0 is published.
[INFO] [1625416646.010922]: 0 is published.
[INFO] [1625416646.620931]: 0 is published.
[INFO] [1625416647.285549]: 0 is published.
```
- python signal_subscriber.py
```bash
[INFO] [1625414692.186853]: /signal_subscriber_18169_1625414654398 signal state : UNKOWN
[INFO] [1625414692.719613]: /signal_subscriber_18169_1625414654398 signal state : UNKOWN
[INFO] [1625414693.261460]: /signal_subscriber_18169_1625414654398 signal state : UNKOWN
[INFO] [1625414693.801427]: /signal_subscriber_18169_1625414654398 signal state : UNKOWN
[INFO] [1625414694.338676]: /signal_subscriber_18169_1625414654398 signal state : UNKOWN
[INFO] [1625414694.871921]: /signal_subscriber_18169_1625414654398 signal state : UNKOWN
[INFO] [1625414695.415470]: /signal_subscriber_18169_1625414654398 signal state : UNKOWN
```
- rostopic echo /signal_info
```bash
data: 0
---
data: 0
---
data: 0
---
data: 0
---
data: 0
---
data: 0
---
data: 0
---
data: 0
```
![signal_detection](https://user-images.githubusercontent.com/52307432/124392902-d5ccbc80-dd32-11eb-9035-a4a68379a682.png)
