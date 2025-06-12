# 🩸 Blood Group Detection Using Fingerprint

A deep learning-based web application that predicts a user's blood group from a fingerprint image using a trained ResNet model. This project removes the need for traditional blood testing by offering a contactless and quick alternative using biometric data.

## 🔍 Overview

This project simplifies the blood group detection process by using fingerprint images. With a deep learning model (ResNet), the system can predict one of the eight major blood types (A+, A−, B+, B−, AB+, AB−, O+, O−) based on fingerprint patterns.

## 🚀 Features

- 🔐 User Authentication (Sign Up / Login)
- 🏠 Clean and simple home page
- 📷 Upload fingerprint image for prediction
- 🤖 ResNet-based deep learning blood group classifier
- 📊 Displays prediction result after upload

## 🛠️ Tech Stack

| Layer        | Technologies                            |
|--------------|------------------------------------------|
| Frontend     | HTML, CSS, JavaScript                   |
| Backend      | Python, Flask                           |
| Deep Learning| ResNet, TensorFlow/Keras                |
| Deployment   | Localhost (optional: Render/Heroku)     |

## 📂 Folder Structure

/project-root
├── backend/

│ ├── uploads/ # Stores uploaded fingerprint images

│ ├── public/

│ │ ├── index.html # Home page

│ │ ├── signin.html # Sign-in/Sign-up page

│ │ └── upload.html # Upload page

│ ├── app.py # Flask server for model prediction

│ └── model/ # Trained ResNet model

 
 2.Open in Browser
Visit: http://localhost:5000

⚙️ How It Works
1.User logs in or signs up

2.Redirects to home page

3.User clicks on upload fingerprint button

4.Image is sent to Flask backend

5.ResNet model processes image and predicts blood group

Prediction result is shown on the page
