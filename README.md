## Title of the Project
Food Quality Analysis Using Image Processing
## About
This project is designed to analyze the quality of food products (specifically fruits and biscuits) using image processing and machine learning techniques. It aims to provide real-time quality assessment by detecting cracks in biscuits and categorizing fruits as fresh or spoiled. Key Features:

Real-Time Fruit Quality Detection:
    The system uses YOLO (You Only Look Once), a deep learning-based object detection algorithm, to detect and classify fruits in images.
    It analyzes the color, texture, and brightness of the detected fruits to determine whether they are fresh or spoiled.

Biscuit Crack Detection:
    The system uses image processing techniques such as edge detection to identify cracks in biscuits.
    It applies methods like Canny edge detection to assess the presence of cracks based on the edges found in the image.

Quality Classification:
    The system classifies the quality of fruits and biscuits into categories such as "Fresh", "Spoiled", and "Cracked".
    For fruits, it checks factors like color, saturation, brightness, and contrast to assess freshness.
    For biscuits, the system detects cracks by analyzing the image’s edges.

User Interface:
    The application features a Graphical User Interface (GUI) built using Tkinter where users can upload images of fruits and biscuits for analysis.
    It provides the ability to view uploaded images and results of the analysis, including the number of fresh and spoiled fruits or cracked biscuits.

Data Preprocessing:
    The uploaded images are preprocessed by adjusting brightness and contrast to enhance the quality of detection.
    Techniques like Local Binary Pattern (LBP) and HSV color space conversion are used to extract relevant features for accurate classification.

Machine Learning and Deep Learning:
    The system integrates machine learning (ML) for quality assessment and classification tasks.
    YOLOv5, a pre-trained model, is used for real-time object detection of fruits.
    The system also employs image feature extraction methods (like color analysis and texture features) to classify fruit quality.

Future Enhancements:
    Expanding the system to handle a wider variety of fruits and food items.
    Integrating machine learning models for automatic classification and prediction of food quality, improving the accuracy and scalability of the system.
    Enhancing real-time processing for large image datasets and live video streams

## Features
<!--List the features of the project as shown below-->
- Implements advance neural network method.
- A framework based application for deployment purpose.
- High scalability.
- Less time complexity.
- A specific scope of Chatbot response model, using json data format.

## Requirements
Hardware Requirements:

Computer/Laptop: Minimum 4 GB RAM (8 GB or higher recommended). Processor: Intel i5 or higher (or equivalent). GPU: Optional but recommended for faster image processing (e.g., NVIDIA GPU for YOLO). Camera or Imaging Device: For capturing real-time images of fruits and vegetables. Storage: At least 10 GB free space for storing datasets and software.

Software Requirements:

Python: Version 3.8 or higher. Python Libraries: OpenCV: For image processing. NumPy: For numerical computations. PIL: For image handling in the GUI. Tkinter: For creating the GUI application. Torch: For YOLOv5 implementation. skimage: For texture analysis. pandas: For handling YOLO's detection output. YOLOv5 Model: Pretrained weights for object detection. Image Dataset: Labeled images of fresh and spoiled fruits/vegetables.

## System Architecture
<!--Embed the system architecture diagram as shown below-->

![Screenshot 2023-11-25 133637](https://github.com/<<yourusername>>/Hand-Gesture-Recognition-System/assets/75235455/a60c11f3-0a11-47fb-ac89-755d5f45c995)


## Output
![image](https://github.com/user-attachments/assets/8f859f79-c02e-47d0-a327-d471e87267d3)

#### Output1 - Name of the output
![image](https://github.com/user-attachments/assets/346937b2-013a-41ec-9482-e51fc1174e5f)



#### Output2 - Name of the output
![image](https://github.com/user-attachments/assets/78b5d071-359c-4206-ae78-ad6e49c5c12c)


Detection Accuracy: 96.7%
Note: These metrics can be customized based on your actual performance evaluations.


## Results and Impact
Accurate Quality Detection:

The system can successfully analyze the quality of fruits and vegetables by detecting spoilage based on visual features like texture, color, and contrast.
Fresh and spoiled items are identified with a higher accuracy after refining the detection algorithm.
Grading System:

The system assigns quality grades (A, B, C, D) to batches of fruits and vegetables based on the spoilage ratio, providing clear and actionable insights.
Item Counting:

The program detects and counts the number of fresh and spoiled items when multiple objects are present in the uploaded image.
GUI Functionality:

A user-friendly interface has been developed, enabling users to upload images and receive detailed quality analysis results in real-time.
Improved Spoilage Detection:

Enhanced algorithms have resolved previous inaccuracies, such as fresh items being classified as spoiled (e.g., fresh bananas now correctly identified as fresh).


## Articles published / References
1. N. S. Gupta, S. K. Rout, S. Barik, R. R. Kalangi, and B. Swampa, “Enhancing Heart Disease Prediction Accuracy Through Hybrid Machine Learning Methods ”, EAI Endorsed Trans IoT, vol. 10, Mar. 2024.
2. A. A. BIN ZAINUDDIN, “Enhancing IoT Security: A Synergy of Machine Learning, Artificial Intelligence, and Blockchain”, Data Science Insights, vol. 2, no. 1, Feb. 2024.




