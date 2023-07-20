# Aerial Semantic Segmentation

## Introduction
This project focuses on performing semantic segmentation on aerial imagery using a U-Net model. The goal is to divide aerial images into different segments and assign meaningful class labels to each pixel, providing a detailed understanding of the scene's content. The model predicts masks for various classes, including paved areas, dirt, grass, gravel, water, rocks, pool, vegetation, roof, wall, window, door, fence, fence-pole, person, dog, car, bicycle, tree, bald-tree, ar-marker, obstacle, conflicting, and unlabeled regions.

## Dataset
The model was trained and evaluated on the Semantic Drone Dataset, which is made freely available by Graz University of Technology for non-commercial purposes such as academic research, teaching, scientific publications, or personal experimentation. The dataset includes more than 20 houses' aerial imagery acquired from nadir view at altitudes of 5 to 30 meters above the ground. Each image has a resolution of 6000x4000px (24Mpx). The training set consists of 400 publicly available images, while the test set comprises 200 private images. It contains bounding box annotations for person detection and pixel-accurate annotations for semantic segmentation, with 20 classes such as trees, grass, water, buildings, vehicles, and more.

## Results
The U-Net model achieves excellent performance in predicting masks for various classes in aerial images. After training on a custom aerial dataset, the model achieves an average Intersection over Union (IoU) of 0.85 . The masks generated by the model accurately identify and segment different objects and land cover types, including roads, buildings, trees, water bodies, vehicles, and other relevant features.

The predictions can be visualized and compared to the ground truth masks to assess the model's accuracy and effectiveness. Users can use the model for inference on new aerial images, obtaining accurate semantic segmentation masks for further analysis and applications.
