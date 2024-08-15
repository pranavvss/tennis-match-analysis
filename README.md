Tennis Analysis

>Introduction
>This project analyzes Tennis players in a video to measure their speed, ball shot speed and number of shots. This project will detect players and the tennis ball using YOLO and also utilizes CNNs to extract court keypoints. This hands on project is perfect for polishing your machine learning, and computer vision skills. 


Final oputput (Solved Yolov5 and Yolov8 not working together for both ball detection and Person detection)

Outut(Solved ball not properly detected)

https://github.com/user-attachments/assets/4204fce4-b8cc-47fb-ac7a-1ea3452018fa

Output (Video Analysis)

https://github.com/user-attachments/assets/376310e5-b490-4382-8697-9b39c1dc1023


Initial analysis

![image](https://github.com/user-attachments/assets/09723fd3-958c-4174-9475-c1fbc26e80d4)
![Screenshot 2024-08-15 195152](https://github.com/user-attachments/assets/f17c0fc6-f7d8-49df-b285-98d8b3e3504e)

Make sure you have a good data set

![image](https://github.com/user-attachments/assets/258f23bc-dc98-49ec-ad4e-2e45ede5cbe5)

I have used 
- Yolov8 for object detection [Visit here](https://github.com/ultralytics/yolov5?tab=readme-ov-file)
- Yolov5 for ball tracking (Yolov5i6u.pt to be precise) [Visit here](https://github.com/ultralytics/ultralytics)
- and i took tennis macth data for roboflow [Download the data](https://universe.roboflow.com/viren-dhanwani/tennis-ball-detection)


## Requirements
* python3.8
* ultralytics
* pytroch
* pandas
* numpy 
* opencv
