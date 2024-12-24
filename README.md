# RoBERTa-based Text Classification Model

This project demonstrates a text classification model using **RoBERTa-large**, a powerful transformer-based model. The model is designed to classify text into three categories and includes data preprocessing, training, evaluation, and testing steps.

## Features
- Preprocess text data (cleaning and tokenization).
- Fine-tune the RoBERTa-large model on a custom dataset.
- Evaluate the model with accuracy metrics and a confusion matrix.
- Test the model on new input text.

## Dataset
The dataset used in this project is called `labeled_data.csv` and contains the following columns:

- `index`
- `count`
- `hate_speech`
- `offensive_language`
- `neither`
- `class`
- `tweet`

As part of the preprocessing, the dataset is reduced to only the `class` and `cleaned_tweet` columns. The `cleaned_tweet` column contains preprocessed text, including tokenization and removal of unnecessary content.


## How to Use

1. Open the Jupyter Notebook file (`RoBERTa-based_Text_Classification_Model.ipynb`).
2. Follow the steps to:
   - Preprocess the dataset (cleaning and reducing to `class` and `cleaned_tweet` columns).
   - Train the RoBERTa-large model on the dataset.
   - Evaluate its performance.
   - Test it on custom input text.


## Future Work
- Extend the dataset for additional classes.
- Implement a more user-friendly interface for testing.
- Experiment with other transformer models (e.g., BERT, GPT).

## Acknowledgments
- [Hugging Face Transformers](https://huggingface.co/transformers/)
- [Kaggle Dataset](https://www.kaggle.com/datasets/mrmorj/hate-speech-and-offensive-language-dataset)
- [Stanford](https://web.stanford.edu/class/archive/cs/cs224n/cs224n.1234/final-reports/final-report-169358304.pdf)
