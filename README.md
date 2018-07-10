# DonorsChoose
kaggle competition, help DonorsChoose.org to screen funding proposals from teachers

## Introduction
DonorsChoose is a platform where teachers request funds for their students for educational purposes. There are huge amount of proposals from teachers to be reviewed by volunteers and it's still increasing. We(with Fei Li) cleaned the data, did feature engineering(including NLP techniques to extract features from texts) and built a high-performance (AUC 0.81) predictor/classifier with Ensemble method (Gradient Boost, GRU, Random Forest, etc.). It can help to automatically choose which proposals to approve. Based on the predictor, volunteers need only to focus on the marginal cases and this greatly reduce unnecessary labor.

## Requirements
Jupyter notebook,

packages:Numpy, Pandas, Scikit-learn, Matplotlib, Seaborn, XGBoost, NLTK, TextBlob, tqdm, Keras

## Claim
Notice that codes are not complete. They need to be organized, too. The AUC=0.81 results are based on multiple learners stacking together.
However, one can still run each file and get predictions. 
## Data preview and EDA
TBD
## Data cleaning and feature engineering
Text data was manipulated with Natural Language Processing techniques.
## Supervised Learning and Embedding/Stacking
Logistic Regression, XGBoost, Capsule Net, GRU, ...
## Results
TBD
## References
TBD
