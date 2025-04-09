# Fake News Detection Project

## Overview

This project aims to build a machine learning model capable of predicting whether a news snippet or headline is real or fake. By leveraging natural language processing (NLP) techniques and supervised learning, the model analyzes textual data to classify news snippets accurately.

## Dataset

The dataset used for this project contains labeled examples of real and fake news snippets. The data is balanced, ensuring an equal representation of both classes, which helps improve the model's performance and reduces bias.

## Methodology

1. **Text Vectorization**:  
    The text columns in the dataset were vectorized using **TF-IDF (Term Frequency-Inverse Document Frequency)**. This technique transforms the textual data into numerical features that can be fed into machine learning models.

2. **Model Selection**:  
    Several machine learning models were tested to determine the best-performing algorithm. After evaluation, **Logistic Regression** achieved the highest accuracy score and was selected as the final model.

## Results

The Logistic Regression model demonstrated strong performance on the dataset, making it the optimal choice for this task. The balanced dataset and TF-IDF vectorization contributed significantly to the model's accuracy.


## Conclusion

This project successfully demonstrates the use of machine learning and NLP techniques to detect fake news. The Logistic Regression model, combined with TF-IDF vectorization, provides a reliable solution for this classification task.

## Presentation
The presentation can be found in the Presentation folder.
