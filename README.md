# College-Library-Late-Fee-Collection-Analysis-dataset

##  Project Overview

This project analyzes **college library late fee data** using Python.  
The goal is to understand how late book returns affect the **fine amount** and how fines vary across **different departments**.
The project uses **data analysis and visualization** to find useful insights.

## Objectives

*Analyze late book return days
*Study fine amount charged to students
* Compare fine data across departments
*Visualize patterns using graphs
* Understand relationship between late days and fine amount

## Dataset Information
The dataset is a CSV file with **1000 records**.

### Columns in the dataset:
* Student_ID – Unique ID of student
* Book_ID – Book identification number
* Department – Student department (CE, CSE, IT, etc.)
* Issue_Date – Date when book was issued
* Due_Date – Last return date
* Return_Date – Actual return date
* Late_Days – Number of days book was returned late
* Fine_Amount – Fine charged in rupees

##  Tools & Libraries Used

 **Python**
 **NumPy** – Numerical calculations
 **Pandas** – Data handling and analysis
 **Matplotlib** – Data visualization
 **Seaborn** – Statistical plots

##  Data Cleaning
Before analysis, the dataset was checked:

* No missing values
* No duplicate records
* Correct data types
* Only required columns were selected for analysis
The data is "clean and ready" for analysis.

### Exploratory Data Analysis (EDA)
## Statistical Summary:
* Average Late Days= 12 days
* Average Fine Amount= ₹60
* Maximum Fine= ₹120
* Minimum Fine=₹0
This shows that higher late days result in higher fines.

### Department-wise Analysis
*Fine records were counted for each department
*Some departments have more late return cases than others
This helps library management identify problem areas.

## Data Visualization
The following plots were created
**Histogram of Departments**  
  Shows distribution of students across departments

 **Histogram of Late Days**  
  Shows how late students return books

**Boxplot (Department vs Fine Amount)**  
  Compares fine amount across departments  
  Shows minimum, maximum, median, and outliers
Graphs make the data easy to understand.


## Key Findings

*Late days and fine amount are directly related
*Some departments show higher fine cases
* Fine system works in a structured manner
* Visualization helps in better decision making

##  Conclusion

This project shows how Python can be used for
*Real-world data analysis
* Understanding patterns in data
* Supporting decision-making using visuals

Library authorities can use this analysis to
*Improve fine policies
* Reduce late book returns

## Future Scope

* Predict fine amount using Machine Learning
* Create an interactive dashboard
* Analyze student reading behavior

##  How to Run the Project

1. Clone the repository
2. Install required libraries
3. Run the Python script
4. Make sure the CSV file is in the same folder

##  Author

**Ankit Raj**  
Computer Science Student  
Data Analysis Project

---

⭐ If you like this project, feel free to star the repository!
