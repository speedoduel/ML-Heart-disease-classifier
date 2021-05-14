# ML-Heart-disease-classifier
A ML project where we use different classifier in python to find the most accurate in python to predict wheather the patient will have stroke or not
We extensively used all Jupyter notebooks for this project and we took classifier like Decision Tree, Logistic Regression and Random Forest and K nearest neighbors Classifier
to see the most accurate one for the dataset in this project and then predicted if the next patient might be at risk with an accuracy of 85.2%
In this project I did the following tasks

![](images/pog.gif)


- imported the data repository from kaggle
- imported the specific libraries
- Analysed the dataset calculated it's mean,min, max, count, Q1,Q2,Q3,Q4 and std using "describe()"
- checked for if any variables required cleaning by finding their datat types using "dabl" 
- Performed feature selection where i made a heatmap of the dataset to see the relation between target and other variables using "seaborn"
- Made infrences from the heatmap
- Made a histogram and chekced if the data was balanced or not using "Seaborn"
- Found target distribution, found the Discriminating PCA direction and the relation of all categorical variable to the target variable using "dabl"
- Created dummy variables for the models and performed standard scaling using "sklearn and "StandardScaler"
- Seperated the data into training and testing using "train_test_split()" from "sklearn"
- Made a working Knn classifier on the data set and used cross validation for improved accuracy using "sklearn" and "KNeighborsClassifier()"
- Made a random forest classifier and compared it's accuracy with the knn classifier using "sklearn" and "RandomForestClassifier()"
- Made a desicion tree classifier and a performed logitic regression then checked the accuracy of each and present the results of the model with the highest accuracy which was logistic regression using "dabl"



![](images/loco.gif)
