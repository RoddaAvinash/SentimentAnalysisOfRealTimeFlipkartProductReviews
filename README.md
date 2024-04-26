## Sentiment Analysis of Real-time Flipkart Product Reviews
## Overview
This project aims to perform sentiment analysis on real-time product reviews sourced from Flipkart. By analyzing customer sentiments, we aim to gain insights into product features that contribute to customer satisfaction or dissatisfaction. The project involves data preprocessing, model training, and deploying a Flask web application for real-time sentiment analysis.

## Dataset
The dataset consists of 8,518 reviews for the "YONEX MAVIS 350 Nylon Shuttle" product from Flipkart. Each review includes features such as Reviewer Name, Rating, Review Title, Review Text, Place of Review, Date of Review, Up Votes, and Down Votes.

## Project Structure
data: Contains the dataset used for analysis.
notebooks: Jupyter notebooks for data analysis, preprocessing, model training, and evaluation.
flask_app: Flask web application for real-time sentiment analysis.
models: Trained machine learning and deep learning models.
requirements.txt: List of Python dependencies required for the project.
## Installation
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/sentiment-analysis-flipkart.git
Navigate to the project directory:
bash
Copy code
cd sentiment-analysis-flipkart
## Install the required dependencies:
Copy code
pip install -r requirements.txt
## Usage
Data Analysis and Model Training:
Explore the Jupyter notebooks in the notebooks directory for data analysis, preprocessing, model training, and evaluation.
Flask Web Application:
Navigate to the flask_app directory.
## Run the Flask app:
Copy code
python app.py
Access the web application at http://localhost:5000 in your web browser.
## Model Deployment
Deploy the Flask web application and trained models on an AWS EC2 instance for accessibility over the internet.
Ensure proper configuration and security measures are in place for the deployed application.
## Acknowledgements
Special thanks to Innomatics Research Labs and Kanav Bansal for their support and guidance throughout this project.

