# Data Analysis & Machine Learning Portfolio

This repository contains a collection of Jupyter Notebooks demonstrating skills in machine learning, data analysis, web scraping, and financial modeling. Each project focuses on a specific problem statement, ranging from deep learning for medical diagnosis to financial derivatives pricing.

## Project List

### 1. Model_Training__Practice.ipynb
**Project: ECG Arrhythmia Classification Model**

* **Description:** Implements a 1D Convolutional Neural Network (CNN) to classify heartbeat categories using the MIT-BIH Arrhythmia Database.
* **Technologies:** Python, TensorFlow/Keras, Pandas, Scikit-learn, Kaggle API.
* **Key Features:**
    * Automated dataset download via Kaggle API.
    * Data preprocessing including ECG signal normalization and One-hot encoding.
    * Construction of a CNN architecture with Convolutional layers, Max Pooling, and Dropout for regularization.
    * Model evaluation using Confusion Matrix, F1-score, and per-class accuracy metrics.

### 2. PTT財經版爬蟲.ipynb
**Project: PTT Finance Board Web Crawler**

* **Description:** An automated web scraper designed to extract article metadata and community interaction from the PTT Finance board.
* **Technologies:** Python, Requests, BeautifulSoup4.
* **Key Features:**
    * User interaction to specify the number of pages to scrape.
    * Deep scraping logic that visits individual article links to retrieve precise timestamps and reaction counts (Push/Boo).
    * Automated pagination handling to traverse through historical data.
    * Implementation of user-agent headers to bypass basic anti-scraping mechanisms.

### 3. UDN爬蟲.ipynb
**Project: UDN News Sequential Scraper**

* **Description:** An Object-Oriented news scraper that iterates through specific ID ranges to collect article data from UDN (United Daily News).
* **Technologies:** Python, Requests, BeautifulSoup4, JSON, Time.
* **Key Features:**
    * Object-Oriented Programming (OOP) design encapsulating request and parsing logic within a class.
    * Sequential traversal based on the numerical structure of article URLs.
    * Error handling mechanisms to skip invalid or deleted article IDs.
    * Data serialization and export to JSON format.

### 4. bankruptcy_decision_tree.ipynb
**Project: Corporate Bankruptcy Prediction Analysis**

* **Description:** Performs Exploratory Data Analysis (EDA) on a financial dataset containing over 90 indicators, aiming to prepare data for a bankruptcy prediction machine learning model.
* **Technologies:** Python, Pandas, Scikit-learn (Decision Tree).
* **Key Features:**
    * Loading and inspection of a high-dimensional financial dataset.
    * Data integrity checks to confirm data types and ensure no missing values.
    * Preparation steps for feature vectorization and decision tree classification.

### 5. 台中市停車場API.ipynb
**Project: Taichung Real-time Parking Availability Tool**

* **Description:** Interfaces with the Government Open Data API to provide real-time queries for parking lot availability in Taichung City.
* **Technologies:** Python, Requests, SSL, JSON parsing.
* **Key Features:**
    * API integration handling HTTPS requests and SSL certificate verification (SSL Context).
    * Data cleaning and parsing of complex nested JSON structures.
    * Interactive search function allowing users to filter parking lots by district (e.g., Beitun District) and view real-time vacancy rates and fee standards.

### 6. 選擇權CRR模型.ipynb
**Project: CRR Options Pricing Model & Volatility Analysis**

* **Description:** A comprehensive financial engineering project combining the theoretical CRR pricing model with empirical market data analysis.
* **Technologies:** Python, NumPy, yfinance.
* **Key Features:**
    * Implementation of the Cox-Ross-Rubinstein (CRR) Binomial Tree model to calculate theoretical prices for European and American options.
    * Integration with the Yahoo Finance API to fetch historical stock data (e.g., TSMC/2330.TW).
    * Calculation of daily returns and annualized volatility to provide empirical inputs for the pricing model.
