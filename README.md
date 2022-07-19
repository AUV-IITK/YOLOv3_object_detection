# YOLOv3_object_detection

This is the object detection pipeline of AUV IITK, trained on [YOLOv3](https://github.com/AlexeyAB/darknet) a real-time object detection DL model.

The custom dataset was made by annotating the images and storing the labels in YOLO format using [OpenLabeling](git@github.com:AUV-IITK/YOLOv3_object_detection.git)
tool.

Detailed training process can be found in [YOLOv3training](./YOLOv3training.ipynb) notebook.

The last saved weights can be found in the [here](https://drive.google.com/drive/folders/1DPb5JKjBqav7pKfaYFYUsmFGzNcYyOan?usp=sharing).

Current accuracy of the model trained on two classes `gate` and `buoy` is 85.7% which can be further increased by increasing the number of iterations.

The training results for 700 and 1000 iterations can be found in the [Results](./results/) folder.