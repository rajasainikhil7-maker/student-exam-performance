# 📊 Student Exam Performance Dashboard

A **Power BI dashboard** designed to analyze student academic performance and identify the factors that may be associated with exam results.

The project uses a student exam performance dataset containing academic, demographic, study-habit, lifestyle, and examination-related attributes. Interactive Power BI visuals are used to explore performance patterns and compare different student groups.

## 📌 Project Overview

The **Student Exam Performance Dashboard** provides insights into:

* Student exam scores
* Pass and fail status
* Performance grades
* Attendance and exam performance
* Study hours and exam scores
* Gender-wise performance
* Study and learning habits
* Student preparation and examination factors

The dashboard is designed to make student performance data easier to understand through interactive charts and filters.

## 🛠️ Tools & Technologies

* **Power BI**
* **Power BI Desktop**
* **DAX**
* **Data Visualization**
* **Data Analysis**
* **Power BI Slicers**

## 📂 Dataset

The Power BI data model contains a table named:

`student_exam_performance`

### Important Dataset Fields

| Category                 | Fields                                                                                                       |
| ------------------------ | ------------------------------------------------------------------------------------------------------------ |
| Student Information      | `student_id`, `age`, `gender`                                                                                |
| Education                | `education_level`, `school_type`, `parent_education`                                                         |
| Financial/Social         | `family_income`, `urban_rural`                                                                               |
| Academic Performance     | `previous_exam_score`, `previous_gpa`, `exam_score`, `performance_grade`, `pass_status`, `performance_level` |
| Attendance & Assignments | `attendance_percentage`, `assignment_completion_rate`, `class_participation`                                 |
| Study Habits             | `study_hours_per_day`, `self_study_hours`, `study_consistency`, `study_method`, `revision_frequency`         |
| Learning                 | `online_learning_hours`, `online_course_hours`, `educational_app_usage`                                      |
| Lifestyle                | `sleep_hours`, `sleep_quality`, `daily_screen_time`, `physical_activity_hours`                               |
| Examination              | `exam_difficulty`, `exam_preparation_days`, `questions_attempted`, `questions_correct`                       |
| Other Factors            | `time_management_score`, `exam_anxiety_level`, `stress_level`, `motivation_level`                            |

## 📊 Dashboard Visualizations

The dashboard contains multiple interactive visualizations.

### 1. Gender-wise Exam Score

A **Column Chart** compares the total exam score across genders.

**Fields used:**

* Axis: `gender`
* Values: `exam_score`

### 2. Pass Status Distribution

A **Donut Chart** displays the number of students according to their pass status.

**Fields used:**

* Category: `pass_status`
* Values: Count of `student_id`

### 3. Attendance vs Average Exam Score

An **Area Chart** analyzes the relationship between attendance percentage and average exam score.

**Fields used:**

* Axis: `attendance_percentage`
* Values: Average `exam_score`

### 4. Performance Grade Distribution

A **Pie Chart** shows the distribution of students across different performance grades.

**Fields used:**

* Category: `performance_grade`
* Values: Count of `student_id`

### 5. Gender Slicer

An interactive **Slicer** allows users to filter the dashboard by gender.

**Field:**

* `gender`

### 6. Study Hours vs Exam Score

A **Scatter Chart** explores the relationship between daily study hours and exam scores.

**Fields used:**

* X-axis: `study_hours_per_day`
* Y-axis: `exam_score`
* Category: `student_id`

The visualization also focuses on the top 10 students based on study hours.

### 7. Performance Grade Treemap

A **Treemap** represents the number of students in each performance grade.

**Fields used:**

* Group: `performance_grade`
* Values: Count of `student_id`

### 8. Gender-wise Pass Status

A **100% Stacked Bar Chart** compares pass status proportions across genders.

**Fields used:**

* Category: `gender`
* Series: `pass_status`
* Values: Count of `student_id`

## 🔍 Key Analysis Areas

The dashboard can be used to explore questions such as:

* How do exam scores differ across genders?
* What percentage of students passed?
* How does attendance relate to exam performance?
* Which performance grades are most common?
* Is there a relationship between study hours and exam scores?
* How does pass status vary between genders?
* What are the different student performance levels?
* How do study habits and lifestyle factors relate to academic performance?

## 📈 Dashboard Features

* Interactive Power BI visuals
* Gender-based filtering
* Multiple chart types
* Performance distribution analysis
* Academic performance analysis
* Study habit analysis
* Examination factor analysis
* Interactive cross-filtering between visuals

## 📁 Project Structure

```text
Student-Exam-Performance/
│
├── student exam performance.pbit
└── README.md
```

## 🚀 How to Use

1. Download or clone this repository.
2. Open **Power BI Desktop**.
3. Open the file:

```text
student exam performance.pbit
```

4. If Power BI asks for data-source information, provide the required dataset/source.
5. Refresh the data if required.
6. Use the dashboard visuals and slicer to explore student performance.

## 🎯 Project Objective

The main objective of this project is to demonstrate how **Power BI can transform student performance data into an interactive analytical dashboard**.

It can be used as a learning project for practicing:

* Data visualization
* Dashboard development
* Power BI
* DAX concepts
* Data analysis
* Interactive filtering
* Business intelligence reporting

## 💡 Skills Demonstrated

* Power BI Dashboard Development
* Data Analysis
* Data Visualization
* DAX
* Interactive Reports
* Slicers and Filters
* Chart Selection
* Academic Performance Analysis

## 📌 File Format

The main project file is provided in **`.pbit` (Power BI Template)** format.

> **Note:** A `.pbit` file is a Power BI template. Depending on how the template was created, the original external dataset may need to be connected or supplied when opening the file.

## 👨‍💻 Author

**Sai Nikhil**

---

⭐ If you find this project useful, consider giving the repository a star!
<img width="500" height="282" alt="Screenshot 2026-09-23 163115" src="https://github.com/user-attachments/assets/4bc4843a-ec66-4400-9609-584ae356a28e" />
