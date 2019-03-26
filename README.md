# License-plate-detection
This project using yolov3  to detection license plate in street using repo : https://github.com/ultralytics/yolov3
# Description 
Python 3.7 or later with the following `pip3 install -U -r requirements.txt` packages:

- `numpy`
- `torch >= 1.0.0`
- `opencv-python`
- `tqdm`
# Data
- Data training :3600 images (size 1000x2000) 
- Data test :  900 images
# How to training 
- Start Training: Run train.py --cfg cfg/yolov3.cfg --img-size 416
# Inference

- Run `detect.py` to apply trained weights to an image, such as `car.jpg` from the `test` folder.

- Link weight  : https://drive.google.com/file/d/1hTH0Qj-fpxMnqnSzRTq64KPwkrPnGxsJ/view?usp=sharing

# Some demo
<img src="https://github.com/ThorPham/License-plate-detection/blob/master/output/image_15.png" width="600">
<img src="https://github.com/ThorPham/License-plate-detection/blob/master/output/image_843.png" width="600">
<img src="https://github.com/ThorPham/License-plate-detection/blob/master/output/image_823.png" width="600">

# Webcam

- Run `detect.py` with `webcam=True` to show a live webcam feed.

# Test
- - Use `test.py --weights weights/weight.pt` to test YOLOv3 weights.
# mAP
- MAP YOLOv3-416 : 97
