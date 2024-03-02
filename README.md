# SMS Spam Detection Project

## Overview

This project, addressing SMS spam detection using a Bayesian approach, was developed as part of an internship task provided by **CodeSoft**. The primary objective is to create an accurate system for classifying SMS messages as either spam or ham (non-spam) through the application of natural language processing techniques.

## Dataset

The dataset used in this project is sourced from Kaggle and includes SMS messages labeled as spam or ham. Ensure that you have the dataset downloaded or linked correctly before running the code.

**Kaggle Dataset Link:** [SMS Spam Collection Dataset](https://www.kaggle.com/dataset-link)

## Project Structure

- **Notebooks:**
  - `01_data_preprocessing.ipynb`: Code for data loading, cleaning, and exploration.
  - `02_spam_filter.ipynb`: Implementation of the Bayesian Spam Filter and classification example.

- **Data:**
  - The dataset should be placed in this folder or follow instructions on how to obtain it.

## Getting Started

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/sms-spam-detection.git
   ```

2. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

3. Navigate to the relevant notebooks (`01_data_preprocessing.ipynb` and `02_spam_filter.ipynb`) and run them sequentially.

## Dependencies

Ensure you have the following Python libraries installed:

```bash
pip install numpy pandas nltk
```

## Project Workflow

1. **Loading and Displaying Data:**
   - Load the SMS dataset and display initial information.

2. **Data Cleaning:**
   - Remove duplicate rows for data cleanliness.

3. **Text Cleaning:**
   - Implement a function (`clean_text`) to preprocess SMS messages.

4. **Bayesian Spam Filter Implementation:**
   - Define a `BayesianSpamFilter` class for training and classification.
   - Implement Laplace smoothing for word probability calculations.

5. **Spam Classification Example:**
   - Demonstrate the application of the Bayesian Spam Filter on an example SMS message.

## Project Objectives

- Develop an effective SMS spam detection system.
- Utilize natural language processing techniques for text cleaning and feature extraction.
- Implement a Bayesian Spam Filter for accurate classification.

## Notes

- The code contains a duplicated section; consider removing one for clarity.
- Customize the project structure or code as needed for your preferences and requirements.

## Acknowledgments

Special thanks to **CodeSoft** for providing the internship task and fostering an environment that encourages practical application of machine learning and data science concepts. This project serves as a valuable learning experience and contributes to the development of skills essential in the field.