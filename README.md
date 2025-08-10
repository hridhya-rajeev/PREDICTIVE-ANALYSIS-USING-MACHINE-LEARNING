# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING
# COMPANY: CODTECH IT SOLUTIONS
# NAME: HRIDHYA ABHINA RAJEEVAN
# INTERN ID: CT04DH2665
# DOMAIN: DATA ANALYTICS
# DURATION: 1 MONTH
# description: 
In this task, the objective was to build a machine learning model capable of predicting outcomes based on a given dataset. I chose to implement a classification model using the well-known Iris dataset, which contains measurements of different types of iris flowers and their corresponding species. The Iris dataset is often used for classification problems because it is clean, balanced, and contains multiple classes, making it ideal for understanding predictive modeling concepts.

The first step was to import the required Python libraries, including scikit-learn, which is a popular machine learning library that provides tools for model building, evaluation, and deployment. I also imported functions for data splitting, model creation, and performance evaluation.

Next, I loaded the Iris dataset using the load_iris() function from scikit-learn. The dataset contains four features — sepal length, sepal width, petal length, and petal width — and a target variable that represents the species of the iris flower. The dataset has three classes: Setosa, Versicolor, and Virginica. Each flower in the dataset is labeled with one of these species.

Once the dataset was loaded, I performed a train-test split to divide the data into training and testing subsets. I used 80% of the data for training the model and 20% for testing it. This step is crucial because it allows us to evaluate how well the model generalizes to new, unseen data.

For the model itself, I selected Logistic Regression, which is a widely used algorithm for classification problems. Although logistic regression was originally designed for binary classification, it can be extended to handle multiple classes using techniques like "one-vs-rest." This makes it well-suited for the three-class problem in the Iris dataset.

After creating the logistic regression model, I trained it using the training dataset. This involved finding the best parameters (weights) that minimize the classification error. Once training was complete, I used the model to predict the classes of the flowers in the testing dataset.

To evaluate the model's performance, I calculated the accuracy score, which measures the percentage of correct predictions out of all predictions made. The model achieved high accuracy, indicating that it was able to correctly classify most of the test samples. I also generated a classification report, which includes precision, recall, and F1-score for each class. Precision measures how many of the predicted samples were actually correct, recall measures how many of the actual samples were correctly predicted, and the F1-score combines these two into a single metric. A confusion matrix was also generated to show the number of correct and incorrect predictions for each class.

The results demonstrated that the logistic regression model performed very well on this dataset, with minimal misclassification. This success can be attributed to the simplicity and separability of the Iris dataset, as well as the robustness of logistic regression for linear decision boundaries.

In conclusion, this task successfully demonstrated feature selection, model training, and evaluation in a machine learning classification problem. By following a clear workflow — loading the dataset, splitting the data, choosing a model, training it, and evaluating its performance — we were able to build a predictive model that achieves high accuracy. The skills developed in this task are applicable to real-world datasets, where similar steps can be followed to create reliable machine learning solutions for predictive analysis.



# output

![Image](https://github.com/user-attachments/assets/6ad54118-765d-488f-b9cc-846028b45a5c)
