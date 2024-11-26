# **Sentiment Analysis on Movie Reviews**

* Name: Shubham Parshuram Sawant
* Username/ User-Id: ssawant4 / 2119480
* Professor: David Hubbard.
____________________________________________
### **Overview**
- This project was centered on the categorization of movie reviews as either positive or negative through sentiment analysis and using learning algorithms. There were an array of thousands of reviews with their corresponding sentiment labels which formed our dataset, for text analysis and representation we used BoW, TF-IDF and N-Gram. Implementation of Logistic Regression, K-Nearest Neighbors (KNN), Naive Bayes, Voting Classifier and Random forest were done.
- Some of the main conclusions depicted here were that the environment model was effective in taking advantage of the promising aspects of individual classifiers since it produced better and consistent results as a single classifier. Preprocessing data and feature selection introduced significant characteristics of the dataset to improve model choice and assessment. Suggested future work options involve using the deep learning models, the feature engineering, and hyperparameters fine-tuning in order to improve the outcomes achieved. This project forms a good example where an integration of conventional machine learning solutions for sentiment classification is quite appropriate.

### **Problem Trying to Solve**
- In the primary task of this project, which is sentiment analysis, the goal was to categorize the movie reviews as positive or negative. The objective here was to examine the impact of various methodologies on the audience response and supervise the performance of the different classifiers that have been proposed. To solve this problem, we sought to gain information on the audience’s stance and sentiment classification algorithms when analyzing textual data.

### **How To Set Up Data for Analysis**
- The dataset contained movie reviews and the sentiment associated with it was positive or negative. Reviews were derived from two large CSV files with thousands of reviews each. This was done to clean the data where missing values and any closers of duplicate entries were deleted. In the study, words in the reviews were tokenised, while the text features were quantified using methods such as Bag of Words, TF-IDF and N-Gram. Other strategies used included Part of Speech tagging and word embedding (with TF-IDF used as a proxy).

### **Pre-Exploratory Data Analysis**
- Initial analysis involves Exploratory Data Analysis (EDA) in order to gain preliminary ideas about their nature. Key insights included: 
1. A reasonable number of positive and negative product testimonials.
2. For example, some reviews are long while others short, so the lengths of the reviews signify audience diversity.
3. Positive and negative subjectivity using VADER reflected a good strength of association between the compound scores obtained and the actual sentiment scores given.
4. These insights helped to determine which features to derive and which model to choose.

### **The Models Used and the Results**
- Five machine learning models were implemented: 
1.	Logistic Regression: Executed as a baseline with high accuracy on training and testing Machine learning datasets. 
2.	K-Nearest Neighbors (KNN): By tuning the hyperparameter; the performance was moderate but came at the cost of computational complexity. 
3.	Naive Bayes: Preface : using the TF-IDF AND N-Gram performance at its best to understand that this kind of technique is more appropriate for text classification. 
4.	Random Forest: High performance, yet they show signs of overfitting to some extent that are evident with the training data set. 
5.	Ensemble Voting Classifier: Integrated the approaches of separate models and got the final result as the greatest general accuracy. 
- Hence, the ensemble model reduced the false positive and false negatives cases, giving a good classification model.

### **Ideas for Improvement**
- While the results were satisfactory, further improvements could be made:
1. Incorporate Deep Learning Models: As a normal practice, people nowadays are using the models like LSTMs or BERT for a better and deeper understanding of the context.
2. Advanced Feature Engineering: Assessing the outcome of a new topic modeling or lexical diversity metric conducted by the Computer Science team.
3. Additional Data Sources: Excluding a part of reviews so that the others help in generalization of the models.
4. Hyperparameter Optimization: Making use of post-processing approaches such as Bayesian Hyperparameter Optimization for week 4 fine-tuning.
- These improvements could potentially extend the model’s effectiveness to other practical problems as well.
