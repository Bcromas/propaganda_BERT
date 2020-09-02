# Predicting Propaganda using BERT

<img src="toa-heftiba-QHuauUyXRt8-unsplash.jpg" width="150" height="200" />

<a href="https://medium.com/@bromas/predicting-propaganda-using-bert-bbb28b7deb71?source=friends_link&sk=92b472b78571058f86ab5e4fb679b35a">Medium article for the project</a>


Guide to files:
* **EDA.ipynb**
  * Exploratory data analysis on training data. 
  * Leverage spaCy, intervaltree, textstat, and Matplotlib for visualizations.
  * Features an approach for increasing training data by 160%!
* **generate_data.ipynb**
  * Create training and dev .tsv files for classifiers.
  * Generate negative spans from news articles, increasing data by +160%.
* **dummy_classifier.ipynb**
  * Establish a baseline model for evaluating more sophisticated models.
  * Perform multi-class classification using training and dev data.
  * Evaluate performance using confusion matrix, classification report, and micro F1. 
* **logistic_regression.ipynb**
  * Create a logistic regression model.
  * Perform grid search to adjust the model's hyperparameters.
  * Perform multi-class classification using training and dev data.
  * Evaluate performance using confusion matrix, classification report, and micro F1.
* **bert_training_validation.ipynb**
  * Fine-tune a pre-trained BERT model on the training data.
  * Perform hyperparameter tuning by evaluating different variations based on: model, epochs, learning rate, and batch size.
  * Evaluate average performance on validation sets using accuracy, precision, recall, and F1.
  * Save the best performing version for evalution on the test set.
* **bert_testing.ipynb**
  * Run best performing version on test data.
  * Evaluate performance using accuracy, precision, recall, and F1.

Photo by [Toa Heftiba on Unsplash](https://unsplash.com/photos/QHuauUyXRt8)
