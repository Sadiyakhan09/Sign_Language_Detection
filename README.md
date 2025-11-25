# ✋🔤 Sign Language Recognition Using CNN & OpenCV

This project is a **real-time Sign Language Recognition System** that detects hand gestures from a webcam and converts them into text using **Deep Learning (CNN)** and **Computer Vision (OpenCV)**.
It is built to support accessibility and help bridge communication between hearing-impaired individuals and others.

---

## 🚀 Features

* 🎥 **Real-time sign detection** from webcam
* 🤖 **CNN-based deep learning model** for gesture classification
* ✋ Hand segmentation and preprocessing using OpenCV
* ⚡ Fast and accurate predictions
* 📊 Visualized training results (accuracy/loss graphs)
* 🧩 Easy to train, update, and use

---

## 🛠️ Technologies Used

* **Python**
* **TensorFlow / Keras**
* **OpenCV**
* **NumPy**
* **Matplotlib**
* **Machine Learning (CNN)**
* **Computer Vision**

---

## 📂 Project Structure

```
.
├── dataset/
│   ├── A/
│   ├── B/
│   ├── C/
│   └── ... (gesture folders)
│
├── model/
│   └── sign_language_model.h5
│
├── src/
│   ├── train.py
│   ├── detect.py
│   ├── utils.py
│
├── README.md
└── requirements.txt
```

---

## 🧠 How the System Works

### 1️⃣ **Capture Frame**

The webcam streams real-time frames using OpenCV.

### 2️⃣ **Preprocess the Image**

* Convert to grayscale
* Resize to 64×64
* Normalize pixel values

### 3️⃣ **CNN Model Prediction**

The trained CNN model predicts the corresponding letter/sign.

### 4️⃣ **Display Output**

The detected letter is displayed on the live video feed.

---

## 📊 Model Training

* Trained on custom dataset of hand gestures
* Used **Convolutional Neural Networks**
* Optimizer: Adam
* Loss function: Categorical Crossentropy
* Training graphs plotted using Matplotlib

Example training command:

```bash
python src/train.py
```

---

## ▶️ Running Real-Time Detection

Make sure your model file exists in the `model/` folder.

Run:

```bash
python src/detect.py
```

Your webcam will open and start predicting signs.

---

## 🧪 Requirements

Install dependencies:

```bash
pip install -r requirements.txt
```

Example `requirements.txt`:

```
opencv-python
tensorflow
numpy
matplotlib
```

---

## 🎯 Skills Gained During This Project

* Building an end-to-end ML pipeline
* Training deep learning models
* Real-time computer vision processing
* Debugging and optimization
* Understanding AI + accessibility applications

---

## 📸 Screenshots / Demo



---

<img width="800" height="450" alt="image" src="https://github.com/user-attachments/assets/0998eadd-f1c7-46cc-8be2-05f4f689ca24" />
<img width="800" height="513" alt="image" src="https://github.com/user-attachments/assets/f4877881-63e1-45f1-833e-00da23e4fa53" />
<img width="800" height="540" alt="image" src="https://github.com/user-attachments/assets/f5eecfaa-cf58-415d-a954-a42f8805f1d2" />
<img width="1126" height="977" alt="image" src="https://github.com/user-attachments/assets/2999d287-10df-4190-b0d7-dff060bc2c36" />
<img width="1172" height="966" alt="image" src="https://github.com/user-attachments/assets/8cfc2d71-1e17-4cea-bf49-1cf634a19f6e" />
<img width="1213" height="979" alt="image" src="https://github.com/user-attachments/assets/8c01f952-71df-49c4-8987-fdfd8f4c1fa7" />
<img width="1280" height="938" alt="image" src="https://github.com/user-attachments/assets/0983094d-b40f-4dc7-b35e-6fc284fdba36" />
<img width="1280" height="933" alt="image" src="https://github.com/user-attachments/assets/47d56380-853c-4ece-8445-5908ec8d485f" />
<img width="1280" height="949" alt="image" src="https://github.com/user-attachments/assets/9b0c31fc-47fa-4a22-8f5c-1e62f4eae668" />




