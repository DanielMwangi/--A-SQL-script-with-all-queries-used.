international_debt_with_missing_values
Connect to the PostgreSQL database using the provided connection string and explore the dataset.
 
1). Write SQL queries to find answers to the following key questions:
 
1- What is the total amount of debt owed by all countries in the dataset?
SELECT SUM(debt) AS total_debt
FROM international_debt_with_missing_values_csv;

2- How many distinct countries are recorded in the dataset?
 SELECT COUNT(DISTINCT country_name) AS total_countries
FROM international_debt_with_missing_values_csv;

3- What are the distinct types of debt indicators, and what do they represent?
 
   SELECT DISTINCT indicator_code, indicator_name
FROM international_debt_with_missing_values_csv;


4- Which country has the highest total debt, and how much does it owe?
 SELECT indicator_name, AVG(debt) AS avg_debt
FROM international_debt_with_missing_values_csv
GROUP BY indicator_name
ORDER BY avg_debt DESC;


5- What is the average debt across different debt indicators?
 
SELECT indicator_name, AVG(debt) AS avg_debt
FROM international_debt_with_missing_values_csv
GROUP BY indicator_name
ORDER BY avg_debt DESC;
6- Which country has made the highest amount of principal repayments?


7- What is the most common debt indicator across all countries?
SELECT indicator_name, COUNT(*) AS COUNT
FROM international_debt_with_missing_values_csv
GROUP BY indicator_name
ORDER BY COUNT DESC
LIMIT 1;


8- Identify any other key debt trends and summarize your findings.
 FROM international
- Document your process: Clearly explain the steps you followed, your query logic, and insights from your findings.
 
2). Final Deliverable: A GitHub repository containing:
		- A SQL script with all queries used.
 - A report (Markdown) summarizing findings with supporting data.
