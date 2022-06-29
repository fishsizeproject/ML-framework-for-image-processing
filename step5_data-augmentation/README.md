# Step 5: Data augmentation

In this framework we use the open source Albumentations library (Buslaev et al. 2020) for data augmentation. The script <i>data_augmentation_classification.ipynb</i> defines an augmentation pipeline for image classification approach and applies vertical and horizontal flips for all images in a directory. The script <i>data_augmentation_object_detection.ipynb</i> is used to transform the annotations (bounding boxes) for the object detection method by applying vertical and horizontal flip to the coordinates of the bounding boxes from the annotations file.

  <a href="https://www.mdpi.com/2078-2489/11/2/125">Buslaev A, Iglovikov VI, Khvedchenya E, Parinov A, Druzhinin M, Kalinin AA (2020) Albumentations: Fast and flexible image augmentations. Information, 11, 1–20. </a>
