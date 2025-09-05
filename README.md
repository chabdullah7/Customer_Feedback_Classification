# Customer Feedback Classification

## Overview
This project is an end-to-end system for classifying and analyzing customer feedback (NPS and Google reviews). It includes data cleaning, embeddings with FAISS, retrieval for similar complaint categories, classification with LLMs, and sentiment analysis. A Flask API is also provided for real-time single and bulk predictions.

## Features
- Data Preprocessing: Cleaning and preparing raw customer reviews  
- Embeddings & Retrieval: Using FAISS for efficient similarity search  
- Classification: LLM-powered classification of feedback into categories  
- Sentiment Analysis: Identifies customer sentiment (positive, negative, neutral)  
- Flask API: Provides endpoints for real-time and batch predictions  

## Tech Stack
- Python  
- FAISS  
- Flask  
- Large Language Models (LLMs)  
- Pandas / Numpy / Scikit-learn  

## Usage
1. Clone the repo  
   `git clone https://github.com/chabdullah7/Customer_Feedback_Classification.git`  
   `cd Customer_Feedback_Classification`  

2. Install dependencies  
   `pip install -r requirements.txt`  

3. Run the Flask API  
   `python app.py`  

4. Send feedback data via API endpoint to get predictions  

## Author
Abdullah  
GitHub: github.com/chabdullah7  
LinkedIn: linkedin.com/in/ch-abdullah-b537951a
