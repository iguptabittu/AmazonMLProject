# Text Classification and Ensemble Modeling

This project demonstrates text classification using various machine learning models and ensemble techniques. The workflow includes data preprocessing, training multiple models, evaluating their performance, and visualizing the results with confusion matrices and ROC curves. Additionally, the project implements an autocomplete function using trigram analysis.

## Features

- **Text Classification** using the following models:
  - Logistic Regression
  - Naive Bayes
  - Neural Network (MLP)
- **Ensemble Learning** with a Voting Classifier to combine the individual models
- **Model Evaluation** with performance metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
- **Data Visualizations**:
  - Confusion Matrix
  - ROC Curve
- **Natural Language Processing (NLP)** techniques:
  - Trigram generation from a text corpus
  - Autocomplete functionality based on trigram frequency

## Dataset

The project uses the [20 Newsgroups dataset](https://scikit-learn.org/stable/datasets/real_world.html#newsgroups-dataset) available in the `sklearn.datasets` library. This dataset contains around 20,000 newsgroup documents organized into 20 categories, making it suitable for text classification tasks.

### Dataset Overview:
- **Features**: Text data from different newsgroups.
- **Labels**: Categories of the documents (20 total categories).

## Requirements

Before running the code, you’ll need to install the required Python libraries. You can install them using the following command:

```bash
pip install -r requirements.txt

