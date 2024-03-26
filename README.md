# GreenTaxiPricePredictionAnalysis
Performed EDA, and created models using Python on a merged data of 8 million rows from 2019,2020 and 2021 data to predict the taxi fare and most profitable pickup locations. Built machine learning models using scikit-learn library to predict congestion surcharge based on pickup, drop-off locations and ride booking density with 83% accuracy.

## Notebooks Overview

### 1. Classification Code Highlighting Feature Importance
- **Purpose:** Focuses on classifying and highlighting the importance of various features within a dataset.
- **Key Operations:**
  - Creation and manipulation of dataframes.
  - Importing taxi zone and holiday data for analysis.

### 2. Location Coordinates Using Pickup Location
- **Purpose:** Determines location coordinates based on taxi pickup locations.
- **Key Operations:**
  - Installation and usage of the `geopy` library for location data.
  - Data filtering to ensure quality and relevance of pickup locations.

### 3. Price Prediction with Visualizations
- **Purpose:** Aims to predict prices through the integration of visual data analysis techniques.
- **Key Operations:**
  - Reading and merging data from multiple files.
  - Preparing and visualizing data to understand trends and patterns.

### 4. Price Prediction with ML Models
- **Purpose:** Develops machine learning models to predict pricing accurately.
- **Key Operations:**
  - Comprehensive importation of libraries for data analysis and model training.
  - Dataframe creation and data importation setup for model training.

## Getting Started

To use these notebooks effectively, ensure you have a Python environment with Jupyter Notebook or JupyterLab installed. Dependencies vary by notebook but generally include pandas, numpy, matplotlib, scikit-learn, and geopy. It's recommended to create a virtual environment and install the required packages via pip:


Open the notebooks in Jupyter to view detailed instructions and execute the code cells in sequence. Each notebook contains specific setup instructions and comments to guide you through the processes.

## Contributing

Contributions to this project are welcome! Whether it's extending the analysis, improving the machine learning models, or fixing bugs, your input is valued. Please feel free to fork the repository, make your changes, and submit a pull request.

