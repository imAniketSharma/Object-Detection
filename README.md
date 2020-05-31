## Car detection using YOLO - Autonomous driving

**We learn to**:
- Use object detection on a car detection dataset
- Deal with bounding boxes


### YOLO
"You Only Look Once" (YOLO) is a popular algorithm because it achieves high accuracy while also being able to run in real-time. This algorithm "only looks once" at the image in the sense that it requires only one forward propagation pass through the network to make predictions. After non-max suppression, it then outputs recognized objects together with the bounding boxes.

<img src="nb_images/architecture.png" style="width:700px;height:400;">
<caption><center> <u> **Figure 1** </u>: **Encoding architecture for YOLO**<br> </center></caption>


#### Visualizing bounding boxes

<img src="nb_images/anchor_map.png" style="width:200px;height:200;">
<caption><center> <u> **Figure 2** </u>
    

#### Non-max suppression

<img src="nb_images/non-max-suppression.png" style="width:500px;height:400;">
<caption><center> <u> **Figure 3** </u>
    
    
### Note:

The yolo.h5 file can be generated using the YAD2K repository here: https://github.com/allanzelener/YAD2K

Steps how to do it on windows:

* Clone the above repository to your computer

* Download the yolo.weights file from here: http://pjreddie.com/media/files/yolo.weights

* Download the yolo.cfg file form here: https://raw.githubusercontent.com/pjreddie/darknet/master/cfg/yolo.cfg

* Copy the downloaded weights and cfg files to the YAD2K master directory