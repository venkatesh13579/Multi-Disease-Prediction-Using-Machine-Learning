# Diabetes Prediction Using Machine Learning

This project predicts whether a person is diabetic or not using machine learning algorithms, particularly **Support Vector Machine (SVM)** and **Logistic Regression**. It uses the Pima Indians Diabetes Dataset.

---

## 📊 Dataset

The dataset used is the **Pima Indians Diabetes Database**, typically found as `diabetes.csv`.

- **Target variable**: `Outcome` (1 = diabetic, 0 = non-diabetic)
- **Features**:
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age

---

## 🧠 Models Used

- **Support Vector Machine (SVM)** with linear kernel
- **Logistic Regression** (imported but not used in the final code)

---

## 🔧 Dependencies

Install the following Python libraries:

pip install numpy pandas scikit-learn

🚀 How to Run

Clone the repository or copy the code into your local project directory.

Ensure the diabetes.csv file is in the specified location (/content/diabetes.csv if using Colab or update to your path).

Run the Python script.

📈 Model Training & Evaluation

The dataset is split into training and testing sets using train_test_split.

SVM is trained using the training set.

Accuracy scores are printed for both training and testing datasets.

📦 Model Saving & Loading

The trained SVM model is saved using pickle as diabetes_model.sav.

The saved model is reloaded and tested with the same input to ensure consistency.
