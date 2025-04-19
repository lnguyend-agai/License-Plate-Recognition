# License-Plate-Recognition

# Introduction
This repository contains the source code and results for a License Plate Recognition system built using Computer Vision.

## Model Folder: 
Includes the dataset and Google Colab notebooks with code for training the model.
## Result Folder: 
Stores the output of the trained model, showcasing detection and recognition performance.

# Tech Stack
YOLOv4: To dectect the license Plate.

MobileNet V2: To recognize the number and character on License Plate.

Image processing (OpenCV libray).

# Flow chart

![image](https://github.com/user-attachments/assets/654f6884-0a91-4b66-9997-47ef03c03aac)


# Result

## 1. License Plate Detection:
Trained a YOLOv4 model to accurately detect license plates in images.

![image](https://github.com/user-attachments/assets/3e5f5b33-7650-4c16-b2dc-e7a8dcf1a4ae)

## 2. Image Processing:
Used OpenCV to preprocess license plate images, segmenting characters with contour detection and filtering.

![image](https://github.com/user-attachments/assets/6fee7b11-76e0-456d-b1f0-d064d949972e)

## 3. Character Recognition:
Applied a trained MobileNetV2 model to recognize characters within green bounding boxes.

![image](https://github.com/user-attachments/assets/6cc6aae7-fa5c-4d0e-a8be-0db581b91c12)

## 4. The final result

A robust system that detects license plates, segments characters, and recognizes them automatically.

![image](https://github.com/user-attachments/assets/1edbf4e3-7c32-4f59-b6dd-2ea61ccfbc4f)

![image](https://github.com/user-attachments/assets/8fc9d4a1-2aaa-4ad5-9fe4-248e784d2e0f)


