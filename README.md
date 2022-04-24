# Anime-Recommendation-Systems
# About
This is a mini project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on recommending animes to viewers. Overview of source code:
1. Data Preparation and Cleaning
2. Exploratory Data Analysis
3. Machine Learning Models

# Contributors
@
@
@JingSiong - Content-based filtering (cosine similarity) and item-based collaborative filtering (KNN and SVD Algorithms)

# Problem Definition
How can we amidst the enormous library of animes, recommend quality animes according to viewers’ preference?
Can we accurately predict the score of an anime and classify it as a top show?

# Exploratory Data Analysis
Univariate Visualisation 
1. Catplots for categorical variables
2. Histograms for numerical variables

Through univariate visualtion, we managed to identify variables such as 'Type' which do not play a significant role in predicting the score and removed them. 

Predictors vs Score
1. Boxplot and Stripplot for categorical predictors
2. Correlation matrix for numerical predictors 

# Machine Learning Models

Predicting anime score using chosen variables 
1. Decision Tree
2. Random Forest Classification

Item-based Collaborative Filtering 
3. K Nearest Neighbours (KNN)
4. 4. Singular Value Decomposition (SVD)
5. Evaluation of these two models using 5-Fold cross validation and train-test split

# Insights and recommendation 
1. Random forest classification is a more accurate and better model than decision tree 
2. Singular Value Decomposition algorithm has a lower error and is more accurate than the K Nearest Neighbours algorithm 
3. Venture into user-based collaborative filtering 

# References
1. https://www.kaggle.com/datasets/hernan4444/anime-recommendation-database-2020?select=animelist.csv
2. https://github.com/codeheroku/Introduction-to-Machine-Learning/blob/master/Building%20a%20Movie%20Recommendation%20Engine/Movie_Recommendation_Engine.ipynb
3. https://www.datacamp.com/community/tutorials/recommender-systems-python
4. https://towardsdatascience.com/a-beginner-friendly-guide-to-recommender-system-3f5fa2a57c02
