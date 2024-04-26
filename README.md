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

## Install the required dependencies:
Copy code
pip install -r requirements.txt
## Usage
Data Analysis and Model Training:
Explore the Jupyter notebooks in the notebooks directory for data analysis, preprocessing, model training, and evaluation.
Flask Web Application:
Navigate to the flask_app directory.
## Run the Flask app:
Access the web application at http://localhost:5000 in your web browser.
## Output Images
![home](https://github.com/RoddaAvinash/SentimentAnalysisOfRealTimeFlipkartProductReviews/assets/155214451/1ba060b3-657b-47db-89b1-d8c8c14cbfb3)
![review1](https://github.com/RoddaAvinash/SentimentAnalysisOfRealTimeFlipkartProductReviews/assets/155214451/cd96bb90-1e1e-4afd-9cfc-23fb64cc0690)
![review1output](https://github.com/RoddaAvinash/SentimentAnalysisOfRealTimeFlipkartProductReviews/assets/155214451/96e16ce1-26f6-467f-b8b7-2ee96263d12a)
![review2](https://github.com/RoddaAvinash/SentimentAnalysisOfRealTimeFlipkartProductReviews/assets/155214451/a5291179-4c13-4a7f-bf95-d0b6750619ca)
![review2output](https://github.com/RoddaAvinash/SentimentAnalysisOfRealTimeFlipkartProductReviews/assets/155214451/a2d580e9-5015-40d0-9589-fe2de80a4389)

## Model Deployment
Deploy the Flask web application and trained models on an AWS EC2 instance for accessibility over the internet.
Ensure proper configuration and security measures are in place for the deployed application.
YOu can access My AWS Deployment of THe Project: http://54.153.162.63:5000/
## Acknowledgements
Thanks to Innomatics Research Labs and Kanav Bansal for their support and guidance throughout this project.

