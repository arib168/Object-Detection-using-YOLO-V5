# State-of-the-art Object detection to extract license plate number and rider details using YOLO V5 and Resnet-50 image classifier

Problem statement : To extract the license plate information if the motorcycle rider is not wearing a helmet (Rider or Pillion or both not wearing).

Steps followed : 
Do custom object detection using YOLO V5 to detect only the motorcycle riders on the road. Also detect the license number plate and the rider's head. 
Then apply image classification using the Resnet50 Image Classifier to determine if the rider is wearing a helmet or not. 
If the rider (including pillion rider if available) is not wearing a helmet, then an image of the rider's license number plate will be saved in a folder number_plates.
Another image of the rider with the motorcycle will be saved in another folder called rider_pictures. 
The data can then be sent to the database of the concerned authorities to impose fines accordingly for the offenders. 

Further scope to improve : Add the overspeeding detection part using YOLO V5.

# MODEL WORKING :

<img
src="./bike_gif.gif"
/>


Given below are the required weight files which are already trained to perform realtime object detection 

# Download Model and other necessary files from link below:
After downloading these files put them all in the main folder and now you can run the code.


yolov5 weight file for motorcycle rider, license plate and head detection: 

Small version:

https://drive.google.com/file/d/1LbX-YRBTgJZEIqQqmCpNq4CNQzoiA8p5/view?usp=sharing


Medium Version:

https://drive.google.com/file/d/16ZDjUcX7vXQYPJ557dooN0em4mJmbJt7/view?usp=sharing

Classification Model: (resnet50)

https://drive.google.com/file/d/1OuOpgq99E5VKPtwUuFZ0GGety3YWjIQn/view?usp=sharing






