# Phishing URL Detection Using Decision Tree

## 📌 Project Overview

This project uses Machine Learning to detect phishing URLs using the **Decision Tree Classification algorithm**. It analyzes numerical features from the PhiUSIIL Phishing URL Dataset to classify URLs into phishing and legitimate categories.

The model is trained and evaluated using Python and Scikit-learn. It also visualizes the decision tree and confusion matrix to understand the model's predictions.

## 🎯 Objectives

- Detect phishing URLs using Machine Learning.
- Preprocess the dataset and handle missing or infinite values.
- Train a Decision Tree Classifier.
- Visualize the decision tree structure.
- Evaluate model performance using classification metrics.

## 🛠️ Technologies Used

- **Python** – Programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Scikit-learn** – Machine Learning and model evaluation
- **Google Colab / Jupyter Notebook** – Development environment

## 📂 Dataset

**Dataset Name:** PhiUSIIL Phishing URL Dataset

The dataset contains URL-related features and a target column named `label`. The project uses numerical columns as input features and the `label` column to create the target classes.

Dataset preprocessing includes:
- Removing records with missing target labels.
- Selecting numerical features.
- Replacing infinite values with missing values.
- Filling missing feature values with their median.

## ⚙️ Project Workflow

1. Import the required Python libraries.
2. Load and explore the dataset.
3. Preprocess the data and select numerical features.
4. Split the dataset into 80% training data and 20% testing data.
5. Train a Decision Tree Classifier with a maximum depth of 5.
6. Visualize the trained decision tree.
7. Predict the classes of test data.
8. Display the confusion matrix.
9. Evaluate the model using performance metrics.

## 🤖 Machine Learning Algorithm

### Decision Tree Classifier

A Decision Tree is a supervised Machine Learning algorithm that makes predictions using a tree-like structure of decision rules. It learns patterns from training data and uses those patterns to classify new records.

In this project, the classifier uses:
- `max_depth=5` to limit the tree depth.
- `class_weight="balanced"` to account for class imbalance.
- `random_state=42` for reproducible model training.

## 📊 Model Evaluation

The model is evaluated using the following metrics:

- **Accuracy:** Measures the overall proportion of correct predictions.
- **Precision:** Measures how many predicted phishing cases are actually phishing.
- **Recall:** Measures how many actual phishing cases are correctly detected.
- **F1-Score:** Balances precision and recall.
- **Specificity:** Measures how many legitimate cases are correctly identified.

The project also generates a confusion matrix to show correct and incorrect classifications.

## ▶️ How to Run the Project

1. Clone or download this repository.
2. Install the required Python libraries:

   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```

3. Place the dataset CSV file in the appropriate location.
4. Open `Decision_Tree_ML.ipynb` in Google Colab or Jupyter Notebook.
5. Update the dataset file path in the notebook if necessary.
6. Run all cells in order to train and evaluate the model.

## 📁 Project Structure

```text
Phishing-URL-Detection/
│
├── Decision_Tree_ML.ipynb
├── PhiUSIIL_Phishing_URL_Dataset.csv
└── README.md
```

*Note: The dataset file must be available at the path specified in the notebook. Include it in the repository only if its size and licensing permit.*

## 🔮 Future Enhancements

- Compare Decision Tree performance with Random Forest and other classification algorithms.
- Improve feature selection and model evaluation.
- Build a simple web application for URL classification.
- Integrate the trained model into a phishing detection tool.

## 📝 Conclusion

This project demonstrates how Machine Learning can be used to identify potential phishing URLs using a Decision Tree Classifier. It covers data preprocessing, model training, prediction, visualization, and evaluation.

**Disclaimer:** This project is intended for educational purposes. Predictions should not be treated as a guarantee that a URL is safe or malicious.

## 👩‍💻 Author

**Archana Devi M.**
