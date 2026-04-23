# 🚀 SpaceX Falcon 9 Landing Prediction

![SpaceX Banner](https://img.shields.io/badge/SpaceX-Falcon9-blue?style=for-the-badge&logo=spacex)
![Python](https://img.shields.io/badge/Python-3.8+-yellow?style=for-the-badge&logo=python)
![Machine Learning](https://img.shields.io/badge/ML-Scikit--Learn-orange?style=for-the-badge&logo=scikit-learn)

### 📖 Project Overview
SpaceX has revolutionized space travel by making rockets reusable. A traditional launch costs around **$165 million**, but SpaceX does it for just **$62 million** by landing the first stage and using it again. This project uses Machine Learning to predict whether a rocket will land safely or crash.

---

### 🎯 Goals
- **Predict** whether the Falcon 9 first stage will land successfully.
- **Compare** different **Machine Learning models** to find the best one.
- **Identify** the **most reliable model for identifying risky landings**.

---

### 🛠️ Tools I Used
- **Python :** The main language.
- **Pandas & NumPy :** For cleaning the data.
- **Matplotlib & Seaborn :** For visualization.
- **Scikit-learn :** For training Machine Learning models.

---

### 🔍 The Analysis (The ML Pipeline)
To find the answer, I followed these 6 professional steps:

1. **Data Exploration :** Looking at the history of Falcon 9 launches.
2. **Data Cleaning :** Fixing missing information, such as Landing Pad data.
3. **Preprocessing :** Turning categorical values into numbers and scaling features.
4. **Model Training :** Training 4 different algorithms : **Logistic Regression, SVM, Decision Tree, and KNN**.
5. **Hyperparameter Tuning :** Using `GridSearchCV` to find the best settings for each model.
6. **Evaluation :** Testing the models on new, unseen data.

---

### 📊 Model Comparison Results
After putting the models through a final evaluation, here is their performance:

| Model | Accuracy | Recall (Class 0 - Risk) | F1-Score |
| :--- | :---: | :---: | :---: |
| **Decision Tree** | 🟢 **89%** | **82%** | **89%** |
| **Logistic Regression** | 🟡 89% | 73% | 88% |
| **SVM** | 🟡 89% | 73% | 88% |
| **KNN** | 🔴 85% | 64% | 84% |

---

### 🏆 Final Conclusion
While Logistic Regression and SVM achieved high accuracy, the **Decision Tree** emerged as the best model.

**Why?** In space travel, failing to detect a crash is much more dangerous than missing a successful landing. The Decision Tree was the **most reliable model for identifying risky landings** (**82% Recall for Class 0**), making it the **most suitable choice for this project**.

---

### ⚙️ How to Run
To run this project locally, follow these steps:

1. **Clone the repository :**

   ```bash
   git clone https://github.com/ZahraAbedi1995/SpaceX_project.git
   ```

2. **Install the required libraries :**

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

3. **Open the notebook :**

   Launch Jupyter Notebook and open `SpaceX_project.ipynb`.
  
   
