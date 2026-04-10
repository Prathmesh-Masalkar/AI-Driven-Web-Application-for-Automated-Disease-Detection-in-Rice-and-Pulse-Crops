# 🌾 AI-Driven Web Application for Automated Disease Detection in Rice and Pulse Crops

An intelligent web application that detects diseases in **rice and pulse crops using deep learning and image processing**. The system analyzes leaf images and predicts crop diseases using trained CNN models.

---

# 🚀 Features

* 🌿 Detect diseases in **Rice and Pulse crops**
* 🧠 Deep Learning based image classification
* 📷 Upload crop leaf image for prediction
* ⚡ Instant disease prediction results
* ☁ Streamlit web interface
* 🔥 Firebase / Firestore integration for storing data
* 🤖 Separate trained models for rice and pulses

---

# 🛠 Tech Stack

### Programming

* Python

### Machine Learning

* TensorFlow
* Keras
* Convolutional Neural Networks (CNN)

### Image Processing

* OpenCV
* Pillow (PIL)
* NumPy

### Web Application

* Streamlit

### Database

* Firebase Firestore

---

# 📂 Project Structure

```
AI-Disease-Detection
│
├── app.py                 # Main Streamlit application
├── utils.py               # Helper functions
├── firebase_config.py     # Firebase configuration
├── firestore_db.py        # Firestore database functions
│
├── models
│   ├── rice_model1.keras
│   └── pulses_model1.keras
│
├── models_training
│   ├── rice.ipynb
│   └── pulses.ipynb
│
├── static
│   ├── rice_classes.txt
│   ├── pulses_classes.txt
│   └── images
│
├── requirements.txt
└── README.md
```

---

# ⚙ Installation

### 1 Clone the Repository

```
git clone https://github.com/YOUR-USERNAME/AI-Driven-Web-Application-for-Automated-Disease-Detection.git
```

### 2 Go to Project Folder

```
cd AI-Driven-Web-Application-for-Automated-Disease-Detection
```

### 3 Install Dependencies

```
pip install -r requirements.txt
```

### 4 Run the Application

```
streamlit run app.py
```

---

# 📊 How It Works

1. User uploads an image of a crop leaf.
2. The image is preprocessed using **OpenCV and NumPy**.
3. The trained **CNN model** analyzes the image.
4. The model predicts the **disease class**.
5. The result is displayed on the web interface.

---

# 🚧 Challenges

* Finding reliable crop disease datasets
* Handling image variations (lighting, background)
* Model accuracy optimization
* Integrating machine learning with web interface

---

# 🔮 Future Improvements

* Support more crop types
* Mobile application development
* Real-time detection using camera
* Disease treatment recommendations
* Multilingual support for farmers

