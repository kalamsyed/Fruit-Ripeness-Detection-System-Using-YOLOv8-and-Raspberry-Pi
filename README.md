Fruit Ripeness Detection System Using YOLOv8 & Raspberry Pi

Project Overview
This project presents a real-time fruit detection and classification system using the YOLOv8 (You Only Look Once v8) deep learning model deployed on a Raspberry Pi 3B+. The system detects fruits such as apple, banana, mango, melon, orange, peach, and pear, and classifies them into four quality stages: Fresh, Semifresh, Semirotten, and Rotten.

The solution integrates computer vision, deep learning, and embedded systems with a conveyor belt mechanism for automated sorting, making it suitable for smart agriculture and post-harvest quality control.


Objectives
- Detect multiple types of fruits in real time  
- Classify fruit ripeness into four stages  
- Deploy YOLOv8 on Raspberry Pi for edge AI processing  
- Automate sorting using a DC motor and conveyor belt  
- Reduce manual effort and post-harvest losses  

Technologies Used
- **Hardware:** Raspberry Pi 3B+, USB Camera, L298N Motor Driver, DC Motor  
- **Software:** Python, OpenCV, YOLOv8 (Ultralytics)  
- **ML/DL:** Convolutional Neural Networks (CNN), Transfer Learning  
- **Other:** GPIO, Embedded Linux (Raspberry Pi OS)



How the System Works
1. Camera captures live fruit images  
2. YOLOv8 detects the fruit and predicts its ripeness stage  
3. Raspberry Pi processes the model output in real time  
4. Conveyor belt motor is triggered based on classification  
5. Fruit is sorted automatically



Install Dependencies
pip install ultralytics opencv-python
