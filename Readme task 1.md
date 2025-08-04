📄 README: Data Cleaning Task – Sales Data
👤 Submitted by:
Praveen Kumar R
Intern – Data Analyst
Date: 2025-08-04

📌 Project Title:
Sales Data Cleaning and Formatting – Excel Export

📁 Description:
This task involved importing a raw sales dataset (in CSV format), identifying formatting issues (such as all values being in a single column), and exporting the cleaned data into a properly formatted Excel (.xlsx) file.

🧹 Tasks Performed:
Loaded Raw CSV File
File contained comma-separated values but was incorrectly structured when opened in Excel due to format confusion.
Used pandas.read_csv() to properly interpret the file.
Cleaned the Dataset
Removed unnecessary Unnamed columns.
Checked for and handled formatting issues like improper column separation.
Exported to Excel Format
Installed and used openpyxl to export the DataFrame.
Saved the final clean dataset using df.to_excel() with proper formatting and without index.

🛠️ Tools Used:
Python (Jupyter Notebook)
Pandas
openpyxl
Excel

🗂️ Output:
✅ Cleaned Excel file: cleaned_file.xlsx
✅ All columns properly split and ready for analysis

📎 Notes:
The original issue occurred because the CSV file was incorrectly opened directly in Excel, which interpreted the entire row as one string.
This was fixed by reading and exporting using appropriate pandas and Excel tools.