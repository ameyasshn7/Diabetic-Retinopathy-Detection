# Diabetic-Retinopathy-Detection with Deep Learning

# BACKGROUND AND MOTIVATION

Diabetic retinopathy is an eye condition caused by diabetes that damages the retina, potentially leading to blindness. Analyzing it using image processing techniques in Python is vital for early detection and treatment. Python's capabilities allow for the automated analysis of retinal images, identifying signs of retinopathy, such as microaneurysms or hemorrhages. This early diagnosis enables timely intervention, preventing vision loss. Python's efficiency in handling large datasets and its accessibility make it a valuable tool in managing diabetic retinopathy on a large scale, improving patient outcomes and reducing the burden on healthcare systems.




This repository contains a deep learning project for detecting diabetic retinopathy, a common diabetes-related eye condition. The goal of this project is to classify retinal images into one of five classes: No DR, Mild, Moderate, Severe, and Proliferative DR.

# Key Features:
Data Preprocessing: The code preprocesses retinal images by applying techniques such as cropping, resizing, Gaussian blur, and circle drawing to enhance image quality.

Data Augmentation: To boost the model's performance, data augmentation is employed, including horizontal and vertical flips, rotation, and zoom.

Model Architecture: The model architecture is based on DenseNet121, a pre-trained convolutional neural network (CNN) that has proven effective for image classification tasks.

Training and Evaluation: The model is trained using a generator to handle large datasets and is evaluated using metrics like accuracy, precision, and recall. Confusion matrices provide insights into classification performance.

Test Prediction and Visualization: The code allows you to make predictions on test images and visualize the results. Each test image is displayed with its target and predicted class for easy assessment.

# How to Use:
Clone this repository.
Install the required dependencies listed in requirements.txt.
Run the provided scripts to preprocess data, train the model, and make predictions.
Results:
After training for a specified number of epochs, the model achieves an accuracy of approximately 72.73% on the validation dataset. This demonstrates its effectiveness in diagnosing diabetic retinopathy.

# Acknowledgments:
Kaggle Diabetic Retinopathy Detection Dataset

