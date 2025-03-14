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


## Model Training and Saving:

- In main.py you can specify which models to train and save. For example:

![image](https://github.com/user-attachments/assets/4654a1bb-311d-4b30-bbfb-8898c14877c5)


## Output Files:

- Trained models are saved in the models/ folder.


## Project Structure

The project consists of the following files and folders:

- **main.py:** Contains the main training and evaluation loop.

- **data.py:** Manages data loading and preprocessing operations.

- **vectorization.py:** Defines text vectorization methods (e.g. TF-IDF).

- **classification.py:** Defines classification models (e.g. Decision Tree, SVM).

- **nlp.py:** Contains operations related to natural language processing (NLP) (e.g. stopword extraction).

- **train.py:** Contains model training and evaluation functions.

- **data/news.json:** Used news text dataset.

- **models/:** Folder where trained models are saved.


## Results

When the project is run, a classification report (precision, recall, F1-score) and accuracy score (accuracy) are obtained for each model. The best performing models are saved in the models/ folder.

Sample Output:

![image](https://github.com/user-attachments/assets/e5a3a23b-f08e-48c8-b0cd-895d022d8817)





