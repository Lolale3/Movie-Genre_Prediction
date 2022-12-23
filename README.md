# Movie-Genre_Prediction
This data science project inspires the idea of how a movie genre can be predicted based on its story or review to further apply it in practice for 
recommendation system used in Netflix, Amazon prime, etc or search engine recommendations such as Google, Yahoo, etc. 

Tools Used: Python, Jupyter Notebook
Libraries Used: NLTK, SkLearn, Pandas, Matplotlib
Models: Logistic Regression, Multinomial Naive Bayes, Stochastic Gradient Descent, Extreme Gradient Boosting,  K-Nearest Neighbors, Random Forest and Support Vector Machine.

The focus of this project is on classifying whether the movie is Drama or Non-Drama based on its story using the Text-Analysis model along with machine learning 
algorithms. The data used for training consists of 20,000 samples and 3498 samples for evaluation of the model which is stored in an excel file. The data is accessed 
using the Pandas library. The data is formatted appropriately for training using various text-analysis models like 
Bag-of-words
TFIDF
LDA 
Word Embedding

Various machine learning models are trained to understand their performance on training data for each text-analyzed data and compared to pick the best model for 
evaluation data. Since the class labels are imbalanced, the Roc-Auc score and F1 score are analyzed for comparison.
