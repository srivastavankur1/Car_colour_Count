# Object and Gender Count

## Description
This project is a model designed to predict the color of cars in traffic, count the number of cars in the traffic signal, identify the gender distribution of people in the traffic signal, and predict the number of other vehicles apart from cars.
![image](https://github.com/Swarni12/Car-Color-and-Count/blob/main/Output_Image.png)



## Problem Statement
- Predict car color in traffic.
- Count the number of cars in the traffic signal.
- Identify the gender distribution of people in the traffic signal.
- Predict the number of other vehicles apart from cars.

## Approach
- **Car Color Prediction**:
  - Red color cars are marked as blue and vice versa.
- **Car Count**:
  - Count the total number of cars detected in the traffic signal.
- **Gender Distribution**:
  - Utilize face detection to determine the gender of individuals present in the traffic signal.
- **Other Vehicles Count**:
  - Identify and count other vehicles apart from cars.

## Implementation
- **Programming Language**: Python
- **Frameworks and Libraries**:
  - OpenCV
  - Streamlit
  - Pandas
  - NumPy
  - PIL (Python Imaging Library)
  - Ultralytics YOLO (You Only Look Once) Object Detection
- **Pre-trained Models**:
  - YOLOv8 for object detection
  - Pre-trained face and gender classification models (caffemodels)

## Project Code
- The project code is available in the `app.py` file.

## Usage
1. Install the required libraries mentioned in the `requirements.txt`.
2. Run the `app.py` file.
3. Upload a video file containing traffic footage.
4. View the real-time analysis of car colors, car count, gender distribution, and other vehicles count in the traffic signal.

## Google Drive
https://drive.google.com/drive/folders/100gaT3kkvmVIjBtkyRZEPP5E1-xGfqDV?usp=sharing

Some of the files were too large that's why I have attached google drive link.

## Author
Ankur Srivastava
