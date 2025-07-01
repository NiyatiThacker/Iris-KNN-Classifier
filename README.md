# 🌸 K-Nearest Neighbors (KNN) Classifier – Iris Dataset

## 📌 Objective
To implement and understand the **K-Nearest Neighbors (KNN)** algorithm for a multi-class classification problem using the **Iris flower dataset**. This includes preprocessing, model training, evaluation, tuning hyperparameters, and visualizing decision boundaries.

---

## 🛠️ Tools & Libraries
- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Scikit-learn (KNeighborsClassifier, metrics, preprocessing)

---

## 📁 Dataset Overview

- **Dataset**: Iris Flower Dataset (CSV)
- **Features**:
  - Sepal Length (cm)
  - Sepal Width (cm)
  - Petal Length (cm)
  - Petal Width (cm)
- **Target**: Species (`Setosa`, `Versicolor`, `Virginica`)

---

## 📊 Jupyter Notebooks

| Notebook                     | Description                                             |
|------------------------------|---------------------------------------------------------|
| `whatisKNN.ipynb`            | Conceptual explanation: What, Why, and How of KNN       |
| `knnClassifier.ipynb`        | Full implementation with step-by-step breakdown         |


---

## 🔢 Key Steps

### ✅ Step 1: Load the Dataset
- Loaded from a `.csv` file
- Extracted feature matrix `X` and label vector `y`
- Mapped numeric labels to flower species

### ✅ Step 2: Normalize the Features
- Used `StandardScaler` to bring all features to same scale (mean=0, std=1)

### ✅ Step 3: Train-Test Split
- 80% training, 20% testing using `train_test_split`

### ✅ Step 4: Train the KNN Model
- Used `KNeighborsClassifier(n_neighbors=3)`
- Model “memorizes” training data and predicts based on proximity

### ✅ Step 5: Model Evaluation
- Accuracy Score: `1.00`
- Perfect confusion matrix
- Classification Report with 100% precision, recall, F1-score

### ✅ Step 6: Accuracy vs K Plot
- Tested K from 1 to 20
- Accuracy was `1.00` for all K values (due to clean dataset)

### ✅ Step 7: Visualize Decision Boundaries
- Used 2D (sepal length & width, petal length & width) to visualize class regions
- Showed smooth, adaptive decision surfaces

---

## 📸 Outputs & Visualizations

### ✔️ Accuracy vs K Value
![image](https://github.com/user-attachments/assets/14a8ad1d-eb06-4e04-adf3-295d452980c6)


### ✔️ Decision Boundary (K=3)
 - Sepal Length & Width
   ![image](https://github.com/user-attachments/assets/6a92944c-3aeb-42ca-9be2-68091db27bcb)

 - Petal Length & Width
   ![image](https://github.com/user-attachments/assets/0cf1175a-e109-49ae-9e40-f4d872feb152)





---

## 📚 What I Learned
- KNN Fundamentals: Learned how KNN works as a lazy learner, storing training data and predicting based on the majority class of the nearest neighbors using distance metrics.

- Feature Scaling: Understood the importance of normalizing features to ensure fair distance comparisons, especially in distance-based models like KNN.

- Tuning K (Hyperparameter): Explored how different values of K affect model performance and the trade-off between overfitting (low K) and underfitting (high K).

- Evaluation Techniques: Used accuracy score, confusion matrix, and classification report to thoroughly evaluate the model’s performance and understand its predictions.

- Visual Insights: Visualized decision boundaries to see how KNN separates classes in 2D space, and how the shape of those boundaries changes with K.

- Full ML Workflow: Gained experience with an end-to-end machine learning pipeline including preprocessing, modeling, tuning, evaluation, and interpretation — documented clearly with what, why, and how at each step.

---

## 🧠 Author
**Niyati Thacker**  
📧 Email: niyatiswork1@gmail.com  
🐱 GitHub: [NiyatiThacker](https://github.com/niyatithacker)




