Audible Data Cleaning Project Overview
This project involved the process of cleaning and standardizing an Audible dataset using Power Query Editor in Excel. The goal was to ensure data consistency and improve the dataset's structure for more effective analysis. Various techniques were applied to clean and transform the dataset, making it ready for further insights.

Dataset Link:
Audible Dataset

Data Cleaning Tasks and Applied Steps
Standardizing Product Titles

Action Taken: Capitalized each word in the "Name" column.
Reasoning: Uniform title formatting improves readability and ensures consistency across the dataset.
Separating Author Names

Action Taken: Split the "Author" column into separate fields for first and last names using delimiters.
Reasoning: This separation helps organize the data better, making it easier to analyze author-specific details.
Consistent Date Format for Release Dates

Action Taken: Converted the "ReleaseDate" column to the DD-MM-YYYY format.
Reasoning: A consistent date format ensures that temporal analysis can be performed accurately and uniformly.
Converting Duration to Minutes

Action Taken: Extracted hours from the "Time" column and multiplied by 60 to convert it into minutes.
Reasoning: Standardizing the time format allows for better manipulation and analysis of durations in Excel.
Price Data Cleanup

Action Taken: Replaced non-numeric values (e.g., "Free") with "0" and converted the column data type to currency format.
Reasoning: Ensures that the price column is numeric and correctly formatted, which is essential for financial analysis.
Converting Star Ratings to Numeric

Action Taken: Replaced text-based star ratings with numeric values.
Reasoning: Numerical ratings are easier to analyze and compare.
Handling Multiple Narrators

Action Taken: Split the "NarratedBy" column to separate individual narrators when multiple names were listed.
Reasoning: This makes it easier to identify and analyze narrators individually rather than as a single group.
Combining Release Info

Action Taken: Merged the "ReleaseDate" and "Language" columns into a new "ReleaseInfo" column with the format "DD-MM-YYYY, Language."
Reasoning: Combining these two pieces of information into a single column simplifies analysis and provides a complete overview in one field.
Filling Null Values

Action Taken: Replaced null values with appropriate placeholders, such as "Not Available" or "0."
Reasoning: This step ensures that there are no empty cells, improving the dataset's integrity.
Key Excel Features Utilized
Power Query Editor: Crucial for data transformations, such as splitting columns, merging data, and changing formats.
Text to Columns: Used to separate combined names or multiple narrators into individual cells.
Data Type Conversion: Ensured the correct data type was applied (numeric, date, etc.) for consistent analysis.
Merge Columns: Combined related data (e.g., release date and language) into one column for simplicity.
Conditional Formatting: Applied to ensure consistency and identify any anomalies or inconsistencies visually.
Project Conclusion
The Audible dataset was successfully cleaned and standardized through a series of structured transformations. Power Query Editor played a key role in this process, enabling efficient data manipulation. With the dataset now organized and formatted consistently, it is ready for deeper analysis, providing more meaningful insights.
