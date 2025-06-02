# VEHICLE INSURANCE PREDICTION MLOPS

*Predict vehicle insurance outcomes with a robust MLOps pipeline and FastAPI-powered web interface.*

[![Python](https://img.shields.io/badge/python-3.12%2B-blue.svg)](https://python.org)
[![Status](https://img.shields.io/badge/status-active-success.svg)](#)

## 🛠️ Built with

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white)

---

## 📋 Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)

---

## Overview

This project is a machine learning application designed to predict vehicle insurance outcomes. It integrates a complete MLOps pipeline for model training, prediction, and deployment, with a user-friendly FastAPI web interface for seamless interaction.

![Demo Output](https://github.com/user-attachments/assets/002d303e-f255-46b9-9324-b5c147e0b8b5)

---

## Key Features

- 🌐 **FastAPI Web Interface**: Provides endpoints for data input, model training, and prediction.
- 🤖 **Machine Learning Pipeline**: Utilizes scikit-learn for robust model training and prediction.
- 📊 **Data Visualization**: Generates insights with matplotlib, plotly, and seaborn.
- ☁️ **Cloud Integration**: Connects to AWS and MongoDB for scalable storage solutions.
- ⚙️ **Configuration Management**: Streamlines settings with PyYAML.
- 📜 **Logging & Error Handling**: Implements comprehensive logging and custom error handling.

---

## Project Structure

- `app.py`: Main FastAPI application with endpoints for the web interface.
- `src/`: Source code for data access, configuration, logging, and ML pipelines.
- `templates/`: HTML templates for web page rendering.
- `static/`: Static files (CSS, JavaScript) for front-end styling.
- `logs/`: Directory for application logs.
- `artifact/`: Stores model artifacts and trained models.
- `notebook/`: Jupyter notebooks for exploratory data analysis.

---

## Getting Started

### Prerequisites

- **Python Version**: 3.12 or higher
- **Package Manager**: pip
- **Environment Variables**:
  - AWS access and secret keys
  - MongoDB connection string

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/tirth013/MLOps-First-Project.git
   cd MLOps-First-Project
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure environment variables**:
   - Set AWS credentials:
     ```bash
     export AWS_ACCESS_KEY_ID=<your-access-key-id>
     export AWS_SECRET_ACCESS_KEY=<your-secret-access-key>
     ```
   - Set MongoDB connection:
     ```bash
     export MONGODB_URI=<your-mongodb-uri>
     ```

### Usage

1. **Run the application**:
   ```bash
   python app.py
   ```

2. **Access the web interface**:
   Open your browser and navigate to `http://localhost:<port>`.

3. **Interact with the application**:
   - **Data Input**: Enter vehicle data via the main form.
   - **Model Training**: Trigger training via the `/train` endpoint.
   - **Prediction**: Submit data to receive insurance predictions.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your improvements or bug fixes.

---

**[↑ Return to top](#vehicle-insurance-prediction-mlops)**
