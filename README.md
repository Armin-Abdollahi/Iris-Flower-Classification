# Iris-Flower-Classification

The iris dataset contains three classes of flowers, Versicolor, Setosa, Virginica, and each class contains 4 features, ‘Sepal length’, ‘Sepal width’, ‘Petal length’, ‘Petal width’. The aim of the iris flower classification is to predict flowers based on their specific features.

Support Vector Machine (SVM): A support vector machine (also known as a support vector network) is a supervised machine learning algorithm that analyzes data for classification and regression. SVMs are one of the most robust classifications methods. SVM approximates a separate line (Hyperplane) between two classes. SVM algorithm finds the points closest to the line from both classes. These points are known as support vectors. Then it computes the distance between the line and support vectors. This distance is called the margin. The main goal is to maximize the margin. The hyperplane which has the maximum margin is known as the optimal hyperplane. SVM mainly supports binary classification natively. For multiclass classification, It separates the data for binary classification and utilizes the same principle by breaking down multi-classification problems into multiple binary classification problems.

Prerequisites:
1. Numpy
2. Matplotlib
3. Seaborn
4. Pandas
5. Scikit-learn

Steps to Classify Iris Flower:
1. Load the data
2. Analyze and visualize the dataset
3. Model training.
4. Model Evaluation.
5. Testing the model.

Step 1 – Load the data:
First, we’ve imported some necessary packages for the project.
- Numpy will be used for any computational operations.
- We’ll use Matplotlib and seaborn for data visualization.
- Pandas help to load data from various sources like local storage, database, excel file, CSV file, etc.
- Next, we load the data using pd.read_csv() and set the column name as per the iris data information.
- Pd.read_csv reads CSV files. CSV stands for comma separated value.
- df.head() only shows the first 5 rows from the data set table.
- All the numerical values are in centimeters.

Step 2 – Analyze and visualize the dataset:
