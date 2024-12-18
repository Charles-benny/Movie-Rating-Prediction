# Movie-Rating-Prediction
This ML project focused on predicting audience ratings for movies using a given dataset. The project demonstrates end-to-end implementation, from data preprocessing to model training, evaluation, and deployment-ready code. 
## Content
The goal of this project is to build a model to predict the **`audience_rating`** based on various features in the dataset, such as movie genre, critics consensus, ratings, and other attributes. This repository includes a complete pipeline for preprocessing the data, engineering features, training and validating multiple machine learning models, and selecting the best-performing model.

---

## Features
- **Data Preprocessing:**
  - Handling missing values in numerical and categorical columns.
  - Sentiment analysis of textual data (e.g., `critics_consensus`).
  - One-hot encoding for categorical features like `genre` and `rating`.
  - Scaling of numerical features.

- **Pipeline Construction:**
  - Modular and reusable pipeline using `sklearn.Pipeline` and `sklearn.compose.ColumnTransformer`.

- **Model Training:**
  - Experimentation with multiple regression models:
    - Linear Regression
    - Random Forest Regressor
    - Gradient Boosting Regressor
    - Extra Trees Regressor
  - Evaluation metrics include:
    - Mean Absolute Error (MAE)
    - Root Mean Squared Error (RMSE)
    - R-Squared (R²)

- **Model Validation:**
  - Train-test split for testing performance.
  - Comparative visualization of model performance.

---

## 📊 **Dataset**
The dataset used in this project includes the following key features:
- `genre`: Categorical representation of movie genres.
- `rating`: Movie ratings such as PG, PG-13, R, etc.
- `critics_consensus`: A textual column containing critics' summary.
- `runtime`, `year`, and other numeric attributes.

**Target Variable:** `audience_rating`

---

## 🛠️ **Tech Stack**
- **Python Libraries:**
  - `pandas`, `numpy` - Data manipulation and analysis.
  - `scikit-learn` - Machine learning pipeline, preprocessing, and model training.
  - `nltk` - Sentiment analysis of textual data.
  - `matplotlib`, `seaborn` - Data visualization.

---
