# Avocado-ripeness-project
Final project for avocado ripeness classification

Author: Danny Goodlow  
Date: June 20, 2025

This project is for my final. I used a dataset from Kaggle to predict how ripe an avocado is using features like firmness, color, and weight. The idea is to help cut down on wasted produce by knowing how ripe something is before it goes bad.

- Source: [Kaggle - Avocado Ripeness Classification](https://www.kaggle.com/datasets/amldvvs/avocado-ripeness-classification-dataset)
- Used the CSV version of the dataset (no images)
- Features include firmness, hue, saturation, brightness, color label, sound in decibels, and weight
- Target column is ripeness (5 levels)

- Cleaned and encoded the data using `LabelEncoder`
- Trained a `RandomForestClassifier`
- Split 80% for training, 20% for testing
- Evaluated with accuracy and a confusion matrix

- Got 100% accuracy on the test data (no misclassifications)
- Honestly, the dataset is probably really well-structured so it made it easy for the model

This was a fun project. It shows how physical traits like firmness and color can be used to make useful predictions. If I had more time, I’d test this on images or messy real-world data. But this version proves the concept.

- `avocado_ripeness.ipynb` – the notebook with all the code
- `avocado_ripeness_dataset.csv` – the dataset used for training/testing

1. Open the notebook in Jupyter or Colab
2. Make sure the CSV is in the same folder
3. Run the cells

I added `profmemo` as a collaborator for grading.
