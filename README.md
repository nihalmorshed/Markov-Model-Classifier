# Markov Model Classifier for Poetry

This project is a Natural Language Processing (NLP) application that classifies poetry texts from Edgar Allan Poe and Robert Frost using a Markov Model. The project demonstrates text preprocessing, tokenization, and model evaluation processes. The main goal of this project is to demonstrate the effectiveness of Markov Models in classifying literary texts

## Dataset

The dataset consists of poems by Edgar Allan Poe and Robert Frost. The text files are downloaded directly from the internet:

- [Edgar Allan Poe](https://raw.githubusercontent.com/lazyprogrammer/machine_learning_examples/master/hmm_class/edgar_allan_poe.txt)
- [Robert Frost](https://raw.githubusercontent.com/lazyprogrammer/machine_learning_examples/master/hmm_class/robert_frost.txt)

## Project Structure

1. **Data Collection and Preprocessing**:
    - Download and read the text files.
    - Preprocess the text by removing punctuation and converting it to lowercase.
    - Split the data into training and testing sets.

2. **Tokenization**:
    - Tokenize the text and assign a unique index to each word.

3. **Model Training and Evaluation**:
    - Train a Markov Model on the training data.
    - Evaluate the model using metrics such as confusion matrix and F1 score.

## Results

The model is evaluated on the testing set, providing insights into its performance in classifying the poems correctly.

## Conclusion 

This project intends to exhibit the implementation of a Markov Model for text classification, highlighting the steps of data preprocessing, tokenization, and model evaluation in NLP.

## Dependencies

The project requires the following libraries:

- numpy
- matplotlib
- scikit-learn

You can install the necessary dependencies using:
```bash
pip install numpy matplotlib scikit-learn
