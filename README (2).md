
# Weather Prediction Using Naive Bayes Classifier

This project demonstrates a simple weather prediction model using the **Naive Bayes classifier**. The model predicts whether to **"Play"** or **"Not Play"** based on various weather conditions from a historical dataset.

## 📁 Dataset

The dataset used in this project is `large_weather_dataset.csv`, which contains weather-related features along with the target column `Play`.

## 📌 Features Used

The dataset typically includes features such as:

- Temperature  
- Humidity  
- Outlook  
- Windy  
- ...and other weather attributes

> **Target variable**: `Play` — Indicates whether a game was played or not.

## 🛠️ Technologies & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib

## 🚀 Steps Performed

### 1. Data Collection
- Loaded the dataset using Pandas.

### 2. Data Preprocessing
- Checked for and removed missing values.
- Encoded categorical variables using `LabelEncoder`.
- Normalized numerical features using `StandardScaler`.

### 3. Model Implementation
- Split the dataset into training and testing sets.
- Trained a **Gaussian Naive Bayes** model on the training data.

### 4. Model Evaluation
- Evaluated using:
  - Accuracy Score
  - Classification Report
  - Confusion Matrix (visualized using Seaborn heatmap)

### 5. Prediction
- Compared actual vs predicted values on the test set.
- Displayed a sample of predictions.

## 📈 Sample Output

- **Accuracy** of the model is printed.
- **Classification report** with precision, recall, and F1-score.
- **Confusion Matrix** for visual evaluation.
- **Sample predictions** with actual vs predicted outcomes.

## 🧪 How to Run

1. Make sure the dataset `large_weather_dataset.csv` is in the same directory.
2. Run the Python script in your environment (e.g., Jupyter Notebook or any IDE that supports Python).

```bash
python weather_prediction.py
```

## ✅ Requirements

Install the following Python libraries if not already installed:

```bash
pip install pandas numpy scikit-learn seaborn matplotlib
```

## 📬 Sample Predictions Output

| Feature Columns | Actual | Predicted |
|-----------------|--------|-----------|
| (Normalized data...) | Yes/No | Yes/No |

## 📄 License

This project is open-source and free to use for educational purposes.
