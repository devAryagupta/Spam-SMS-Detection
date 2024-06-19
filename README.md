# Spam-SMS-Detection


## Introduction
This project aims to build an AI model for spam SMS detection. The dataset contains a set of SMS labeled messages in English, tagged as spam or legitimate (ham).

## Dataset
The dataset is available on [Kaggle][(https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)] and contains the following columns:
- The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam.
- The files contain one message per line. Each line is composed by two columns: v1 contains the label (ham or spam) and v2 contains the raw text.
- A collection of 425 SMS spam messages was manually extracted from the Grumbletext Web site. This is a UK forum in which cell phone users make public claims about SMS spam messages, most of them without reporting the very spam message received. The identification of the text of spam messages in the claims is a very hard and time-consuming task, and it involved carefully scanning hundreds of web pages. 

## Data Preprocessing
- Load the data.
- Clean the text (remove punctuation, convert to lowercase, etc.).
- Tokenize the text.
- Remove stopwords.

##  Feature Extraction
-  use TF-IDF (Term Frequency-Inverse Document Frequency) to convert the text data into numerical features that can be used by machine learning algorithms.

## Model Selection and Training
-  use three classifiers:

- Naive Bayes
- Logistic Regression
- Support Vector Machines (SVM)

## Model Tuning and Optimization
- Performed hyperparameter tuning using Grid Search for Random Forest.
- Selected the best model based on performance metrics.

## Evaluation
- We will evaluate our models using accuracy, precision, recall, and F1-score.

## Conclusion
- Summarized findings and final model performance.
- The best model was selected based on ROC-AUC and other performance metrics.
- Suggested future work and potential improvements.

## How to Run the Code
1. Clone the repository.
2. Install the required packages using `pip install -r requirements.txt`.
3. Run the Jupyter Notebook to reproduce the results.

## Bug / Feature Request :man_technologist:
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here][([(https://github.com/devAryagupta/Spam-SMS-Detection/issues/new)] by including your search query and the expected result.
If you'd like to request a new function, feel free to do so by opening an issue [here].[(https://github.com/devAryagupta/Spam-SMS-Detection/issues/new)] Please include sample queries and their corresponding results.

## Connect with me! 🌐
Known on internet as **Arya Gupta**

[<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/linkedin.png" title="LinkedIn">](https://www.linkedin.com/in/arya-gupta-5968ab289/)

[<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/telegram-app.png" title="Telegram"/>](https://t.me/Brooklyn7e)
## Email Me :e-mail:

[<img target="_blank" src="https://img.icons8.com/?size=100&id=pLfVjzYzDfaw&format=png&color=000000" title="Mail me">](mailto:ag551410@gmail.com)
