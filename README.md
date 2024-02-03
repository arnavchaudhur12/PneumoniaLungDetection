
91% Accuracy
Pneumonia Detection Deep Learning Project
Project Overview
This project utilizes deep learning to detect pneumonia in chest X-ray images. The Convolutional Neural Network (CNN) model is trained to classify images into two categories: Normal and Pneumonia.

![image](https://github.com/arnavchaudhur12/PneumoniaLungDetection/assets/95077985/d810742b-0954-41b3-ada8-5f0aac4f9d52)

Dependencies
Ensure you have the following libraries installed:

TensorFlow
Keras
NumPy
Matplotlib
OpenCV
Install dependencies using:

bash
Copy code
pip install numpy matplotlib opencv-python tensorflow keras
Model Overview
The CNN model architecture includes an input layer, two Conv2D layers, a Dense layer, and an output layer. The model is compiled using the Adam optimizer and binary crossentropy loss function.

Data Generation
Training and validation data are generated using ImageDataGenerator to enhance the model's performance.

Model Training
The model is trained using the generated data with a specified number of epochs.

Model Evaluation
Evaluate the model on the provided test data to assess its performance.

Results
The project aims to detect pneumonia in chest X-ray images using deep learning techniques. Feel free to explore and enhance the model for further improvements.

Visualization
Visualize the training and validation accuracy, as well as loss, to understand the model's learning progress.

Heatmap Generation
Generate a heatmap to visualize the areas of focus in the input image.

Conclusion
This project serves as a foundational example for pneumonia detection using deep learning. Feel free to customize this README further according to your preferences and specific details about your project.

Author
Arnab Choudhury
