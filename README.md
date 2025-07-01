🎓 Student Performance Prediction - ML Project
This project aims to predict whether a student will pass or fail based on various input features such as exam scores, parental education, gender, and test preparation. It uses a **Logistic Regression model** and includes data preprocessing, feature encoding, and evaluation metrics.

 📊 Dataset
- Source: [Kaggle - Student Performance Dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- Columns include:
  - Gender
  - Race/Ethnicity
  - Parental Level of Education
  - Lunch
  - Test Preparation Course
  - Math, Reading, and Writing Scores
  - 
 🔄 Workflow
1. **Data Cleaning & Exploration**
2. **Feature Engineering**: Created `average_score` and `pass`/`fail` labels
3. **Label Encoding**: Converted categorical features to numeric
4. **Model Training**: Logistic Regression
5. **Evaluation**: Accuracy, Classification Report, Confusion Matrix

 📈 Results
- **Accuracy**: ~85% (may vary based on test split)
- Model performs well in classifying student outcomes based on test scores and other inputs.

 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

 📁 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/Rayavarpu-kavya/student-performance-ml.git
