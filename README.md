# PRODIGY_DS_04

# Task 04: Sentiment Analysis and Visualization on Social Media Data

## 📌 Objective

Analyze and visualize sentiment patterns in social media data to understand public opinion and attitudes towards specific topics or brands.

## 📁 Dataset

We used a dataset from Kaggle titled [Twitter Entity Sentiment Analysis](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis), which contains tweets annotated with sentiment labels (`Positive`, `Negative`, `Neutral`) and relevant entity tags.

## 🧰 Technologies Used

- Python
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, nltk, wordcloud

## 🔍 Project Workflow

1. **Data Preprocessing**:
   - Removal of special characters, URLs, mentions, and hashtags.
   - Tokenization and stopword removal.
   - Lemmatization using NLTK.

2. **Exploratory Data Analysis (EDA)**:
   - Sentiment distribution (bar plots, pie charts).
   - Word clouds for each sentiment category.
   - Entity frequency analysis.

3. **Sentiment Classification**:
   - TF-IDF Vectorization
   - Logistic Regression and Support Vector Machine (SVM)
   - Accuracy, confusion matrix, and classification report for model evaluation

4. **Visualization**:
   - Word clouds for top words in positive, negative, and neutral tweets.
   - Sentiment trends using bar and pie charts.

## 📈 Results

- Achieved high accuracy (~85–90%) with SVM classifier.
- Visuals clearly indicate which entities are most talked about positively or negatively.

## 📌 Key Insights

- Most tweets in the dataset are neutral, followed by positive sentiment.
- Certain entities receive more polarized opinions.
- Text preprocessing significantly improves model performance.

