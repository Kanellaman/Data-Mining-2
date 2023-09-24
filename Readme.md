# Data Analysis and Classification

This code performs data analysis and classification tasks on a dataset of books. It includes the following main steps:

## Data Cleaning and Preprocessing

- Reads data from a CSV file (`books_1.Best_Books_Ever.csv`).
- Extracts and converts the `bookId` column to integers.
- Drops rows with missing values in specific columns.
- Extracts and preprocesses data for analysis, including handling genres and authors.

## Data Analysis

- Generates various insights and statistics about the dataset.
- Creates histograms and displays information about book ratings and page counts.

## Recommendation System

### Bigrams and Unigrams

- Utilizes the TF-IDF vectorization technique for bigrams and unigrams.
- Calculates cosine similarities between book descriptions.
- Provides book recommendations based on cosine similarity.

## Classification

### Random Forest, Naive Bayes, and Support Vector Classifier (SVC)

- Preprocesses textual data using Word2Vec.
- Performs classification using Random Forest, Naive Bayes, and Support Vector Classifier.
- Evaluates model performance with precision, recall, F1-score, and accuracy metrics.
