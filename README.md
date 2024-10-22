# GSTN-Analytics-Hackathon
The project entailed building a predictive model to predict GST revenue.Making use of the historical data, this project was focused on predicting GST revenue so that governments can properly manage their financial resources, have adequate budgets, and hence make the best use of the available resources. By applying machine learning algorithms,it was able to make precise estimates, which thereby would improve collection and strengthen the country's economic strategy.

The dataset will be divided into the train and test sets.The training set will form the model and the test set is used to assess the generalization of the developed model.Since there are no categorical variables involved in the dataset, only numerical preprocessing techniques have been applied. Mean imputation for missing values and feature scaling. Feature scaling is pretty crucial because it prevents model biasing in situations such as Logistic Regression and Support Vector Machines (SVM) models, especially if they are sensitive to the magnitudes of their features.

The three algorithms used for the construction of this model are Logistic Regression, Random Forest, and XGBoost. Each brings a different strength to the table in terms of modelling.Interpretabilty has the biggest strength of Logistic Regression; XGBoost handles complicated interactions involving features very well; and, finally, Random Forest provides robustness based on averaging decision trees. To optimize performance and predictive performance for the ensemble based on the strengths of each of its constituent models, a StackingClassifier is used to combine all three of these models.
Accuracy, precision, recall, and F1-score are the performance metrics used to assess the model. The model reaches an accuracy of 97.74% and an AUC score of 0.99. Hence, it classifies well. Also, the confusion matrix gives a very low misclassification rate as well as very few false positives and false negatives. Hence, it is highly reliable for the prediction
