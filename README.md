# Spam Detection

## Project Overview

The primary objective of this project is to classify SMS messages as either spam or not spam. The model is trained on a dataset of labeled SMS messages and uses various NLP techniques to preprocess the text before classification.

## Tools and Techniques

### Tools:
- **Python**: The main programming language used.
- **Jupyter Notebook**: Used for running the code and visualizing the results.
- **Spacy**: A popular NLP library used for text processing tasks like tokenization, lemmatization, and stop word removal.
- **pandas**: A library for data manipulation and analysis, used for handling the dataset.

### Techniques:
- **Text Preprocessing**:
  - **Tokenization**: Splitting text into words.
  - **Lemmatization**: Reducing words to their root form using Spacy.
  - **Stopword Removal**: Removing common words that don't affect classification.
  
- **Data Handling**:
  - The dataset (`spam_sms.xlsx`) is loaded with pandas, containing labeled SMS messages (spam/ham).
  
- **Modeling**:
  - A machine learning classifier is trained on the processed data using text vectorization and training algorithms.

- **Evaluation**:
  - Model performance is assessed with accuracy, precision, recall, and F1-score.

## Project Structure

- `Spam_Detection.ipynb`: Jupyter notebook with the implementation.
- `spam_sms.xlsx`: SMS dataset for training.
- `requirements.txt`: Lists dependencies.
