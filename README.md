Decision Tree Classification for Social Network Ads
This project implements a Decision Tree classifier to predict whether users will purchase a product based on their age and estimated salary from social network ads data.

Key Features
Data Preprocessing: Standard scaling for feature normalization

Model Training: Decision Tree classifier with hyperparameter tuning

Evaluation Metrics: Confusion matrix, accuracy score, and classification report

Visualizations:

Decision boundaries for training and test sets

Feature importance analysis

Precision-Recall curve

Full Decision Tree visualization

Hyperparameter Optimization: GridSearchCV for finding optimal parameters

Technologies Used
Python 3

Scikit-learn

Pandas

NumPy

Matplotlib

Jupyter Notebook

How It Works
Data is loaded and split into training/test sets

Features are scaled using StandardScaler

Optimal hyperparameters are found using GridSearchCV

Decision Tree model is trained with best parameters

Model performance is evaluated on test data

Various visualizations are generated to understand model behavior

Usage
Clone the repository

Install required packages: pip install -r requirements.txt

Run the Jupyter notebook: jupyter notebook Decision_Tree_Classification.ipynb

Results
The model achieves 91% accuracy on the test set with the following performance metrics:

Precision: 0.91

Recall: 0.83

F1-score: 0.87
