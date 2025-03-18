# Breast-Cancer-Classification-using-Newton-s-Method-in-Logistic-Regression.
The aim of this project is to implement a logistic regression classifier and apply it to the Wisconsin dataset for breast cancer. Newton’s Method Accuracy has been Achieved by Logistic Regression.
The aim of this project is to implement a logistic regression classifier and apply it to the Wisconsin dataset for breast cancer. We have used the data set which is provided in the Assignment. About 80% of the dataset required to be divided into training instances, with the remaining portion being tested against the testing instance. Using the provided data set, the given file was downloaded and imported. Libraries like NumPy, Pandas, and sci-kit-learn modules to create models, manipulate data, and assess performance are used. Newton’s optimization technique is used to formulate a “Newton classifier” class that implements logistic regression.  The attributes implemented in this class are n_iteration, which is used for mentioning the number of iterations used in this class and split_ratio which is used for the testing and training the data sets, accs_nr is the attribute which we have used for the storing the accuracy of data sets, nr_model used for the making the predictions and two more attributes which we have utilized are acc_sk, sk_model.
Custom Logistic Regression Class:
 This is the class which is trained by the Newton-Raphson to optimize the iterates the specific number of iterations. This also ensures the preparation of the data and post processing of the data
Evaluation Of Performance:
In this the average performance accuracy of the Custom Logistic Regression Class provides the efficient classification of the tasks. By these we can assess how the implementation of custom works.
Data loading and preprocessing of the data:
Firstly the datasets will be readed using the Pandas, getting the features and extracting them and those are stored in the variable feat and that labels are encoded into numerical types using the factorize(). The code runs a loop and splits the data and tests the data and computes the accuracy using the accurate scores which we have acquired in the class and evaluating the stability and consistency.
Output:
Average accuracy using Custom Newton Classifier: 0.962
Average accuracy using scikit-learn's implementation: 0.945
“Newton’s Method Accuracy has been Achieved by Logistic Regression.” 
