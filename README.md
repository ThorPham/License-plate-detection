# License-plate-detection
This project using yolo3  to detection license plate in street
# Description 
Python 3.7 or later with the following `pip3 install -U -r requirements.txt` packages:

- `numpy`
- `torch >= 1.0.0`
- `opencv-python`
- `tqdm`
# Data
- Data training :3600 images (size 1000x2000) 
- Data test 900 images
# Inference

Run `detect.py` to apply trained weights to an image, such as `car.jpg` from the `test` folder:
<img src="https://github.com/ThorPham/License-plate-detection/blob/master/output/image_15.png" width="600">
<img src="https://github.com/ThorPham/License-plate-detection/blob/master/output/image_843.png" width="600">
**YOLOv3:** `python3 detect.py --cfg cfg/yolov3.cfg --weights weights/weight.pt`
 #mAP

- Use `test.py --weights weights/weight.pt` to test YOLOv3 weights.

<i></i> | yolov3 |  
--- | ---| ---    
YOLOv3-416 | 97| 
