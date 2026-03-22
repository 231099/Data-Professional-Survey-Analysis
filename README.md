# Data Professional Survey Analysis (Power BI)

## Project Overview
This project analyzes survey data from over 600 individuals working in the data field. The goal was to understand salary trends, job satisfaction, and the popular programming languages used across different countries.

## Key Insights
* **Demographics:** Overview of age, education level, and ethnicity across the data landscape.
* **Salary vs. Role:** Breakdown of average salaries by job titles like Data Analyst, Scientist, and Engineer.
* **Happiness Levels:** Analysis of work-life balance and salary satisfaction.
* **Technical Preferences:** Python and R remain the dominant languages in the industry.

## Data Transformation (ETL)
The raw dataset required significant cleaning before visualization. 
* **Column Selection:** To maintain a focused and high-performing report, I excluded several unuseful columns (such as browser type, OS, and specific time stamps) that did not contribute to the core analysis.
* **Data Cleaning:** Handled "Other" categories in job titles and industries to ensure consistent grouping.
* **DAX Measures:** Created custom measures to calculate average happiness scores and salary ranges.

## Tools Used
* **Power BI Desktop:** For data modeling and visualization.
* **Power Query:** For data transformation and filtering.
* **Excel:** The source of the raw survey data.

## How to View
1. Download the `.pbix` file located in the `/Dashboard` folder.
2. Open with Power BI Desktop.
