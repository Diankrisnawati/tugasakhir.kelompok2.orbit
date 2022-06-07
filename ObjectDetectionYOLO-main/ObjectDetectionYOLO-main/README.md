# YOLOv3 Object Detection 📸
Object Detection using coco.names dataset , weights and configuration files of real time object detection algorithm YOLOv3

To change the weights and configurations file , you may do so by changing the file directory of the same.

# Requirements 🏫
```
- pip install opencv-python
- pip install numpy
```

# Usage 👥
```
# Paramaters which can be tuned to your requirements
confThreshold = 0.5
nmsThreshold = 0.2

# for reading all the datasets from the coco.names file into the array
with open("coco.names", 'rt') as f:
    class_names = f.read().rstrip('\n').split('\n')
    
# configration and weights file location
model_config_file = "yolo-config\\yolov3-tiny.cfg"
model_weight = "yolo-weights\\yolov3-tiny.weights"

```

# How to Run this Program 🏃‍♂️
```
python run main.py
```

# Reference 🧾
You can read more about [YOLO](https://pjreddie.com/darknet/yolo/)

# Contact 📞
You may reach me using 

- [Mail](mailto:rahul20ucse156@mahindrauniversity.edu.in) 📧
- [Linkedin](https://www.linkedin.com/in/rahul-arepaka/) 😇







