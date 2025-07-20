## 👤 Extrovert vs. Introvert Behavior Prediction

### 📌 Project Overview

This project aims to predict whether an individual exhibits **extroverted or introverted behavior** based on various features such as time spent alone, social event attendance, friends circle size, and post frequency. The goal is to provide insights into personality traits based on observable behaviors.

-----

### ⚙️ Technical Highlights

  * **Dataset**: [Kaggle - Extrovert vs. Introvert Behavior Data](https://www.kaggle.com/datasets/rakeshkapilavai/extrovert-vs-introvert-behavior-data)
  * **Size**: 2900 entries, 8 columns (after initial loading)
  * **Key Features**:
      * Time\_spent\_Alone, Stage\_fear, Social\_event\_attendance, Going\_outside, Drained\_after\_socializing, Friends\_circle\_size, Post\_frequency
  * **Approach**:
      * Data Cleaning (Handling Missing Values, Dropping Duplicates)
      * Exploratory Data Analysis (Histograms, Boxplots, Heatmaps)
      * Label Encoding for Categorical Features
      * Binary Classification (Extrovert: `1`, Introvert: `0` - *assuming this mapping after encoding*)
      * Models Used:
          * Logistic Regression, Ridge Classifier, SVC, Random Forest, XGBoost, AdaBoost, Gradient Boosting, Bagging, Decision Tree
  * **Best Accuracy**:
      * $\\sim$93% with Gradient Boosting and SVC
      * $\\sim$92% with Logistic Regression and AdaBoost

-----

### 🎯 Purpose and Applications

  * Provide insights into personality traits based on behavioral data.
  * Potentially inform personalized recommendations for social interactions or work environments.
  * Support psychological research and behavioral studies.
  * Enhance understanding of social dynamics and individual preferences.

-----

### 🛠️ Installation

Clone the repository:

```bash
git clone https://github.com/BhaveshBhakta/Extrovert-vs.-Introvert-Behavior-Prediction-Using-ML.git
cd Extrovert-vs.-Introvert-Behavior-Prediction-Using-ML
```

Install the necessary libraries:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn xgboost
```

-----

### 🤝 Collaboration

We welcome contributions to improve the project. You can help by:

  * Improving model robustness via hyperparameter tuning.
  * Adding explainability (e.g., SHAP or LIME) for model predictions.
  * Exploring advanced feature engineering techniques.
  * Deploying the model via API or a web dashboard.
