# Vehicle Insurance Prediction MLOps Project

## Demo Output Image
![image](https://github.com/user-attachments/assets/002d303e-f255-46b9-9324-b5c147e0b8b5)
## Overview
This project is a machine learning application designed to predict vehicle insurance outcomes. It leverages FastAPI for the web interface and implements a complete MLOps pipeline for model training and prediction.

## Features
- **Web Application**: Built with FastAPI, providing endpoints for data input, model training, and prediction.
- **Machine Learning**: Utilizes scikit-learn for model training and prediction.
- **Data Visualization**: Supports data visualization with matplotlib, plotly, and seaborn.
- **Cloud Integration**: Integrates with cloud storage using boto3 and pymongo.
- **Configuration Management**: Manages configurations with PyYAML.
- **Logging and Error Handling**: Implements a robust logging system and custom error handling.

## Project Structure
- `app.py`: Main application file with FastAPI endpoints.
- `src/`: Source code directory containing various modules for data access, configuration, logging, and pipelines.
- `templates/`: HTML templates for rendering web pages.
- `static/`: Static files such as CSS and JavaScript.
- `logs/`: Directory for storing application logs.
- `artifact/`: Directory for storing model artifacts.
- `notebook/`: Jupyter notebooks for exploratory data analysis.

## Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/tirth013/MLOps-First-Project.git
   cd MLOps-First-Project
   ```

2. **Install Dependencies**:
   Ensure you have Python installed, then run:
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure AWS and MongoDB Keys**:
   - **AWS Keys**: Set your AWS access and secret keys as environment variables:
     ```bash
     export AWS_ACCESS_KEY_ID=<your-access-key-id>
     export AWS_SECRET_ACCESS_KEY=<your-secret-access-key>
     ```
   - **MongoDB Keys**: Set your MongoDB connection string as an environment variable:
     ```bash
     export MONGODB_URI=<your-mongodb-uri>
     ```

4. **Run the Application**:
   Start the FastAPI server:
   ```bash
   python app.py
   ```

5. **Access the Application**:
   Open your browser and navigate to `http://localhost:<port>` to access the web interface.

## Usage
- **Data Input**: Use the main form to input vehicle data for prediction.
- **Model Training**: Trigger model training via the `/train` endpoint.
- **Prediction**: Submit the form to receive insurance prediction results.

## Dependencies
- Python packages listed in `requirements.txt`, including FastAPI, scikit-learn, pandas, numpy, and more.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.
