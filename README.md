# customer-reviews-analysis

## Project Overview
This project analyzes customer reviews using Natural Language Processing (NLP), time series analysis, and neural networks to identify patterns in customer feedback, review activity, and product ratings.

## Objectives
- Identify frequently mentioned words and phrases in customer reviews.
- Analyze changes in review volume and average ratings over time.
- Build a neural network to predict customer ratings from review text.
- Evaluate model performance using accuracy, a classification report, and a confusion matrix.

## Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib
- NLTK
- Scikit-learn
- TensorFlow and Keras

## Project Workflow
1. **NLP:** Clean and preprocess review text, then analyze word frequencies and common phrases.
2. **Time Series Analysis:** Examine review volume and average ratings over time.
3. **Neural Networks:** Convert review text into TF-IDF features, train a neural network, and evaluate its predictions.

## Model Results
The neural network achieved **58.50% test accuracy** on 200 test reviews. The classification report showed that the model predicted five-star reviews more successfully than lower ratings, highlighting the effect of class imbalance.

## Dataset
The analysis uses `amazon_reviews_lab.csv`.

## How to Run
1. Download or clone this repository.
2. Install the required Python libraries.
3. Place the dataset in the appropriate working directory.
4. Open and run the Jupyter Notebook cell by cell.

## Limitations
The dataset contains more five-star reviews than lower-rated reviews. Consequently, the model struggles to classify some rating categories. Accuracy should therefore be interpreted alongside the classification report and confusion matrix.

## Author
Shalom Cheptoo
