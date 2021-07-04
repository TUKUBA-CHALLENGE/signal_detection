# Traffic Signal Detection

## Procedure for RealSense D435i
```bash
$ roslaunch realsense2_camera rs_camera.launch
```
```bash
$ python signal_publisher.py
```
```bash
$ python signal_subscriber.py
```
```bash
$ rosrun rqt_image_view rqt_image_view
```

