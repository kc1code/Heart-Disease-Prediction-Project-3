# Heart Disease Prediction using Logistic Regression 
  /)/)  
( . .)
( づ♡

This project implements a Logistic Regression model to predict the presence of heart disease using a public heart disease dataset. It helps in identifying whether a person is likely to have a heart attack based on medical attributes.

## 📂 Dataset
The dataset used includes features like:
- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Rest ECG
- Max Heart Rate Achieved
- Exercise Induced Angina
- ST Depression
- Slope of Peak Exercise ST Segment
- Number of Major Vessels
- Thalassemia
- Target (1 = Heart Disease, 0 = No Heart Disease)

## 🛠 Dependencies
Install the following libraries before running the project:
```bash
pip install numpy pandas scikit-learn
```

## 🚀 Project Workflow
### 1️⃣ Importing Dependencies
Essential libraries such as NumPy, Pandas, and Scikit-learn are imported.

### 2️⃣ Data Loading and Preprocessing
- CSV data is loaded into a Pandas DataFrame.
- Dataset is analyzed using `.info()`, `.describe()`, and `.isnull()` methods.
- Features (`X`) and target (`Y`) variables are separated.

### 3️⃣ Splitting the Dataset
- Dataset is split into training and testing sets with an 80-20 ratio.

### 4️⃣ Training the Model
- A **Logistic Regression** model is trained using the training dataset.

### 5️⃣ Model Evaluation
- Model accuracy is calculated for both training and testing datasets using `accuracy_score()`.

### 6️⃣ Predictive System
- A predictive system is built to classify new input data as either having heart disease or not.

## 📊 Results
- **Training Accuracy:** `{0.8512396694214877}`
- **Testing Accuracy:** `{0.819672131147541}`

_(Note: Accuracy may vary depending on the system run and dataset changes.)_

## 📜 Usage
Update the `input_data` tuple in the script with new values to make predictions:
```python
input_data = (62,0,0,140,268,0,0,160,0,3.6,0,2,2)
```
Run the script to check if the person has heart disease.

## 🔮 Future Improvements
- Use advanced models (Random Forest, SVM, XGBoost)
- Add data visualization for better insights
- Deploy the model using Flask or Streamlit for user interface

## 🤝 Contributing
Feel free to fork the repo, improve the model, and submit pull requests!

## 📜 License
This project is open-source and available under the **MIT License**.

---
✨ _Stay Healthy and Keep Learning!_ ✨

