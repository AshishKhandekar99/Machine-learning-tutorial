# Machine-learning-tutorial
In this assignment, I am preparing a tutorial on a machine-learning technique.

README - Decision Tree Classifier on Wine Dataset
=================================================

**Project Title:**
Understanding Decision Trees: The Impact of Hyperparameters on Model Performance

**Description**:
This project demonstrates how various hyperparameters impact the performance of a Decision Tree classifier using the Wine dataset from the UCI Machine Learning Repository.

**Dataset**:
- Wine Dataset (178 samples, 13 features, 3 target classes)
- Source: scikit-learn's load_wine

**Key Components**:
- Data preprocessing using StandardScaler
- Hyperparameter experiments:
  - max_depth: [3, 5, 10, None]
  - min_samples_split: [2, 5, 10]
  - criterion: ['gini', 'entropy']
- Performance evaluation using accuracy and confusion matrix
- Visualization of results: learning curves, accuracy vs. hyperparameters, feature importance
- GridSearchCV for advanced hyperparameter tuning

**Best Model Configuration**:
- max_depth = 5
- min_samples_split = 2
- criterion = 'entropy'
- Achieved over 96% accuracy on test set

**Tools Used**:
- Python 3.x
- scikit-learn
- matplotlib
- seaborn
- pandas, numpy

**How to Run**:
Open the notebook (.ipynb file) in Jupyter Notebook or Google Colab and run the cells in sequence.

**Author**:
Ashish Khandekar

**References**:
- UCI Machine Learning Repository
- Scikit-learn Documentation
- Breiman et al., Classification and Regression Trees (1984)
