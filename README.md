# Keratoconus Detection Using Deep Learning

A deep learning project for detecting Keratoconus eye disease using medical image classification techniques.  
This project applies Convolutional Neural Networks (CNN), ResNet, and MobileNetV2 models with TensorFlow/Keras to analyze corneal images and predict disease conditions.

---

## Features

- Keratoconus image classification
- Deep learning-based prediction
- CNN, ResNet, and MobileNetV2 models
- Flask-based prediction interface
- Medical image preprocessing
- Model evaluation and visualization

---

## Technologies Used

- Python
- TensorFlow / Keras
- CNN
- ResNet
- MobileNetV2
- Flask
- NumPy
- Matplotlib
- OpenCV

---

## Project Structure

```bash
Keratoconus_detech/
│
├── dataset/               # Medical image dataset
├── models/                # Trained models
├── screenshots/           # Demo images
├── app.py                 # Flask application
├── train_model.ipynb      # Training notebook
├── requirements.txt
└── README.md
```

---

## Model Workflow

1. Load and preprocess corneal images
2. Train deep learning models
3. Evaluate model performance
4. Predict Keratoconus conditions
5. Display prediction results through Flask interface

---

## Installation

### Clone Repository

```bash
git clone https://github.com/hoangan-110/Keratoconus_detech.git
cd Keratoconus_detech
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Usage

### Run Flask Application

```bash
python app.py
```

Then open:
```text
http://127.0.0.1:5000
```

---

## Screenshots

### Prediction Interface

![Prediction Interface](screenshots/interface.png)

### Prediction Result

![Prediction Result](screenshots/result.png)

---

## Model Evaluation

The project evaluates model performance using:
- Accuracy
- Loss Curves
- Confusion Matrix

### Example Metrics
- CNN Accuracy: 92%
- ResNet Accuracy: 95%
- MobileNetV2 Accuracy: 96%

---

## Future Improvements

- Improve dataset quality
- Add real-time prediction support
- Deploy using Streamlit or Hugging Face Spaces
- Optimize model performance

---

## Author

**Vu Hoang An**  
Information Technology Student  
Thai Nguyen University of Information and Communication Technology

GitHub: https://github.com/hoangan-110
