# Student Exam Performance Indicator

This project predicts student exam performance based on various demographic and educational factors using a machine learning model. It is built using **Flask** for the web interface, **Streamlit** for an alternative UI, and **TensorFlow** for training the prediction model.

## Table of Contents
- [Overview](#overview)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Overview

The **Student Exam Performance Indicator** aims to predict students' mathematics scores based on input features such as gender, ethnicity, parental education, lunch type, and preparation course completion status. The prediction model is a neural network trained using TensorFlow.

### Features:
- **Input**: Demographic and educational details (Gender, Race/Ethnicity, Parental Education, etc.)
- **Output**: Predicted Math Score
- **Model**: Pre-trained Neural Network model saved as `model.h5`
- **Web Interface**: Two UI options - Flask-based interface and a more interactive Streamlit UI.

## Project Structure

├── app.py # Flask application entry point ├── model.py # Model training and prediction logic ├── templates/ │ └── index.html # HTML for Flask web interface ├── static/ │ └── style.css # Custom styles for the web interface ├── model.h5 # Pre-trained machine learning model ├── requirements.txt # Python dependencies └── README.md # Project documentation


## Installation

### Prerequisites:
- **Python 3.8+**
- **pip** for managing Python packages

### Setup:
1. **Clone the repository:**
   ```bash
   git clone https://github.com/modiparth527/student_exam_performance.git
   cd student_exam_performance

2. **Create and activate a virtual environment (optional but recommended):**
    conda create -p venv python==3.8
    conda activate venv

3. **Install Dependencies**
    pip install -r requirements.txt

4. **Ensure the pre-trained model `model.h5` is present in the root directory. If not, follow the Model Training section to train and generate the model**

