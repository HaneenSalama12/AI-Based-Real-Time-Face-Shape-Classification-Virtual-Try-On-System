# 👓 AI-Based Real-Time Face Shape Classification & Virtual Try-On System

An AI-powered computer vision system that detects a person's **face shape in real time** and provides a **virtual glasses try-on experience**.

The system combines deep learning, computer vision, and facial analysis to classify face shapes and visualize suitable eyeglasses directly on the user's face.

---

## 📌 Project Overview

Choosing suitable eyeglasses can be difficult because different frame styles complement different face shapes.

This project aims to provide an intelligent solution by:

1. Detecting the user's face.
2. Classifying the face shape using a trained AI model.
3. Recommending suitable glasses based on the detected face shape.
4. Applying the selected glasses virtually in real time.

The model training and the real-time application are organized into separate parts of the project.

---

## ✨ Features

* 🎯 Real-time face shape classification
* 👤 Face detection and facial landmark analysis
* 🧠 Deep Learning-based classification
* 👓 Face-shape-based glasses recommendation
* 🕶️ Virtual glasses try-on
* 📷 Real-time camera interaction
* 📐 Facial landmark-based glasses positioning
* 💻 Python-based implementation

---

## 🧠 Face Shapes

The system classifies faces into the following categories:

* Oval
* Round
* Square
* Heart
* Oblong

---

## 🔄 System Workflow

```text
             Input Camera
                  │
                  ▼
            Face Detection
                  │
                  ▼
        Facial Landmark Detection
                  │
                  ▼
        Face Shape Classification
                  │
                  ▼
        Detected Face Shape
                  │
                  ▼
       Glasses Recommendation
                  │
                  ▼
          Virtual Try-On
                  │
                  ▼
           Final Output
```

---

## 🏗️ Project Structure

```text
AI-Based-Real-Time-Face-Shape-Classification-Virtual-Try-On-System/
│
├── Training/
│   └── Training.ipynb
│
├── app/
│   ├── project.ipynb
│   └── glassess/
│
├── README.md
└── requirements.txt
```

### 📂 Training

Contains the notebook used for:

* Data preprocessing
* Model preparation
* Model training
* Model evaluation
* Saving the trained model

### 📂 App

Contains the real-time application notebook used for:

* Loading the trained model
* Face detection
* Face shape prediction
* Glasses selection
* Virtual glasses overlay

### 📂 Glasses

Contains the glasses assets used by the virtual try-on component.

---

## 🛠️ Technologies Used

| Technology   | Purpose                          |
| ------------ | -------------------------------- |
| Python       | Main programming language        |
| YOLO         | Deep learning / object detection |
| OpenCV       | Image and video processing       |
| MediaPipe    | Facial landmark detection        |
| NumPy        | Numerical operations             |
| Pandas       | Data processing                  |
| Matplotlib   | Visualization                    |
| Google Colab | Model training                   |

---

## 🤖 Model Training

The model was trained using a face-shape dataset containing multiple face-shape categories.

The training pipeline includes:

```text
Dataset
   ↓
Data Preprocessing
   ↓
Model Training
   ↓
Validation & Evaluation
   ↓
Best Model
   ↓
Real-Time Inference
```

The trained model is saved as:

```text
best.pt
```

> **Note:** The trained model (`best.pt`) can be downloaded from the link below:

[Download the trained model](https://drive.google.com/drive/folders/1fEBCYEi-W9u5rck7lRMZNYrujq6cf3FF?usp=sharing)

---

## 🕶️ Virtual Try-On

After predicting the user's face shape, the application selects suitable glasses and overlays them on the detected face.

Facial landmarks are used to determine the appropriate position and scale of the glasses.

This allows the glasses to follow the user's face during real-time camera movement.

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/HaneenSalama12/AI-Based-Real-Time-Face-Shape-Classification-Virtual-Try-On-System.git
```

### 2. Navigate to the project

```bash
cd AI-Based-Real-Time-Face-Shape-Classification-Virtual-Try-On-System
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Application

Open the application notebook:

```text
app/project.ipynb
```

Make sure the trained model `best.pt` is available in the expected location before running the notebook.

---

## 📊 Training Notebook

The complete training pipeline is available in:

```text
Training/Training.ipynb
```

It contains the preprocessing and model training workflow.

---

## 📸 Demo

Screenshots and demonstration videos of the real-time virtual try-on system can be added here.

---

## 🔮 Future Improvements

* Improve face-shape classification accuracy
* Add more glasses styles
* Improve glasses alignment and tracking
* Add more advanced recommendation logic
* Build a web-based interface
* Deploy the model as an online application
* Add support for additional face shapes and accessories

---

## 👩‍💻 Author

**Haneen Salama**

Computer Engineering Student | AI & Machine Learning Enthusiast

GitHub: [HaneenSalama12](https://github.com/HaneenSalama12)

---

## 📄 License

This project is for educational and portfolio purposes.
