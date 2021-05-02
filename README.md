# Jetson-Nano_-
젯슨 나노 코드 모음
gst-launch-1.0 nvarguscamerasrc ! 'video/x-raw(memory:NVMM), width=(int)1920, height=(int)1080, format=(string)NV12, framerate=(fraction)30/1' ! nvvidconv flip-method=3 ! 'video/x-raw(memory:NVMM), width=(int)480, height=(int)640, format=(string)I420' ! nvoverlaysink -e
