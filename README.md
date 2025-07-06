# Calories-Burned-Prediction
CalorieX
# 🔥 Calories Burned Prediction using XGBoost

A machine learning project that predicts the number of calories burned during physical activity using health metrics and XGBoost regression.

---

## 📌 Overview

This project focuses on predicting how many calories a person burns during exercise based on various physiological factors such as:
- Age
- Gender
- Height
- Weight
- Exercise duration
- Heart rate
- Body temperature

The model is trained using the powerful XGBoost Regressor, which delivers high accuracy and low error on real-world health data.

---

## 🚀 Tech Stack

- **Python**
- **Pandas** & **NumPy** (Data Handling)
- **Matplotlib** & **Seaborn** (Data Visualization)
- **Scikit-learn** (Model Evaluation & Splitting)
- **XGBoost** (Regression Model)
- **Google Colab** (Development Environment)

---

## 📊 Dataset Used

- `calories.csv`: Contains calorie data for different users.
- `exercise.csv`: Contains physical and physiological data like heart rate, duration, etc.
- Total Samples: `15,000`

---

## 🧪 Steps Performed

1. **Data Loading**  
   Combined two CSV files into one DataFrame.

2. **Data Cleaning**  
   Checked for missing values and replaced categorical values with numeric equivalents.

3. **Exploratory Data Analysis**  
   Used distribution plots and heatmaps to understand data patterns and correlations.

4. **Feature Engineering**  
   Removed unnecessary columns like `User_ID` and converted `Gender` to binary.

5. **Model Training**  
   Trained an XGBoost Regressor on the data using an 80-20 train-test split.

6. **Evaluation**  
   - Metric Used: **Mean Absolute Error (MAE)**
   - Result: `MAE = 1.48`

---

## 📈 Result

The model was able to predict calorie burn with high accuracy:
Mean Absolute Error = 1.48
This means the average prediction error is just **1.48 calories**, which is excellent considering real-world data noise.

---

## 📌 How to Run

1. Upload the notebook to [Google Colab](https://colab.research.google.com/)
2. Upload both datasets: `calories.csv` and `exercise.csv`
3. Run each cell step-by-step


Calories-Burned-Prediction/
│
├── Calories Burnt Prediction.ipynb
├── calories.csv
├── exercise.csv
├── README.md




---

## 💡 Future Improvements

- Add more features like BMI, fitness level, or daily activity score.
- Try other regression models for comparison.
- Deploy using Streamlit for user interaction.

---

## 👨‍💻 Author

**Het Shah**  
📍 Mumbai, India  
🎓 Electronics & Telecommunication Engineer with Data Science 
💼 Aspiring Data Analyst / ML Developer / Data Scientist 
📫 [LinkedIn](https://www.linkedin.com/in/hetchiragshah/) 

---

⭐ *If you like this project, consider giving it a star!*
