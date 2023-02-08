# Object Detection in Rainy Images based on Multistage Deraining Network

Object detection is the process of detecting objects in a given image or video. Most of the existing autonomous vehicles are using cameras and deep learning methods for detecting the objects. Object detection in rainy environment is a challenging task due to the heavy degradations caused by rain streaks of different size,direction and densities. This leads to the blurring of background scenes and limits the accuracy of object detection models. In this work a method for object detection and recognition in rainy environment is proposed. This work consists of two modules, deraining module and object detection module. Deraining is performed using a multi stage architecture based on supervised attention module, object detection is performed using YOLOv7 algorithm. Single image deraining is the task of recovering clean rain free background image from rain degraded images. To address the degradations caused by rain, deraining module uses multi-stage architecture which progressively restore the image using supervisory attention signals from ground truth images. This work addresses the challenging image deraining task into multiple subtasks by introducing three different stages along with object detection module. Further this method analyzes the effect of rain in high-level computer vision task like object detection and the detection performance in rainy and derained image is calculated. The proposed method is evaluated quantitatively and qualitatively. Comparative analysis for object detection is done with YOLOv5 and YOLOv7 and the results are quantified. Experiment result demonstrates that proposed method obtained good performance compared with existing methods.
