# Students' performance prediction
This machine learning initiative focuses on the task of predicting the final grades for 107 enrolled students in a fully online, nine-week machine learning course. The study, administered via the Moodle learning management system, utilizes students' performance metrics, including mini projects, quizzes, peer reviews, and the final grade. Through essential phases like exploratory data analysis, data preprocessing, feature selection, and algorithm selection, the project consistently yields highly accurate models.

<a target="_blank" href="https://colab.research.google.com/github/vinaysanga/Student-Performance-Prediction/blob/master/MP2_Notebook.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## 1. Introduction
In the context of digital transformation in education, accurately predicting student performance in online courses becomes crucial for proactive intervention. The project uses a dataset from 107 students, employing a structured workflow for predictive modeling. Key phases include exploratory data analysis (EDA), data preprocessing, and feature selection, streamlining the feature set for subsequent analysis.

## 2. Data Preprocessing 
The data contains details about 107 students based on the following parameters:
- **Status0**: course / lectures / content related
- **Status1**: assignment relate
- **Status2**: grade related
- **Status3**: forum related

There are 9 grades related to different quizzes, mini projects, etc. Apart from these, there are 36 logs related to the status above.
The data has no null values and there are a total of 47 features. Out of these ’Week1_Stat1’ has positive correlation with every other variable.

**For the entire info, please check [MP2_Report](https://github.com/vinaysanga/Student-Performance-Prediction/blob/master/MP2_Report.pdf)**
