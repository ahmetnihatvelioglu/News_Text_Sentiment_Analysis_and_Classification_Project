# Overwiev
This project is a machine learning project that aims to perform sentiment analysis using news texts and classify texts into specific categories. The project includes cleaning text data, vectorization, training classification models, and evaluation stages.


## Key Features:

- **Data Preprocessing:** Cleaning text data, converting to lowercase, cleaning special characters and removing stop words.

- **Vectorization:** Converting text data to vectors using TF-IDF (Term Frequency-Inverse Document Frequency) method.

- **Classification Models:**

1- Decision Tree

2- K-Nearest Neighbors (KNN)

3- Stochastic Gradient Descent (SGD)

4- Naive Bayes

5- Support Vector Machines (SVM)

6- Random Forest

7- Logistic Regression

8- Gradient Boosting

- **Model Optimization:** Hyperparameter optimization with Grid Search.

- **Model Evaluation:** Evaluation of model performance with classification report, accuracy score and cross-validation.

- **Model Saving and Loading:** Saving trained models and loading them for reuse.


## Setup

To run the project, follow these steps:

- Install Required Libraries:

"pip install scikit-learn pandas nltk joblib"

Download NLTK Stopwords:

- The project uses Turkish stop words. You need to download these words using the NLTK library. Download the stopwords by running the following code:

"import nltk
nltk.download('stopwords')"

## Dataset

The project uses a JSON file called **data/news.json**, which contains news text and related sentiment labels.

## Usage

Run **main.py** File:

- Use the following command to run main.py file:

"python main.py"

Setting Parameters:

- In the main.py file, you can set the classifiers used, vectorization parameters, and Grid Search parameters


![image](https://github.com/user-attachments/assets/67e8ff12-97f8-4637-91b5-6ed6977ae566)





