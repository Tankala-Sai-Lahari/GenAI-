# GenAI-
course in GenAI introduction
*SageMaker-basic chatbot*
--------------------------
    creating the chatbot functionatity using python dictionaries and the will       respond according to the keywords.
*Building Enery Efficiency (Supervised learning)*
--------------------------------------------------
    in this we created an supervised alorithm for the scenario.
    we use libraries like :
    ---importing libraries----
    pandas ,numpy , matplotlib.pylot, seaborn,sklearn where,
    PANDAS: 
         pandas is a data manipulation package in Python for tabular data.DataFrames. 
    NUMPY   :
        NumPy is a module for Python that allows you to work with  multidimensional arrays and matrices.
    matplotlib.pyplot :
        a collection of command style functions that make matplotlib work like MATLAB. Each pyplot function makes some change to a figure
    SEABORN:
    Seaborn is a library for making statistical graphics in Python. It builds on top of matplotlib and integrates closely with pandas data structures
    SKLEARN:
        Scikit-learn is a library in Python that provides many unsupervised and supervised learning algorithms. It's built upon some of the technology you might already be familiar with, like NumPy, pandas, and Matplotlib
*Building a Decision Tree*
------------------------------
    Scenario:
    Imagine you are a data analyst at a telecom company. The marketing department has noticed an increase in customer churn and needs your help to identify which customers are most likely to leave next month.

    Dataset Description
    We will use a synthetic dataset for this exercise. The dataset contains the following columns:

    CustomerID: A unique identifier for each customer.
    Age: The age of the customer.
    MonthlyCharge: The monthly bill amount for the customer.
    CustomerServiceCalls: The number of times the customer contacted customer service.
    Churn: This is our target variable, indicating whether the customer churned (Yes) or not (No).
    STEP BY STEP PROCEESS:
    Setup the Environment:
    Import necessary libraries: Pandas for data manipulation, Scikit-learn for machine learning, and Matplotlib for visualization.
    Create the Dataset:
    Use Python to create a synthetic dataset. We'll make a small dataset for simplicity.
    Data Preparation:
    Split the data into features (X) and the target variable (y).
    Further split the dataset into training and testing sets.
    Build the Decision Tree Model:
    Use Scikit-learn to create a DecisionTreeClassifier.
    Train the model on the training data.
    Evaluate the Model:
    Make predictions on the test set.
    Calculate the accuracy of the model.
    Visualize the Decision Tree:
    Use Matplotlib to visualize how the decision tree makes decisions.
    Discuss the Results:
    Interpret the decision tree.
    Discuss how it can be used by the company to reduce customer churn.
    *KEY CONCEPTS*:
    Splitting the Dataset - The dataset is divided into training and testing sets. Typically, 70% of the data is used for training the model, and the remaining 30% is reserved for testing.

    Training Data vs. Testing Data - Training data is used to train the machine learning model. In contrast, testing data, which the model has not seen during training, is used to evaluate the model's performance and generalization ability.

    Model Training Process - The process involves using a 'fit' method where the model is trained using features (X_train) and targets (Y_train). The testing data is not used in this stage.

    Prediction and Accuracy Assessment - After training, the model makes predictions on the test data (X_test). These predictions are then compared with the actual outcomes (Y_test) to calculate the model's accuracy.
![image](https://github.com/Tankala-Sai-Lahari/GenAI-/assets/99111736/02da8d67-dd04-4933-ba7d-799063711627)


