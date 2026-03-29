# Face-Stylization-Model


---

## 📌 Project Overview

This project implements **face stylization using JoJoGAN**, enabling users to transform facial images into various artistic styles such as anime, cartoon, and custom styles using deep learning techniques.

---

## 🚀 Features

### 🔹 Core Functionalities

* Upload input face image
* Apply pre-trained artistic styles
* Perform custom style transfer using a reference image

### 🔹 Advanced Features

* Semantic editing (Eyes / Lips regions)
* Style Blending in required proportions
* Interactive web interface using Gradio

---

## 🧠 Technologies Used

### 🔹 Programming & Frameworks

* Python
* PyTorch

### 🔹 Deep Learning Models

* JoJoGAN
* e4e Encoder

### 🔹 Libraries & Tools

* OpenCV
* Mediapipe


---

## 📂 Project Structure

```
JoJoGAN/
│
├── models/                # Pretrained model files (.pt)
├── app.py                 # Streamlit web application
├── e4e_projection.py      # Encoder projection logic
├── notebook.ipynb         # Google Colab notebook
```

---

## ⚙️ Setup Instructions

### 🔹 Step 1: Open Notebook

* Open the project notebook in **Google Colab**

### 🔹 Step 2: Run Cells

* Execute all cells sequentially

### 🔹 Step 3: Add Models

* Upload required `.pt` model files into the `models/` folder

### 🔹 Step 4: Launch Application

* Run the Gradio app to start stylization

---

## 📸 Results

The system generates high-quality stylized face images based on selected styles and user inputs.

---

## 💡 Future Improvements

* Add more artistic style models
* Improve real-time processing speed
* Deploy as a fully functional web application

---

## 👩‍💻 Author

**Goda Hasitha**
