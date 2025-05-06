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
Manikant dataset 
Object Detection - :https://universe.roboflow.com/qcdgrp19/pothole-manikant/dataset/1
Object Segmentation - : https://app.roboflow.com/qcdgrp19/pothole-segmentation-cxool/browse?queryText=&pageSize=50&startingIndex=0&browseQuery=true

Yolo results
v8 70 epochs object detection multiple classes-:https://drive.google.com/drive/u/1/folders/1Rs8MH90TmXkEOFPXY-PX2_HNIOFWbCbf 
https://universe.roboflow.com/qcdgrp19/pothole-manikant/dataset/1

################################################################################################
Results from YOLO ,sam ,sam2 models


<img width="518" alt="Screenshot 2024-11-05 at 9 19 29 PM" src="https://github.com/user-attachments/assets/24ea407f-e776-4aa3-89d7-c527899f8476">

Insights-:
Segmentation performed better than detection
For SAM first finetuned the transformer model on images then used the segmented masks to generate bounding boxes 
SAM could be useful if we further combine it with a detection model since even after finetuning sam segments a lot of non potholes. We could use a classifier 
SAM2 gives very accurate predictions but in some instances even it segments objects of non interests.
