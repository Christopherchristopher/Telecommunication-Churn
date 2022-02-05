# TELECOMMNUNICATYION-CHURN
Churning is a common and a major business problem facing business in major industrY. Wether in the Communication, Real Estate, Health, Aviation, or Hospitality etc. A churned customer provides less or zero revenue and also increase competitor market share. So therefore, there is a need to manage churning. Which is why customer retention strategies is at the fore to address this problem.
This project is aimed at understanding why customers churn through the major services provided by a company in a certain Telecommunication Industry.
It consists of the Exploratory Data Analysis and subsequently, machine learning modeling of churning customers.
I started out by importing our dataset into my Jupyter notebook, and printing out the first five and last five roles just to have an overview of the kind of data I will working with.

## Exploratory Data Analysis
1.Understand the variables in the dataset: Having an overview understanding of the data by printing the shape, the column values, and the data types of the dataset.
2.Cleaning the Data: Checking for incomplete dataset and dropping columns where neccessary
3.Analyse relationships between variables: Analyzing the univariate and bivariate relationship between variables and the target variable (Churn customers)
4Explore and visualize relationships: Visualizing relationship between variables by plotting diagrams against variables 

### Model Building
Model Building
Importing the relevant libraries and classifiers
1.	Model Selection : Our  problem is a classification problem and so therefore we have decided to go with any of the classification algorithms.: DecisionTreeClassifier
2.	Split : Understating our predictors(x) and targets(y) and splitting our dataset accordingly
3.	DecisionTreeClassifier: We fit and train our model using this algorithm
4.	Model check: We check the accuracy of our model, confusion_matrix and classification report and not satisfied with the accuracy because of how low our accuracy was, we then employed the oversampling technique.




