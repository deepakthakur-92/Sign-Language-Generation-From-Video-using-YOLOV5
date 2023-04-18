# Sign-Language-Generation-From-Video-using-YOLOV5

## Introduction:
This project is focused on detecting objects in images and videos using Deep Learnign and computer vision techniques. The project uses a pre-trained YOLOV5 model and fine-tunes it on a custom dataset.


Data Source:

## Model:
YOLOv5 (You Only Look Once version 5) is a state-of-the-art object detection model that was introduced in 2020 by the developers of the YOLO (You Only Look Once) model series.

The YOLOv5 model is based on a single-stage object detector architecture, which means it performs the object detection task in a single forward pass through the network, unlike two-stage architectures such as Faster R-CNN. This makes YOLOv5 faster than other models while still maintaining high accuracy.

The YOLOv5 model uses a backbone network, which is a pre-trained feature extractor, that is based on the CSPDarknet53 architecture. The backbone is followed by several neck and head layers that perform the task of predicting the class and location of objects in the image.

The YOLOv5 model also uses a new anchor-free detection method called "ATSS" (Anchor-free Two-Stage Detection), which improves the model's accuracy and generalization ability.

Additionally, the YOLOv5 model also uses data augmentation techniques, such as Mosaic data augmentation, CutMix, and Mixup, to improve the robustness and generalization of the model.

Overall, YOLOv5 is a powerful and efficient object detection model that is suitable for real-time applications.

## Evaluation:
The model's performance is evaluated using metrics such as confusion matrix, precision, recall, and F1-score. The evaluation result saved in model evaluation results directory.

## Results
The results of the object detection are displayed in the form of bounding boxes around the detected objects and the corresponding class labels.

## Instructions to run the Project:
1. Clone the repository.
```
git clone https://github.com/deepakthakur-92
```
## STEP 02: 
Create an environment

```bash
conda create --prefix ./env python=3.7 -y
```

## STEP 03:
Activate the environment

```bash
conda activate ./env
```

## STEP 04: 
Install the requirements

```bash
pip install -r requirements.txt
```



Note:This is a basic object detection project which can be used as a starting point for more complex projects. You can add more features and improve the performance by using more advanced techniques.