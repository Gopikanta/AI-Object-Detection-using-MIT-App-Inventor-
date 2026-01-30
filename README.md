# AI-Object-Detection-using-MIT-App-Inventor-

An Android application that uses machine learning to recognize everyday objects in real-time using the device's camera

**📱 Project Overview**

This project implements an AI-based object recognition system using MIT App Inventor and Google's Teachable Machine. The app can identify six different categories of objects with confidence percentages displayed for each detection.

**🎯 Features**

* **Real-time Object Recognition:** Identifies objects using a custom-trained ML model

* **Multiple Object Categories:** Recognizes 6 different object types

* **Image Selection:** Images directly acess from mobile cam for analysis

* **Confidence Scores:** Displays percentage confidence for each object category

* **User-Friendly Interface:** Simple and intuitive design

**🔍 Recognized Objects**

The app can identify the following objects:

- 📚 Book

- 🌸 Flower Vase

- 🍾 Bottle

- 📱 Mobile Phone

- ✏️ Marker

- ❌ No Objects (background)

**🛠️ Technologies Used**

* **MIT App Inventor:** Visual programming platform for Android app development

* **Teachable Machine:** Google's web-based tool for training machine learning models

* **TMIC Extension:** TeachableMachineImageClassifier extension for MIT App Inventor

* **Deep Learning:** Image classification using trained neural network

**📋 Prerequisites**

- MIT App Inventor account (https://appinventor.mit.edu/)

- Android device 

- Internet connection for initial setup

**🚀 Setup Instructions**

**Step 1:** Train the Model on Teachable Machine

- Visit Teachable Machine
  
- Select "Image Project" → "Standard image model"

- Create 6 classes:

   - Book
     
   - Flower Vase
     
   - Bottle
     
   - Mobile Phone
     
   - Marker
     
   - Nothing (no objects)

- Use your webcam to capture multiple images (at least 50-100) for each class from different angles and lighting conditions
  
- Click "Train Model" and wait for training to complete
  
- Click "Export Model" → Select "Upload my model"
  
- Copy the generated model URL

**Step 2:** Set Up MIT App Inventor

- Go to MIT App Inventor

- Create a new project named "ObjectRecognition" or similar
  
- Import the TMIC extension:

- Go to Extensions → Import Extension
  
- Upload the TeachableMachineImageClassifier extension (.aix file)

  **🎓 How It Works**

- Model Training: Images are collected for each object category and used to train a convolutional neural network via Teachable Machine
  
- Model Deployment: The trained model is hosted on Google's servers and accessed via a URL
  
- Image Classification: When a user selects an image, it's sent to the TMIC extension
  
- Inference: The extension processes the image through the neural network
  
- Results Display: Confidence scores for each category are returned and displayed

**📊 Model Performance**

- The model accuracy depends on:

  - Quality and quantity of training images
    
  - Diversity of angles, lighting, and backgrounds during training
    
  - Similarity between training and real-world images

**Tips for Better Accuracy:**

- Capture at least 100+ images per class
  
- Use varied lighting conditions
  
- Include different angles and distances
  
- Avoid cluttered backgrounds during training
