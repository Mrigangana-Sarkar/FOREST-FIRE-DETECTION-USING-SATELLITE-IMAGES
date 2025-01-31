Forest Fire Detection Using Satellite Images
Project Overview
This project leverages satellite imagery to detect forest fires using machine learning techniques, specifically Convolutional Neural Networks (CNNs). By analyzing satellite images, the model automatically classifies whether a region is affected by fire, providing valuable early warnings for forest management and disaster prevention.

Objective
The aim of this project is to develop an automated system that can detect forest fires from satellite images. This system is crucial for early intervention and monitoring forest health in real-time.

Technologies Used
Convolutional Neural Networks (CNNs): A type of deep learning model particularly well-suited for image classification.
TensorFlow/Keras: These frameworks are used for implementing and training the CNN model.
Flask: A lightweight web framework used to deploy the model as a web application.
Python: The programming language for developing the model, data processing, and deploying the web app.
Dataset
The dataset used for this project consists of satellite images labeled with two categories: images showing forest fires and those without. The images are preprocessed for training the CNN model.

Model Description
The CNN model is trained using the dataset of satellite images to learn features that differentiate between fire and non-fire images. Once trained, the model is integrated into a web interface, enabling users to upload satellite images for prediction.

Key Features
Image Classification: The model classifies whether an uploaded satellite image depicts a forest fire.
Web Interface: A Flask-based web app that allows users to interact with the model.
Real-Time Predictions: The model provides predictions on new satellite images as they are uploaded.
How It Works
Users upload a satellite image via the web interface.
The CNN processes the image and identifies patterns linked to forest fires.
The system classifies the image and outputs a prediction of whether a forest fire is present.
Installation and Setup
Follow the provided instructions to set up the project environment, install dependencies, and run the application. The steps ensure the project can be replicated and run locally.

Future Work
Real-time satellite image feed integration.
Model improvement through advanced architectures for higher accuracy.
Deployment on cloud platforms to scale the solution.


