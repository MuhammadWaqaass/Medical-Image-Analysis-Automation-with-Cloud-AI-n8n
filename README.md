# AI for Early Skin Disease Detection – Cloud API with n8n 🌐🤖

This project demonstrates how a **trained AI model for skin disease detection** can be deployed as a **scalable cloud API** and automated using **n8n workflows**.

The goal is to make **early skin disease detection** accessible, fast, and usable from anywhere — without requiring powerful hardware or manual steps.

---
<img width="952" height="445" alt="aaa" src="https://github.com/user-attachments/assets/1b9b3a80-3a99-41ab-b0d4-5d5b22561b69" />
---
<img width="959" height="442" alt="cccvcv" src="https://github.com/user-attachments/assets/797f092c-5e09-4c12-a063-7d294afe90da" />


## 🔍 Project Overview

The system allows users to upload a **skin image** and receive:
- The **predicted skin disease class**
- A **confidence score** for the prediction

Everything runs in the cloud and can be connected to automation tools like **n8n** for hands-free processing.

---

## 🧠 Step 1: Train the AI Model

- A deep learning model was trained on skin images
- The model learns to recognize different skin conditions
- Focus on **early detection** to support faster diagnosis

---

## 🌐 Step 2: Convert Model into a Web API

- A lightweight web service was created using **FastAPI**
- The API accepts an image file
- The image is processed and passed to the AI model
- The API returns:
  - Disease class
  - Prediction confidence

---

## ☁️ Step 3: Cloud Deployment (Google Cloud Run)

- The entire application is packaged into a container
- Deployed on **Google Cloud Run**

### Benefits:
- No powerful machine needed
- Auto-scales with traffic
- Secure and production-ready
- Accessible from anywhere

---

## 🧪 Step 4: Test & Use

You can send an image to the API and receive:
- Which skin disease it might be
- How confident the model is about the prediction

This makes testing and real-world usage simple and fast.

---

## 🔁 Step 5: Automation with n8n

- The cloud API is connected to **n8n**
- n8n automatically:
  - Sends images to the API
  - Receives predictions
  - Can store, notify, or trigger next actions

No manual coding required after setup.

---

## ✅ Why This Matters

- Faster early skin disease detection
- Remote monitoring support
- Cloud-based and scalable
- Easy integration with workflows
- AI accessible anytime, anywhere

This project shows the power of **AI + Cloud + Automation** working together.

---

## 🚀 Technologies Used

- TensorFlow / Keras
- FastAPI
- Google Cloud Run
- Docker
- n8n Workflow Automation
- Python

---

## 📌 Use Cases

- Telemedicine platforms
- Health monitoring systems
- AI-powered diagnostics
- Automated medical workflows

---

## 📬 Contact

Feel free to connect if you want to:
- Extend this project
- Integrate it into workflows
- Discuss AI in healthcare
