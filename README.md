# YOLOv4-Tiny-Cloud-Training-Tutorial
[![Train Custom Model In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1XldR7IoXt3gdqGPG0OfMzFOUJ6iqrSVr?usp=sharing)

In this project we walk through the steps of training a custom Yolov4-tiny model.

PROJECT: 
Many species of sea turtles have become endagered and coastlines are extensive to monitor by foot.
Computer vision algorithms can be run on an edge device for detection and classification of endangered species tracks on the beaches.

As we will be running the model in real time onboard a drone we have to consider afew limiting factors like computational power,video quality and detection time for this i have chosen to use a one stage detector Yolov4-Tiny.

PIPELINE:

1) Data:
        - from video footage 250 images were taken
        - labelled (with https://github.com/DanC6312/    Yolo-Voc_image_labelling)
        - Augmented an aditional 450 images
2) Model:
        - YoloV4-Tiny (https://arxiv.org/ftp/arxiv/papers/2011/2011.04244.pdf)
3) Training:
        - Trained on Colab free GPU using the notebook above
4) Results: 
![Example Of YOLOv4-Tiny Detections](images/green_turtle_118.png)
![Example Of YOLOv4-Tiny Detections](images/Hawksbill_Track_160.png)
5) Conclusion:
        - With the limited amount of data available the accuracy of classification is low
### YOLOv4-Tiny Video Example
<p align="center"><img src="videos/result.gif"\></p>

Cheers
Dan
