# task-data-engineer

**Overview**
This project includes two assignments chosen from the provided list to showcase skills in data engineering, specifically ETL pipeline creation and data quality validation. The project uses open-source tools and libraries to meet the specified requirements.

**Data Set Link**

https://www.kaggle.com/datasets/dansbecker/melbourne-housing-snapshot


https://www.kaggle.com/competitions/titanic/data

**Assignments**
1. ETL Pipeline Using Open-Source Tools

**Objective: Build a simple ETL (Extract, Transform, Load) pipeline.**
Process:
  1.Extract: Data is sourced from a CSV file. The dataset used for this project is publicly available and specified in the documentation.
  
  2.Transform: The data undergoes specific transformations, including:
  
  3. Filtering rows based on defined conditions.
     
  4. Aggregating data (e.g., sum or average).
     
  5. Removing missing or invalid data.
     
  6. Load: The transformed data is loaded into a new CSV file or stored in a local SQLite database.
      
  7. SQL Implementation: SQL queries are provided to create the necessary tables in SQLite and load transformed data.

**Data Quality Assurance**

Objective: Ensure data quality through validation and data cleaning techniques.
Process:
  1. Implement checks for missing data, duplicates, and outliers.

  2.Define transformations to handle data inconsistencies.
  
  3.Generate a data quality report summarizing the dataset's state and the applied quality checks.

**Requirements**
The project is implemented using open-source libraries only, including:

Python for scripting.

Pandas for data manipulation.

SQLite for database operations.

Jupyter Notebooks for code and analysis.

**Project Structure**
ETL.ipynb: Jupyter notebook for the ETL pipeline assignment.

Data_quality.ipynb: Jupyter notebook for data quality validation and checks.

README.md: Documentation for understanding the project, requirements, and instructions.

**Instructions**
Clone the Repository:

bash
Copy code

git clone [<repository-url>](https://github.com/nishitha922/task-data-engineer.git)
Install Required Libraries:


Copy code
pip install -r requirements.txt
Ensure Python and the necessary libraries are installed as listed in the requirements.txt file.

**Run the Notebooks:**

Open and execute the notebooks in Jupyter or any compatible environment.
Follow the cell instructions for each assignment.
Assumptions
It’s assumed that all necessary packages are installed as listed in the requirements file.
Missing or invalid data in the source CSV is handled through specified transformation steps.

**Tools Used**

Python: Scripting language for the ETL and data quality processes.
Pandas: Data manipulation and transformation.
SQLite: For storing transformed data as part of the loading step.
Jupyter Notebook: For documenting code and running data analysis.

How to Run the Code
1. ETL Pipeline:
   
  Open ETL.ipynb.
  Follow the sections for Extract, Transform, and Load.
  Execute each cell in sequence to load, transform, and save data.
  
3. Data Quality Validation:

  Open Data_quality.ipynb.
  Run each cell to validate and clean the dataset.
  Review the generated data quality report for summary insights.
