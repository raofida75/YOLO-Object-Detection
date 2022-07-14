<div align="center">
<h1> YOLO Object Detection </h1>
<i><h3>YOLO, A real time object detection algorithm.</h3></i>
</div>

![](https://github.com/raofida75/YOLO-Object-Detection/blob/main/Images/detection.jpg)

The YOLO algorithm ‘only looks once’ at the image since it requires only a single forward propagation to detect objects. The YOLO algorithm employs a Convolutional Neural Network to predict class probabilities and multiple bounding boxes using image features. Traditional deep learning approaches for object detection, such as R-CNN and DPM, were typically too slow for real-time tasks. In this project, we will show how to use the most recent YOLOv4 algorithm for vehicle detection systems, which is one of the most important techniques used in self-driving cars.

## Requirements
- Python
- tensorflow 
- numpy, 
- opencv


## Dataset

Download the pre-trained YOLO v4 weights file from this <a href="https://sourceforge.net/projects/darknet-yolo.mirror/files/darknet_yolo_v4_pre/yolov4.weights/download" target="_blank"><b>link</b></a> and place it in the `/pretrained_models` folder.

YOLO Model has been pre trained on coco dataset.
The COCO dataset consists of 80 labels, including:

- Cars 
- trucks
- Airplanes
- People
- Stop signs
- Animals

You can find a full list of what YOLO trained on the COCO dataset can detect <a href="https://github.com/pjreddie/darknet/blob/master/data/coco.names" target="_blank"><b>using this link.</b></a>

## Sample Output
<p align="center">
<img src="https://github.com/raofida75/YOLO-Object-Detection/blob/main/Images/output.png" width="750"/>
</p>

## Deliverables
For detailed explanation you can refer to my report <a href="https://github.com/raofida75/YOLO-Object-Detection/blob/main/docs/Final%20Report.pdf"
target="_blank"><b>here.</b></a>

## Achievement
The report presented by my group was able to secure second position in the entire mechanical engineering department. There were around 52 groups in total.

[Link to my presentation](https://www.youtube.com/watch?v=c6kijZ1vYnQ)

## References
YOLO research paper
  - [link to the research paper](https://github.com/raofida75/YOLO-Object-Detection/blob/main/docs/YOLO%20Paper.pdf)

Convolutional Neural network course by Deeplearning.ai 
  - [link to the course](https://www.coursera.org/learn/convolutional-neural-networks?specialization=deep-learning)
