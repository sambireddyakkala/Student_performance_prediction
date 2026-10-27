# Student Performance Prediction Using Machine Learning

## 📌 Project Overview

The **Student Performance Prediction System** is a Machine Learning project that predicts students' final academic grades based on their previous performance.

The project uses a student performance dataset and applies regression algorithms to estimate the final grade (`G3`). It also compares model performance using evaluation metrics and visualizes prediction results.

## 🎯 Objectives

- Predict students' final grades using Machine Learning.
- Analyze the relationship between previous grades and final grades.
- Train and evaluate multiple regression models.
- Compare model performance using evaluation metrics.
- Visualize actual and predicted student grades.

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 📂 Dataset

The project uses the `student_data.csv` dataset.

- **Number of records:** 395
- **Number of attributes:** 33
- **Target variable:** `G3` (Final Grade)
- **Important feature:** `G2` (Second Period Grade)

The dataset contains student-related information and academic performance details.

## ⚙️ Machine Learning Workflow

1. Load the student dataset.
2. Explore and analyze the data.
3. Select input features and target variable.
4. Split the dataset into training and testing sets.
5. Train multiple regression models.
6. Predict students' final grades.
7. Evaluate model performance.
8. Visualize actual and predicted grades.

## 🤖 Machine Learning Algorithms

The notebook compares multiple regression algorithms to evaluate their performance in predicting final grades.

The models are evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## 📊 Results and Visualization

The project generates:

- Model performance comparison
- Evaluation metrics
- Actual vs. predicted grade graph
- Sample student grade prediction

The analysis shows a strong relationship between second-period grades (`G2`) and final grades (`G3`).

## 🚀 How to Run the Project

### Option 1: Google Colab

1. Download the project notebook from this repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Select **File → Upload notebook**.
4. Upload the `.ipynb` notebook.
5. Click **Runtime → Run all**.
6. Upload `student_data.csv` when requested.

### Option 2: Run Locally

Clone the repository:

```bash
git clone https://github.com/Akkala Sambi Reddy/Student_performance_prediction.git
```

Open the project folder:

```bash
cd Student_performance_prediction
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

## 📁 Project Structure

```text
Student-Performance-Prediction/
├── Student_Performance_Prediction.ipynb
├── student_data.csv
├── README.md
└── requirements.txt
```

Make sure the notebook filename shown above matches the notebook you upload to GitHub.

## 🔮 Future Improvements

- Include more student-related features.
- Improve model performance through hyperparameter tuning.
- Develop a simple web application using Streamlit.
- Allow users to enter student details and predict grades.
- Explore classification methods to predict performance categories.

## 🎓 Applications

- Student academic performance analysis
- Educational data mining
- Early identification of students who may need academic support
- Machine Learning model development and evaluation

## 👨‍💻 Author

**Student Performance Prediction using Machine Learning**

Developed as a learning project to understand Machine Learning, regression algorithms, data preprocessing, and model evaluation.

## 📜 License

This project is intended for educational and learning purposes.
