# 🎓 Student Marks Prediction

An interactive **Machine Learning web app** built using **Streamlit** that predicts a student’s marks based on study habits and academic factors.  
The app provides **accurate predictions**, **performance insights**, **factor analysis**, and **personalized recommendations** to help students improve their scores.

This project uses **Random Forest** and **Linear Regression**, allows **CSV upload**, supports **model retraining**, and includes a rich, **dashboard-style UI**.

---

## ⭐ Features

### 🔍 1. Predict Marks Using ML
- Enter details: **Study Hours, Attendance, Sleep Hours, Internet Usage, Previous Marks**
- Real-time mark prediction (0–100 scale)
- Includes model confidence score

### 📊 2. Dataset Handling
- Upload your own CSV dataset  
- Dataset preview  
- Summary statistics  
- Validation of required columns  

### 🧠 3. Model Training
Choose between:
- 🌲 **Random Forest**
- 📈 **Linear Regression**

Hyperparameters supported:
- `n_estimators`
- `max_depth`

ML Pipeline includes:
- Train/Test split (80/20)
- Metrics:
  - **R² Score**
  - **MAE (Mean Absolute Error)**
- Trained model auto-saved using **joblib**

### 📈 4. Visualizations & Analytics
- Scatter Plot: **Study Hours vs Marks**
- Performance Comparison Graph
- Factor-wise detailed analysis
- Study efficiency breakdown
- Personalized recommendations

### 📘 5. Improvement Suggestions
- Study hours target  
- Attendance improvement guidance  
- Sleep cycle recommendations  
- Internet usage optimization  
- Combined improvement strategy  
- Future score estimation  

### 📤 6. Export Options
- Export predicted result as **CSV**  
- Download detailed result report as **PDF**  

---

## 🛠️ Tech Stack

| Category | Tools |
|----------|--------|
| Frontend | Streamlit |
| ML Models | Random Forest, Linear Regression |
| ML Libraries | Scikit-learn |
| Data Processing | Pandas, NumPy |
| Visualization | Plotly |
| Model Storage | Joblib |

---
### 📥 **Uploading Your Own Dataset**

- Click Browse Files in the sidebar
- Upload a CSV
- App automatically:
- Validates columns
- Shows dataset preview
- Displays statistics
- Allows retraining anytime

---
## 🔬 **How the Model Works**
**1. Training**
- Choose Random Forest or Linear Regression
- Select hyperparameters
- App:
   - Splits dataset (80/20)
   - Trains model
   - Calculates:
      - R²
      - MAE
Saves model to:
```
models/student_mark_model.pkl
```

---

## 🚀 Installation & Setup

### **Prerequisites**
- Python **3.8+**  
- pip installed  

---

### **1. Clone the Repository**
```bash
git clone https://github.com/surajpathak23/Student-Marks-Prediction.git
cd Student-Marks-Prediction
```

---
## Contact
📌 *Author: Suraj Kumar*
🔗 [LinkedIn](https://www.linkedin.com/in/suraj-kumar-2307skp/) | [GitHub](https://github.com/surajpathak23) | [WhatsApp](https://wa.me/919142496994)
