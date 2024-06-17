# Dialy_DSA-100-days

## Daily Log

### Day 25 - June 17, 2024

**Today's Focus:** Participating in an AI Hackathon and focusing mostly on ML Algorithms
![image](https://github.com/ajaykr2712/Dialy_DSA-100-days/assets/112938234/42f3ccc7-016d-43b7-a912-e8ea6c00055e)

**Resources Used:**
- 📖 <a href="https://www.deeplearningbook.org/">Deep Learning by Ian Goodfellow, Yoshua Bengio, and Aaron Courville</a>
- 🌐 <a href="https://www.coursera.org/learn/machine-learning">Coursera - Machine Learning by Andrew Ng</a>
- 🌐 <a href="https://scikit-learn.org/stable/">Scikit-learn Documentation</a>

**Activities:**
- 📝 Participated in an AI Hackathon, collaborating with a team to solve real-world problems using ML algorithms.
- 📌 Worked on implementing and fine-tuning various machine learning models.

**Detailed Notes:**
- 📝 ML Algorithms Explored:
  - **Linear Regression:** Simple and efficient for linear relationships between variables.
  - **Decision Trees:** Non-linear models that split data into subsets based on feature values.
  - **Random Forest:** An ensemble method using multiple decision trees to improve accuracy.
  - **Support Vector Machines (SVM):** Effective for high-dimensional spaces and used for classification tasks.
  - **K-Nearest Neighbors (KNN):** A simple, instance-based learning method for classification and regression.
  - **Neural Networks:** Deep learning models that are powerful for complex patterns and large datasets.

**Code Snippets:**
```python
# Example of a simple Decision Tree Classifier using scikit-learn
from sklearn.datasets import load_iris
from sklearn.tree import DecisionTreeClassifier
from sklearn.model_selection import train_test_split
from sklearn.metrics import accuracy_score

# Load dataset
iris = load_iris()
X, y = iris.data, iris.target

# Split dataset into training and test sets
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.3, random_state=42)

# Initialize and train the model
clf = DecisionTreeClassifier()
clf.fit(X_train, y_train)

# Predict and evaluate
y_pred = clf.predict(X_test)
accuracy = accuracy_score(y_test, y_pred)
print(f'Accuracy: {accuracy}')
Reflections:

🤔 Working on real-world problems in the hackathon provided hands-on experience with ML algorithms.
🚀 Collaborating with a team helped in learning new techniques and best practices in machine learning.
