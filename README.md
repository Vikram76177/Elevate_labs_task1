🧹 Data Cleaning & Preprocessing - Task 1
📌 Internship: Data Analyst

Task: Data Cleaning and Preprocessing
Dataset: Marketing Campaign Dataset
Tool Used: Microsoft Excel (Primary)

🎯 Objective

The purpose of this task was to clean and prepare a raw dataset containing null values, duplicates, and inconsistent formats so that it becomes ready for accurate analysis and visualization.

📂 Files in This Repository

marketing_campaign_raw_dataset.csv → Original raw dataset (unchanged)

marketing_campaign_cleaned_dataset.xlsx → Main working file with table format & correct data types

marketing_campaign_cleaned_dataset.csv → Final cleaned dataset for submission

Short Summary of Changes.docx → Concise report summarizing all cleaning actions and final outcomes


🔧 Cleaning Steps Performed
1. Column Standardization

Renamed all column headers to:

lowercase

no spaces

underscore-separated format

2. Handling Missing Values

Numeric columns: Filled missing values using Median

Text columns: Replaced missing values with "Unknown"

This ensured no blank values remained in critical fields.

3. Removing Duplicates

Used Excel's Remove Duplicates feature across all columns

Ensured each row represents a unique record

4. Fixing Data Types

Converted incorrect data types:

Text numbers ➝ Numeric

Text dates ➝ Proper Date format

Ensured consistency for columns like:

income

year_birth

date fields

5. Text Standardization

Removed extra spaces using TRIM

Standardized case formatting

Ensured uniform categorical values

6. Table Formatting

Converted dataset into Excel Table format for better data handling and filtering

Maintained structured layout in .xlsx version

✅ Final Results
Criteria	Status
Null values removed	✅
Duplicates removed	✅
Column names cleaned	✅
Data types standardized	✅
Dataset ready for analysis	✅

Final dataset is now consistent, structured, and analysis-ready.

📊 Tools & Techniques Used

Microsoft Excel

TRIM, MEDIAN, VALUE, IF formulas

Remove Duplicates

Data Type Conversion

Table Formatting

📎 How to Reproduce

Open marketing_campaign_raw_dataset.csv

Apply cleaning steps described above

Save as Excel format for working

Export final output as CSV

👤 Author

Vikram Singh Bisht
Data Analyst Intern


🔗 GitHub Repository created as per task submission guidelines.
