## YOLO: Real-Time Object Detection
```
git clone https://github.com/AlexeyAB/darknet.git
cd darknet
make

wget https://github.com/AlexeyAB/darknet/releases/download/darknet_yolo_v4_pre/yolov4-tiny.weights

./darknet detector test ./cfg/coco.data ./cfg/yolov4-tiny.cfg ./yolov4-tiny.weights data/person.jpg -i 0 -thresh 0.25
```

### reference
https://pjreddie.com/darknet/yolo/  

### yolo yolo2 yolo3 yolo4 yolo5 ...  
git clone https://github.com/pjreddie/darknet (yolov3)  
git clone https://github.com/AlexeyAB/darknet (yolov4)  
