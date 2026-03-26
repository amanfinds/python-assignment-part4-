#  Student Performance Analysis & Prediction

##  Project Overview
This project analyzes student performance data using **Data Analysis, Visualization, and Machine Learning** techniques.  
It explores patterns in student scores and builds a predictive model to determine whether a student will **Pass or Fail**.

---

##  Dataset Information
The dataset contains performance details of 15 students with the following features:

- Academic Scores: Math, Science, English, History, PE  
- Attendance Percentage  
- Study Hours per Day  
- Target Variable: `passed` (1 = Pass, 0 = Fail)

---

##  Technologies Used
- Python   
- Pandas (Data Analysis)  
- Matplotlib (Visualization)  
- Seaborn (Advanced Visualization)  
- Scikit-learn (Machine Learning)  
- Google Colab  

---


##  Key Analysis Performed

###  Data Exploration
- Checked dataset structure, types, and summary statistics  
- Compared subject scores for passing vs failing students  
- Identified top-performing student  

---

###  Data Visualization

#### Matplotlib Plots:
1. Bar Chart — Average score per subject  
2. Histogram — Distribution of math scores  
3. Scatter Plot — Study hours vs average score  
4. Box Plot — Attendance comparison (Pass vs Fail)  
5. Line Plot — Math vs Science scores  

#### Seaborn Plots:
6. Bar Plot — Math & Science vs Pass/Fail  
7. Scatter Plot — Attendance vs performance with regression lines  

---

##  Machine Learning Model

### Model Used:
- Logistic Regression

### Features:
- Subject scores  
- Attendance  
- Study hours  

### Steps:
- Data splitting (80% train / 20% test)  
- Feature scaling using StandardScaler  
- Model training and evaluation  

---

##  Results

- Training Accuracy: *(varies)*  
- Test Accuracy: *(depends on small dataset)*  

> Note: Due to the small dataset size, accuracy may vary significantly.

---

##  Feature Importance
- Model coefficients were analyzed to understand which features influence passing or failing.
- Positive coefficients → increase chance of passing  
- Negative coefficients → increase chance of failing  

---

##  Prediction Example
A new student’s performance was tested using the trained model to predict:
- Pass/Fail result  
- Probability of prediction  

---

##  Key Insights
- Higher study hours and attendance strongly correlate with better performance  
- Students with low scores and attendance are more likely to fail  
- Consistency across subjects improves chances of passing  

---

##  Limitations
- Very small dataset (15 students)  
- Model is for learning purposes, not real-world deployment  

---

##  How to Run
1. Open Google Colab  
2. Upload `part4_visualization_ml.ipynb`  
3. Run all cells sequentially  
4. Download generated plots  

---




