
This project classifies news articles using a machine learning pipeline built with Python scripts.

AG News Dataset (Kaggle)

Multinomial Naive Bayes

Folder Structure:
- data/raw → original dataset
- data/processed → cleaned data
- src → scripts
- models → saved ML model
- results → evaluation output

Steps to Run:
1. Install dependencies
pip install -r requirements.txt

2. Place the dataset in data/raw
https://www.kaggle.com/datasets/amananandrai/ag-news-classification-dataset

3. Run:
python main.py

Final Result:
~88-90% accuracy depending on preprocessing
