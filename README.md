# 🎓 Student Performance Analytics Dashboard

## ❓ Problem Statement

Educational institutions need early indicators of students who are likely to fail or drop out.  
This project analyzes academic and behavioral metrics to identify at-risk students.

---

## 🎯 Objective

- Analyze student performance data including:
  - Marks (Final Score)
  - Attendance (%)
  - Participation (as login/activity proxy)
- Calculate averages and correlations
- Visualize trends and risks using dashboards

---

## 📦 Dataset Overview

- Source: Student Behavior Dataset (Kaggle)
- Total Records: ~5000
- Key Features Used:
  - `Attendance (%)`
  - `Final_Score` → Renamed to `marks`
  - `Participation_Score` → Renamed to `logins`
- Removed unnecessary fields like Assignments, Projects, Quizzes for simplicity

---

## 📊 Key Analyses

### ✔️ Averages
- **Marks**: 69.55  
- **Attendance**: 75.36%  
- **Logins**: 49.96  

### ✔️ Correlation Matrix
- Heatmap showing correlation between:
  - Marks
  - Attendance
  - Logins

### ✔️ Absentee Impact
- Comparison of average marks for:
  - High Attendance students
  - Low Attendance students

### ✔️ Student Risk Groups
- Top 10 students (by marks)
- Bottom 10 students (at risk)
- Shown using colored bar charts

---

## 📊 Final Dashboard Output

![Dashboard](https://github.com/LAXMAN7795/Student-Performance-Analytics-Dashboard/blob/8700fcf6ca750c0a55901e57bd67e6284c21c2a2/output/student_performance_dashboard.png)

---

## 📁 File Structure

├── Student_Performance_Dashboard.ipynb
├── Students Performance Dataset.csv
├── outputs/
│ └── student_performance_dashboard.png
└── README.md

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/student-performance-dashboard.git
   cd student-performance-dashboard
Open the notebook:

Use Google Colab or Jupyter

File: Student_Performance_Dashboard.ipynb

Run all cells to reproduce the dashboard.

✅ Conclusion
This dashboard gives educators a clear, data-driven overview of student engagement and achievement.
While correlations are weak, the visual insights help identify both high performers and at-risk students.

🙌 Acknowledgment
Thanks to open data contributors on Kaggle.
