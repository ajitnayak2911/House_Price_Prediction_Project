# House Price Prediction Project

A web-based application for predicting house prices using a machine learning model. The application is built with Flask and leverages a pre-trained regression model to estimate housing prices based on user-inputted features.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Model Details](#model-details)
- [Requirements](#requirements)
- [License](#license)

## Demo

NA

## Features

- Predicts house prices based on user input of various features.
- Simple, user-friendly web interface.
- Built with Python, Flask, and a serialized (pickle) machine learning model.

## Project Structure

```
House_Price_Prediction_Project/
├── app.py                        # Main Flask application
├── house_price_prediction_model.pkl  # Pre-trained model file
├── requirements.txt              # Python dependencies
├── templates/                    # HTML template files (e.g., index.html)
└── venv/                         # Python virtual environment (optional)
```

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ajitnayak2911/House_Price_Prediction_Project.git
   cd House_Price_Prediction_Project
   ```

2. **Set up a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Flask app:**
   ```bash
   python app.py
   ```
   The application will be available at `http://127.0.0.1:5000/`.

## Usage

- Open the web application in your browser.
- Input the required house features in the form (e.g., CRIM, ZN, INDUS, CHAS, NOX, RM, AGE, DIS, RAD, TAX, PTRATIO, B, LSTAT).
- Submit the form to get the predicted house price.

## Model Details

- The model is loaded from `house_price_prediction_model.pkl` using Python's `pickle` module.
- The prediction is based on the following features:
  - CRIM, ZN, INDUS, CHAS, NOX, RM, AGE, DIS, RAD, TAX, PTRATIO, B, LSTAT
- The model was pre-trained (details about training data and algorithm can be provided here).

## Requirements

The main dependencies are listed in `requirements.txt`. Key packages include:
- Flask
- numpy
- pickle (standard Python library)

Install all requirements using:
```bash
pip install -r requirements.txt
```

## License

NA

---

*Feel free to contribute or raise issues to enhance this project!*
