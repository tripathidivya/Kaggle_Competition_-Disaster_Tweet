# Kaggle_Competition_-Disaster_Tweet
Linked Project from Kaggle
Kaggle Competition - Disaster Tweet

**Overview**:\n
This repository contains code and resources for the Kaggle competition "Disaster Tweet." The competition's goal is to develop a machine learning model to classify tweets as either related to a disaster or not.

**Data**:
The dataset consists of labeled tweets, with a binary target variable indicating whether a tweet is disaster-related or not. You can find the dataset on Kaggle here.

**Files**:
train.csv: Training data with labels.
test.csv: Test data for making predictions.

**Logic**:
1.Take data
2. Apply Tokenization
3. Clean the data: Hyphens, Numbers, Punctuation, removing unnecessary white space, Contractions words
4. Convert string to lowercase
5. Apply Lemmatization
6. Plot WordCloud
7. Apply Vectorization
8. Baseline Model: MultinomialNB() / svm.SVC()
9. Add vectorization.transform function to pipeline and model.predict to pipeline

**Usage**:
Clone this repository to your local machine.
Install the required dependencies mentioned in requirements.txt.
Use the provided code and notebooks to build and evaluate your model.
Make predictions on the test set and submit your results to Kaggle.

**Important Links**:
Kaggle Competition Link: Disaster Tweet
Discussion Forum: Kaggle Discussion

**Contact**:
For any questions or issues, please contact me(Divya Tripathi) at tripathi.divya@outlook.com

Happy coding! 🚀
