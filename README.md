# Natural Language Processing to classify the Yelp Reviews from 1 through 5 stars
## Project Description
The NLP project will be attempting to classify Yelp Reviews into 1 star or 5 star categories based off the text content in the reviews.

## Dataset
1. The data is taken from https://www.kaggle.com/c/yelp-recsys-2013
2. Each observation in this dataset is a review of a particular business by a particular user.

## Technologies used
1. Python (NumPy, Pandas)
2. Data Visualization (Matplotlib, Seaborn)
3. Feature Engineering
4. Machine Learning (NLP MultinomialNB)

## Project Tasks
### 1. Import and load the data
Imported and loaded the data from yelp csv file into **DataFrame**. Examined the overall statistical information of the dataset using some statistical methods like <code>describe(), info()</code>. 
### 2. Exploratory Data Analysis
Analyzed different features by plotting different kinds of graphs using **Seaborn FaceGrid**, **Boxplot**, **countplot**. Examined the important features from the correlation coefficient provided by **Heatmap**.
### 3. Feature Extraction (Vectorization)
Scikit-learn’s **CountVectorizer** is used to convert the reviews text to a vector of term/token counts. This is used as a input for the Machine Learning model.
### 4. Train a Machine Learning model
Built a Machine Learning model uisng **Multinomial Naive Bayes Classifer** to classify the discrete features i.e. word counts for text classification.
### 5. Predictions and Evaluations
Predicted and evaluated the model using metrics like **confusion matrix** and **classification report** with an accuracy of **91%**.
