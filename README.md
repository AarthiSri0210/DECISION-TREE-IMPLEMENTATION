# DECISION-TREE-IMPLEMENTATION

**COMPANY**: CODETECH IT SOLUTIONS

**NAME**: PATHI AARTHI SRI

**INTERN ID**: CT4MJWB

**DOMAIN**: MACHINE LEARNING

**DURATION**: 16 WEEKS

**MENTOR**: NEELA SANTOSH

# DESCRIPTION 

The goal of this project is to classify Iris flowers using a **Decision Tree Model**. The model is trained on the **Iris dataset**, which contains three species of flowers: **Setosa, Versicolor, and Virginica**. The dataset includes four features:
- Sepal length
- Sepal width
- Petal length
- Petal width

### **Steps Performed**
1. **Data Loading & Preprocessing**
   - Loaded the Iris dataset using `sklearn.datasets.load_iris()`.
   - Converted it into a Pandas DataFrame for easier manipulation.
   - Saved the dataset in CSV format.

2. **Model Training**
   - Split the dataset into **80% training and 20% testing**.
   - Trained a **Decision Tree Classifier** using `sklearn.tree.DecisionTreeClassifier`.
   - Used the **Gini index** as the criterion and limited tree depth to **3** to prevent overfitting.

3. **Evaluation & Testing**
   - Predicted labels for the test set.
   - Evaluated performance using **Accuracy Score, Classification Report, and Confusion Matrix**.

4. **Visualization**
   - Used `sklearn.tree.plot_tree()` to visualize the decision tree structure.
   - Saved the visualization as `decision_tree.png`.

5. **Model Saving**
   - Saved the trained model as `decision_tree_model.pkl` using `joblib.dump()`.

## 📊 Results & Visualizations
- **Model Accuracy:** Displays test accuracy and a classification report.
- **Confusion Matrix:** Provides insights into prediction performance.
- **Decision Tree Visualization:** The decision tree is saved as `visualizations/decision_tree.png`.

## 🌍 Applications of Decision Tree Models
- **Medical Diagnosis:** Used to classify diseases based on symptoms.
- **Spam Detection:** Helps classify emails as spam or not.
- **Customer Segmentation:** Used in marketing to group similar customers.
- **Fraud Detection:** Identifies suspicious transactions in finance.

## 📦 Dependencies
- Python 3.x
- Scikit-Learn
- Pandas
- NumPy
- Matplotlib
- Joblib

## 🔗 Resources
- [Iris Dataset](https://archive.ics.uci.edu/ml/datasets/Iris)
- [Scikit-Learn Documentation](https://scikit-learn.org/)

# OUTPUT

![Image](https://github.com/user-attachments/assets/7056d02d-a951-4670-ad7a-55a6f8a3e8a8)
