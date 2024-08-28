# MedGPT-Insights
This project involves scraping doctors' details from various hospitals.  The scraped data is cleaned and processed using pandas to remove duplicates, handle missing values, and standardize text formats. The final cleaned dataset is saved as a CSV file. Additionally, the project Use the cleaned data to train a Private GPT model.

# Project Documentation: Hospital Doctors Data Scraper and GPT-2 Model Training

## Overview

This project involves two main components:

1. Web Scraping and Data Cleaning:
- Scraped data on doctors from hospitals across various cities in India.
- Cleaned and processed the data for further use.

2. GPT-2 Model Training:
- Trained a GPT-2 model on the cleaned data.
- Saved the trained model for future use.

## Steps
- Data Collection
- Initial DataFrame Creation
- Data Inspection
- Removing Duplicates
- Handling Missing Values
- Dropping Unnecessary Columns
- Dropping Rows with Missing Values
- Model Setup
- Training Loop
- Model Evaluation and Saving

## Findings and Performance
Data Cleaning: Successfully removed duplicates, handled missing values, and cleaned the dataset for further use.
Model Training: Trained GPT-2 model with a learning rate of 5e-5 over 3 epochs. The loss improved over the epochs indicating successful training.

## Final Remarks
The data cleaning process ensured that the dataset was free of duplicates and missing values, making it suitable for training. The GPT-2 model was trained effectively, with performance metrics indicating good model learning. The trained model and tokenizer have been saved and are ready for further use or deployment.
