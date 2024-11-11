# Classify_Waste_Products_Using_Transfer_Learning
Develop an automated waste classification model that can accurately differentiate between recyclable and organic waste based on images. By the end of this project, you will have trained, fine-tuned, and evaluated a model using transfer learning, which can then be applied to real-world waste management processes.

Table of contents

Classify Waste Products Using Transfer Learning
Introduction
Project Overview
Aim of the Project
Objectives
Tasks List
Sample Task: Sample screenshot showing code and output
Setup
Installing Required Libraries
Importing Required Libraries
Task 1: Print the version of tensorflow
Background
Create a model for distinguishing recyclable and organic waste images
Dataset
Importing Data
Define configuration options
Loading Images using ImageGeneratorClass
ImageDataGenerators
Task 2: Create a test_generator using the test_datagen object
Task 3: Print the length of the train_generator
Pre-trained Models
VGG-16
Task 4: Print the summary of the model
Task 5: Compile the model
Fit and train the model
Plot loss curves for training and validation sets (extract_feat_model)
Task 6: Plot accuracy curves for training and validation sets (extract_feat_model)
Fine-Tuning model
Task 7: Plot loss curves for training and validation sets (fine tune model)
Task 8: Plot accuracy curves for training and validation sets (fine tune model)
Evaluate both models on test data
Task 9: Plot a test image using Extract Features Model (index_to_plot = 1)
Task 10: Plot a test image using Fine-Tuned Model (index_to_plot = 1)
Authors
Introduction
In this project, you will classify waste products using transfer learning.

Project Overview
EcoClean currently lacks an efficient and scalable method to automate the waste sorting process. The manual sorting of waste is not only labor-intensive but also prone to errors, leading to contamination of recyclable materials. The goal of this project is to leverage machine learning and computer vision to automate the classification of waste products, improving efficiency and reducing contamination rates. The project will use transfer learning with a pre-trained VGG16 model to classify images.

Aim of the Project
The aim of the project is to develop an automated waste classification model that can accurately differentiate between recyclable and organic waste based on images. By the end of this project, you will have trained, fine-tuned, and evaluated a model using transfer learning, which can then be applied to real-world waste management processes.

Final Output: A trained model that classifies waste images into recyclable and organic categories.

Learning Objectives
After you complete the project, you will be able to:

Apply transfer learning using the VGG16 model for image classification.
Prepare and preprocess image data for a machine learning task.
Fine-tune a pre-trained model to improve classification accuracy.
Evaluate the model’s performance using appropriate metrics.
Visualize model predictions on test data.
By completing these objectives, you will be able to apply the techniques in real-world scenarios, such as automating waste sorting for municipal or industrial use.

Tasks List
To achieve the above objectives, you will complete the following tasks:

Task 1: Print the version of tensorflow
Task 2: Create a test_generator using the test_datagen object
Task 3: Print the length of the train_generator
Task 4: Print the summary of the model
Task 5: Compile the model
Task 6: Plot accuracy curves for training and validation sets (extract_feat_model)
Task 7: Plot loss curves for training and validation sets (fine tune model)
Task 8: Plot accuracy curves for training and validation sets (fine tune model)
Task 9: Plot a test image using Extract Features Model (index_to_plot = 1)
Task 10: Plot a test image using Fine-Tuned Model (index_to_plot = 1)
