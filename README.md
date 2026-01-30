# AI-Object-Detection-using-MIT-App-Inventor-
An Android application that uses machine learning to recognize everyday objects in real-time using the device's camera

###**📱 Project Overview**

This project implements an AI-based object recognition system using MIT App Inventor and Google's Teachable Machine. The app can identify six different categories of objects with confidence percentages displayed for each detection.

**🎯 Features**

Real-time Object Recognition: Identifies objects using a custom-trained ML model

Multiple Object Categories: Recognizes 6 different object types

Image Selection: Images directly acess from mobile cam for analysis

Confidence Scores: Displays percentage confidence for each object category

User-Friendly Interface: Simple and intuitive design

🔍 Recognized Objects

The app can identify the following objects:

📚 Book

🌸 Flower Vase

🍾 Bottle

📱 Mobile Phone

✏️ Marker

❌ No Objects (background)

🛠️ Technologies Used

MIT App Inventor: Visual programming platform for Android app development

Teachable Machine: Google's web-based tool for training machine learning models

TMIC Extension: TeachableMachineImageClassifier extension for MIT App Inventor

Deep Learning: Image classification using trained neural network

📋 Prerequisites

MIT App Inventor account (https://appinventor.mit.edu/)

Android device 

Internet connection for initial setup

🚀 Setup Instructions
Step 1: Train the Model on Teachable Machine

Visit Teachable Machine
Select "Image Project" → "Standard image model"
Create 6 classes:

Book
Flower Vase
Bottle
Mobile Phone
Marker
Nothing (no objects)


Use your webcam to capture multiple images (at least 50-100) for each class from different angles and lighting conditions
Click "Train Model" and wait for training to complete
Click "Export Model" → Select "Upload my model"
Copy the generated model URL
