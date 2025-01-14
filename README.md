# BT4222_Group3_Toxic_Comment_Classification

## Motivation
The widespread usage of social networks has resulted in a vast amount of information being produced through online communication among users. 510,000 comments are posted on Facebook every minute and around 6,000 tweets are posted on Twitter each second. While active online interaction contributes greatly to improving the quality of human life, it also poses a serious threat due to the potential of toxicity. People may tend to use offensive language termed as toxic comments to express their intense emotions. These toxic comments may be threatening, obscene, insulting or identity-based hatred, which can lead to personal attacks, online harassment, and bullying, making it an unfortunate aspect of online communication. 

To address the above issues, our group will therefore aim to develop a multi-label classifier to identify toxic comments and categorise different types of toxicity into the following categories: toxic, severe-toxic, threat, obscene, insult, and identity-hate.



## Getting Started
This project mainly uses Jupyter Notebook. Upon cloning this repository into your local machine, run the following command to install all relevant packages.
```bash
pip install -r requirements.txt
```

## Files
The following table contains a brief description of the files and folders in this repository.
| Folder / File | Description |
| - | - |
| **1_Cleaning.ipynb** | Data Cleaning, such as expanding contractions, removing URLs |
| **2_Preprocessing.ipynb** | Data proprocessing, such as tokenization, POS tagging and lemmatization|
| **3_EDA.ipynb** | Exploratory Data Analysis|
| **4_Feature Engineering.ipynb** | Creating new features and evaluation to select appropriate features |
| **helper_functions.py** | Helper functions including data cleaning, preprocessing and evaluation score for models |
| **5_Embedding.ipynb** | Word Embedding and Sentence Embedding method |
| **6_Processing Test.ipynb** | Feature Engineering on test data|
| **7_Oversampling.ipynb** | Oversampling on minority classes|
| **Logistic Regression & Random Forest.ipynb** | Logistics Regression & Random Forest Model|
| **LogReg & RandomForest Models Evaluation.ipynb**| Logistics Regression & Random Forest Model Evaluation|
| **LightGBM & Naive Bayes.ipynb** | LightGBM & Naive Bayes Model|
| **LightGBM & Naive Bayes Evaluation.ipynb**| LightGBM & Naive Bayes Model Evaluation|
| **Boosting Models.ipynb** | AdaBoost & XGBoost Model|
| **Boosting Models Evaluation.ipynb**| AdaBoost & XGBoost Model Evaluation|
| **LSTM.ipynb**| Long Short-term Memory Model and Evaluation|
| **Ensemble.ipynb**| Ensemble on models|
| **8_Model Evaluation.ipynb** | Metrics and evaluation of models |
| **tuner**| Dump and output of all models|
| **performance**| Metrics of performance of each model|
| **Data**| Train and test dataset|
| **comparision**| Comparison between best model and Prospective API|
| **prediction**| Predictions using best model and Prospective API|

