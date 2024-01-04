# Sentiment_enhanced_drug_recommendation_system

# Sentiment-Enhanced Drug Recommendation System

## 1. Problem Statement

Traditional drug recommendation systems often overlook the sentiment expressed in user feedback, leading to inaccurate recommendations. This study addresses this issue by proposing a sentiment-enhanced drug recommendation system. The system incorporates sentiment analysis techniques into the collaborative filtering algorithm to provide more accurate and relevant drug recommendations, considering both positive and negative user sentiments.

### 1.1 Objectives and Research Questions

#### Objectives:

- Gather appropriate data
- Conduct in-depth exploratory data analysis to understand the data.
- Identify and annotate sentiments in reviews using the VADER algorithm.
- Examine the relationship between drug rankings and sentiments in reviews.
- Develop a rank-based sentiment-enhanced drug recommendation system.
- Create a model-based sentiment-enhanced drug recommendation system using the Singular Value Decomposition (SVD) model.
- Perform an intensive evaluation and comparative analysis of the system's performance.

#### Research Question:

- How can sentiment analysis be integrated into the collaborative filtering algorithm to improve drug recommendations for user health conditions?

### 1.2 Methodology

The methodology involves data preprocessing, feature extraction, and implementing the collaborative filtering algorithm with sentiment analysis techniques. The publicly available Drug Review Dataset from the UCI Machine Learning Repository is used for experimentation.

#### Steps:

1. **Data Preprocessing:**
   - Remove noise and irrelevant information from the dataset.
  
2. **Feature Extraction:**
   - Extract user ratings, drug names, user health conditions, and user reviews from the dataset.

3. **Sentiment Analysis:**
   - Use lexicon-based and machine learning-based approaches to extract sentiments from user feedback.
   
4. **Collaborative Filtering with Sentiment Analysis:**
   - Detect sentiments in drug reviews and translate them into numerical values (0 or 1).
   - Incorporate sentiment scores into the collaborative filtering algorithm.

5. **Implementation and Evaluation:**
   - Implement the sentiment-enhanced collaborative filtering algorithm using Python.
   - Evaluate the system using standard metrics such as Root Mean Squared Error (RMSE), accuracy, precision, and recall.

For a visual representation of the implementation flow, refer to the figure in the repository.

### 1.3 Scope and Limitations

The project focuses on developing and evaluating a sentiment-enhanced drug recommendation system using a collaborative filtering algorithm. It uses a publicly available dataset for experimentation, which may impact generalizability. The study specifically explores lexicon-based and machine learning-based sentiment analysis techniques.

## 2. Data Collection

Data collection is a critical stage, and the Drug Review Dataset from the UCI Machine Learning Repository is used available on https://archive.ics.uci.edu/ml/datasets/Drug+Review+Dataset+%28Druglib.com%29. The dataset contains two files with 3107 and 1036 drug reviews for training and testing datasets, respectively, across nine columns.
