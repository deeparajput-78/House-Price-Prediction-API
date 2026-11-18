# House-Price-Prediction-API

🏡 House Price Prediction API

Predict House Prices Using Machine Learning and FastAPI

📌 Project Overview

House Price Prediction API is a Machine Learning-based web application built using Python and FastAPI.

The project predicts house prices based on different property features such as area, number of bedrooms, bathrooms, stories, parking, furnishing status, and other facilities.

It uses a real-world housing dataset from Kaggle to train a Machine Learning regression model and provides predictions through REST API endpoints.


✨ Features

Predict house prices based on property details.

REST API built using FastAPI.

Real-world Kaggle housing dataset.

Machine Learning regression model.

Interactive API documentation using Swagger UI.

Input validation using Pydantic.

Easy-to-use API endpoints.


🛠️ Technologies Used

Technology

Purpose

Python

Programming Language

FastAPI

Backend Framework

Pandas

Data Processing

NumPy

Numerical Operations

Scikit-learn

Machine Learning

Uvicorn

ASGI Server

Pydantic

Data Validation

HTML & CSS

Frontend (if implemented)


📊 Dataset Information

Dataset: Housing Prices Dataset

Source: Kaggle

Dataset contains:

545 records

13 columns


📁 Project Structure

House-Price-Prediction-API/
│
├── main.py
├── model/
│   └── house_price_model.pkl
│
├── dataset/
│   └── Housing.csv
│
├── templates/
│
├── static/
│   └── style.css
│
├── requirements.txt
├── README.md
└── .gitignore
