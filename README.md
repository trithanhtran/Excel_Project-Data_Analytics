# My Excel Data Analytics Projects

## Excel Salary Dashboard
![Screenshot 2025-02-09 110906](https://github.com/user-attachments/assets/000137a7-3b98-46f2-978e-28648720c17b)  
### Introduction

This data jobs salary dashboard was created to help job seekers investigate salaries for their desired jobs and ensure they are being adequately compensated.

The data is from my Excel course, which provides a foundation in analyzing data using this powerful tool. The data contains detailed information on job titles, salaries, locations, and essential skills that are presented here.

### Dashboard File

My final dashboard is [here](Project_1%20Dashboard)

### Excel Skills Used
The following Excel skills were utilized for analysis:
- 📈 Charts
- 🧮 Formulas and Functions
- ❎ Data Validation

### Data Jobs Dataset

The dataset used for this project contains real-world data science jab information from 2023. The dataset includes detailed information on:

- 🙍‍♂️ **Job titles**  
- 💰 **Salaries**  
- 📍 **Locations**   
- 🛠️ **Skills**  

## Dashboard Build
### 📈 Charts
📊 Data Science Job Salaries - Bar Chart

![Screenshot 2025-02-09 124009](https://github.com/user-attachments/assets/be48a4c5-bac2-4518-a26f-81369bd84cf8)

- 🛠️ **Excel Features:** Ultilized bar chart feature (with formatted salary values) and optimized layout for clarity.  
- 🎨 **Design Choice:** Horizontal bar chart for visual comparison of median salaries.  
- 📈 **Data Organization:** Sorted job titles by descending salary for improved readability.  
- 💡 **Insights Gained:** This enables quick identification of salary trends, noting that Senior roles and Engineers are higher-paying than Analyst roles.

🗺️ **Country Median Salaries - Map Chart**

![Screenshot 2025-02-09 124726](https://github.com/user-attachments/assets/418705e2-b2c6-4361-a4b1-ef17b5349ad2)

- 🛠️  **Excel Features:** Utilized Excel's map chart feature to plot median salaries globally.  
- 🎨 **Design Choice:** Color coded map to visually differentiate salary levels across regions.  
- 📊 **Data Representation:** Plotted median salary for each country with avaliable data.  
- 👁️ **Visual Enhancement:** Improved readability and immediate understanding of geographic salary trends.    
- 💡 **Insights Gained:** Enables quick grasp of global salary disparities and highlights high/low salary regions.  

### 🧮 Formulas and Functions

💰 Median Salary by Job Titles

```
=MEDIAN(
IF(
    (jobs[job_title_short]=A2)*
    (jobs[job_country]=country)*
    (ISNUMBER(SEARCH(type,jobs[job_schedule_type])))*
    (jobs[salary_year_avg]<>0),
)
)
```
- 🔍 **Multi-Criteria Filtering:** Checks job title, country, schedule type, and excludes blank salaries.  
- 📊 **Array Formula:** Utilizes `Median()` function with nested `IF()` statement to analuze an array.  
- 🎯 **Tailored Insights:** Provides specific salary information for job titles, regions, and schedule types.  
- 🔢 **Formula Purpose:** This formula popylates the table below, returning the median salary based on job title, country, and type.

🍽️Background Table

![Screenshot 2025-02-09 130428](https://github.com/user-attachments/assets/2b059381-3dff-476b-9585-ffbe3a99eb59)

📈 Dashboard Implementation

![Screenshot 2025-02-09 130631](https://github.com/user-attachments/assets/be5e64ab-6b9a-4363-92bb-114de4925caf)

### ❎ Data Validation

🔍 **Filtered List**
- 🔒 **Enhanced Data Validation:** Implementing the filtered list as a data validation rule under the `Job Tile`, `Country`, and `Type` option in the Data tab ensures:  
  - 🎯 User input is restricted to predefined, validated schedule types
  - 🚫 Incorrect or inconsistent entries are prevented
  - 👥 Overall usability of the dashboard is enhanced

![Screenshot 2025-02-09 131507](https://github.com/user-attachments/assets/5e183e76-7326-48db-8215-0a1ea3ea5ae1)

## Conclusion
I created this dashboard to showcase insights into salary trends across various data-related job titles. Utilizing data from real-world, this dashboard allows users to make informed decisions about their career paths. Exploring the functionalities to understand how location and job type influence salaries.


## Salary Analysis
As a former job seeker, I've always been surprised by the lack of data exploring this most optimal jobs and skills in the data science market. I set out to understand what skills top employers request and how to land more pay.
[Checkout my work here](Project_2%20Analysis)

![Screenshot 2025-02-09 120247](https://github.com/user-attachments/assets/784b40dd-148f-4ab7-aeca-f0c70bbb60b8)

![Screenshot 2025-02-09 120232](https://github.com/user-attachments/assets/3838130f-0a3c-479f-b3dc-6dbf0dd70336)
