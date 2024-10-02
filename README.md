# Pothole-Detection---SAM-vs-YOLO

Pothole Detection on self annotated datasets using yolo object detection and segmentation models and SAM segmentation model

################################################################################################

Implementation and comparison with the repository - : https://github.com/mounishvatti/pothole_detection_yolov8
 given dataset - : https://app.roboflow.com/vit-76kid/pothole-detection-project-3yiqt/1
################################################################################################

my annotated datasets 
Object Detection - : https://app.roboflow.com/qcdgrp19/potholedetection-6fvuv/1
Object Segmentation - : https://app.roboflow.com/qcdgrp19/pothole-segmentation-cxool/browse?queryText=&pageSize=50&startingIndex=0&browseQuery=true

################################################################################################
Results from YOLO models
<img width="358" alt="Screenshot 2024-10-02 at 8 19 13 PM" src="https://github.com/user-attachments/assets/c91cabdf-afcc-4649-9f23-b43d4855655c">

Insights-:
Segmentation performed better than detection
For SAM first finetuned the transformer model on images then used the segmented masks to generate bounding boxes that would fulfil detection purpose


Output videos- :
Test Video-:
https://drive.google.com/file/d/1fw1SqNMhHqJ2Hq51YXQp9d9pUIOJtits/view?usp=sharing
Given Dataset-: 
1)yolov10 detection model- https://drive.google.com/file/d/13VVz_atnmDcbMAhh9DOrtCqzlfFsm77m/view?usp=sharing
My Dataset-: 
1) yolov8 segmentation model-: https://drive.google.com/file/d/19B47yW27CPQdPAng7WJCRSp6Gc9ejwcW/view?usp=sharing
2) yolov10 detection model - : https://drive.google.com/file/d/1o_TfIJ6tYo6lZ8juoOpLqsB1fk2KfS3Z/view?usp=sharing
3) SAM Masks overlaid-: https://drive.google.com/file/d/1HwfF7vZByej2hA6rRxHAjkGS4o0WkA_l/view?usp=sharing
4) SAM Bounding Boxes- : https://drive.google.com/file/d/1hjPKq7fDHnybyUhyAFvt2A-bmmrHWIcI/view?usp=sharing


