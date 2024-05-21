# census-income-data-science
I worked on census income dataset that’s evaluate the income of populations in United-States, Cambodia, England and some of other countries with features capital-gain , capital-loss , hours-per-week , work class , age and education these Extraction was done by Barry Becker from the 1994 Census database.
Its associated task was a classification, and I applied a three Machine learning 
Algorithms after preprocessing the data are:
1- Naive Bayes (GaussianNB)
2- Decision Tree Classifier
3- K-Nearest Neighbors (KNN)

Preprocessing section :
Handle missing values.
Remove duplicates.
 Encode categorical variables.
Normalize numerical features.

 Algorithms applying :
DecisionTreeClassifier with {'criterion': 'gini', 'max_depth': 5} with Train accuracy : 83% and      Test accuracy : 83%
KNeighborsClassifier with accuracy 80.6%
GaussianNB with accuracy 79.5%

The tasks done was an :
1- Split the dataset into training and testing sets.
2- Train the machine learning models using the training set.
3- Evaluate the models using appropriate metrics (accuracy)
4- Compare the performance of different algorithms and select
the best-performing model for each task.
