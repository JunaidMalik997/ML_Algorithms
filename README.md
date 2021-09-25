# Machine_Learning_Algorithms
Linear Regression, Logistic Regression, KNN, Decision Tree and Random Forest, SVM, K Means Clustering, PCA

# 1. Linear Regression:

Performed two tasks using Linear Regression:

a. USA House Price Prediction using USA_Housing.csv dataset. In which various features such as Avg area and avg. number of rooms etc were set as Input features while House Price was set as Output feature which is to be predicted by the Linear Regression Model.

b. Predicting the Yearly Amount Spent by the customer on Web and Mobile App using Ecommerce Customers dataset. Various features such as Avg.time, length of membership, Avg session length etc were used as Input features whereas Linear Regression Model predicts the Yearly Amount Spent by the customer.

# 2. Logistic Regression:

a. Using titanic_train.csv dataset tried to predict whether the passenger survived or not using Logistic Regression. Some of the columns were missing values, so we cleaned the data first either by deleting the row alltogether or by extrapolating the values of the non-null entries to null entries if the column was not missing a lot of the values. We then train by logistic regression which is a binary classifier and predicts either Survived or not survived, based on other input features from titanic_train.csv dataset. Then we teat our trained model on titanic_test.csv dataset.

b. Using advertising.csv dataset we try to predict whether a user based on different input parameters such as age, daily time spent on site, daily internet usage etc clicked on ad or not. We use Logistic Regression and provide input parameters and try to predict output label which is clicked on ad. We also cleaned the data, and converted some continuous data to categorical data in order to extract maximum information from the data.

# 3. K Nearest Neighbor (KNN):

a. Used the anonymous data called Classified Data having many points belonging to various features. We first scale the data using the Standard Scaler, and then apply KNN algorithm to predict the target class. We try to choose the best K value for which we get the lowest error rate.

b. Used the KNN_Project_Data dataset having many anonymous features and a target class. After some data pre-processing, used KNN algortihm to predict the target class based on data points choosing the K value having the least error rate.

# 4. Decision Tree and Random Forest:

a. Used the kyphosis.csv dataset to predict the value of Kyphosis either Present or Absent using feature names called Age, Number and Start. Used both Decision Tree and Random Forest Classifier to predict the value of kyphosis.

b. Used the loan_data.csv dataset to predict whether a certain individual paid off his loan completely or not using various features as present in the loan_data.csv. Performed some exploratory data analysis and data cleaning and then applied Decision Tree and Random Forest classifier on the data.

# 5. Support Vector Machine (SVM):

a. We used sklearn builtin dataset called load_breast_cancer. We try to predict the presence or absence of breast cancer using various medical features such as mean radius, mean concavity, worst fractal dimension etc. We then used Support Vector Machine ALgorithm to develop a model to predict on test dataset.

b. We used builtin seaborn iris dataset which has 3 classes and we try to predict them using various,input features such as sepal_length, sepal_width, petal_length, petal_width. We then use SVM algorithm to come up with a hyper-plane to distinguish the 3 classes.

# 6. K-Means Clustering:

a. Used scikit learn to get some artificial data points having 4 centroids. We then applied K means clustering to find those 4 clusters.

b. We used College_Data to predict whether the college is private or not using features such as Grad Rate, Room Board, Outstate etc. After that, K means clustering was applied to find the clusters that preicts whether the college is private or not.

# 7. Principal Component Analysis (PCA):

Used Scikit Learn builtin load_breast_cancer dataset. After some data pre-processing, we reduce the dimensionality of the dataset to 2 principal components.
