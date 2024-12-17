# infrared-hit-uav-


The HIT-UAV contains 2898 infrared thermal images extracted from 43470 frames, captured by UAV from different scenes (schools, parking lots, roads, playgrounds, etc.), covering a wide range of aspects including objects (Person, Bicycle, Car, OtherVehicle), flight altitude data (from 60 to 130 meters), camera perspective data (from 30 to 90 degrees), and daylight intensity (day and night).

The data was originally presented in Suo, Jiashun, Tianyi Wang, Xingzhou Zhang, Haiyang Chen, Wei Zhou, and Weisong Shi. “HIT-UAV: A High-Altitude Infrared Thermal Dataset for Unmanned Aerial Vehicles.” arXiv, April 7, 2022. http://arxiv.org/abs/2204.03245.

The original data was stored in two formats: COCO and PASCAL VOC. We have transformed the data into the YOLO format (class_id x_center y_center width height).
