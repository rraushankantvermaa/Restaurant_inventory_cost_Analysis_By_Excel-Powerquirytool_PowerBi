# 📊 Learning Management System (LMS) Restaurant inventory and cost Analysis— Power BI Dashboard

## 📌 Project Overview

This project is an interactive **Learning Management System (LMS) of Restaurant inventory and cost Analysis** developed using **Microsoft Power BI**.

The dashboard analyzes LMS-related data to provide meaningful insights into learner performance, course activity, engagement, completion, and other key performance indicators.

The goal of this project is to transform raw LMS data into an interactive business intelligence dashboard that can help organizations understand learning trends and make data-driven decisions.

---

## 🎯 Project Objectives

* Analyze learner and course-related data.
* Track important LMS performance indicators.
* Identify trends and patterns in learning activity.
* Analyze course completion and learner performance.
* Create interactive dashboards for business users.
* Provide actionable insights using data visualization.
* Demonstrate practical Power BI and data-analysis skills.

---

## 🛠️ Tools & Technologies

| Tool                      | Purpose                                      |
| ------------------------- | -------------------------------------------- |
| **Microsoft Power BI**    | Data visualization and dashboard development |
| **Power Query**           | Data cleaning and transformation             |
| **DAX**                   | Measures and calculated metrics              |
| **Microsoft Excel / CSV** | Data source and data preparation             |
| **GitHub**                | Project documentation and version control    |

---

## 📂 Project Structure

```text
LMS-PowerBI-Project/
│
├── README.md
│
├── LmsPowerBi.pbix
│
├── Dataset/
│   └── LMS_Dataset.xlsx
│
├── Screenshots/
│   ├── Dashboard.png
│   ├── Learner_Analysis.png
│   ├── Course_Analysis.png
│   └── Performance_Analysis.png
│
└── Documentation/
    └── Project_Findings.pdf
```

> File names can be changed according to the actual files uploaded to this repository.

---

## 📊 Dashboard Features

The Power BI report contains interactive pages designed to analyze different aspects of the LMS.

### 1. 📈 Overview Dashboard

Provides a high-level summary of the LMS using KPI cards and visualizations.

Key metrics may include:

* Total Learners
* Total Courses
* Total Enrollments
* Course Completion
* Average Performance
* Active Learners
* Completion Rate

---

### 2. 👨‍🎓 Learner Analysis

Analyzes learner-related information and behavior.

The analysis includes:

* Learner participation
* Learner performance
* Completion behavior
* Engagement trends
* Learner-level KPIs

---

### 3. 📚 Course Analysis

Analyzes course-level performance and activity.

The dashboard can be used to identify:

* Popular courses
* Course enrollment trends
* Course completion
* Course performance
* Courses requiring additional attention

---

### 4. 📊 Performance Analysis

Analyzes learner/course performance using interactive Power BI visuals.

Possible analysis includes:

* Performance distribution
* Average scores
* Completion vs performance
* Performance by course
* Performance trends

---

## 🔄 Data Preparation

The dataset was processed using **Power Query** before creating the dashboard.

The major data preparation steps included:

1. Importing the raw dataset.
2. Checking column names and data types.
3. Handling missing values.
4. Removing duplicate records where required.
5. Cleaning inconsistent values.
6. Transforming columns.
7. Creating calculated fields where required.
8. Loading the cleaned data into Power BI.

---

## 🧮 DAX

DAX (Data Analysis Expressions) was used to create calculated measures and KPIs.

Example:

```DAX
Total Learners = DISTINCTCOUNT(LMS[User_ID])
```

Example:

```DAX
Total Enrollments = COUNTROWS(LMS)
```

Example:

```DAX
Average Score = AVERAGE(LMS[Score])
```

Example:

```DAX
Completion Rate =
DIVIDE(
    [Completed Learners],
    [Total Learners],
    0
)
```

> The exact DAX measures should be updated according to the column names used in the final dataset.

---

## 🎨 Power BI Visualizations

The project uses different Power BI visuals, such as:

* KPI Cards
* Bar Charts
* Column Charts
* Line Charts
* Donut Charts
* Tables
* Matrix
* Slicers
* Filters

These visuals allow users to interactively explore the LMS data.

---

## 🔍 Key Insights

The dashboard helps identify:

* Overall LMS performance.
* Learner engagement patterns.
* Course enrollment trends.
* Course completion patterns.
* High- and low-performing courses.
* Learner performance differences.
* Areas where learning programs may require improvement.

The exact findings are documented within the Power BI report and project documentation.

---

## 🎛️ Interactive Features

The dashboard includes interactive functionality such as:

* Slicers
* Cross-filtering
* Drill-down
* Visual interactions
* Dynamic KPI calculations
* Page navigation

Users can filter the dashboard to analyze specific learners, courses, categories, or other available dimensions.

---

## 📸 Dashboard Preview

Add screenshots of your Power BI dashboard here.

```text
Screenshots/
│
├── Dashboard.png
├── Learner_Analysis.png
├── Course_Analysis.png
└── Performance_Analysis.png
```

Example:

```markdown
![LMS Dashboard](Screenshots/Dashboard.png)
```

---

## 💡 Business Value

This dashboard demonstrates how raw LMS data can be converted into meaningful business insights.

Organizations can use similar dashboards to:

* Monitor learning performance.
* Understand learner engagement.
* Track course effectiveness.
* Identify performance gaps.
* Support training-related decisions.
* Improve learning program management.

---

## 🚀 Skills Demonstrated

This project demonstrates practical knowledge of:

* Power BI
* Power Query
* DAX
* Data Cleaning
* Data Transformation
* Data Modeling
* Data Visualization
* KPI Development
* Business Intelligence
* Exploratory Data Analysis
* Dashboard Design
* Analytical Thinking

---

## 👨‍💻 Author

**Raushankant Verma**

Aspiring Data Analyst

### Skills

* Excel
* SQL
* Power BI
* Python
* Data Analysis
* Data Visualization

---

## 📜 License

This project is created for **educational, portfolio, and demonstration purposes**.

If the dataset belongs to a third party, all rights related to the original dataset remain with its respective owner.
