# Data-Analysis-Portfolio
Welcome to my GitHub portfolio! This repository showcases my projects and contributions to the open source community.
## About Me
I am a dedicated and detail-oriented data analyst with a passion for transforming raw data into meaningful insights. With a solid foundation in data scraping, analysis, visualization, and cleaning, I specialize in extracting valuable information from diverse datasets. My analytical skills, combined with proficiency in SQL, Python, Tableau, Excel, and Power BI, empower me to uncover patterns, trends, and actionable insights that drive informed decision-making. I have successfully applied my skills in various projects. This experience has honed my ability to tackle complex analytical challenges and deliver valuable results. In the dynamic field of data analysis, I am committed to staying updated with the latest technologies and methodologies. I actively seek opportunities for professional development to enhance my skill set and contribute effectively to data-driven decision-making.
### Skills
-Data Analysis and Visualization

-Data Cleaning

-Data Scraping

-SQL and Python
### Tools
1.Tableau: I use Tableau to create interactive and visually appealing data visualizations that facilitate understanding and decision-making.

2.Excel: Excel is one of my go-to tools for data analysis, manipulation, and reporting. I am proficient in using advanced Excel functions and features.

3.Power BI: I leverage Power BI to create dynamic reports and dashboards, providing stakeholders with clear and actionable insights.

## Projects
### Data exploration using SQL : [HERE](https://github.com/BovasTheAnalyst/Data-Analysis-Portfolio/blob/a4abc0f194a8d53a7438322ea711a68c3a236706/COVID%20Portfolio%20Project%20-%20Data%20Exploration.sql)
Title: Covid-19 Data Exploration and Analysis

**Overview:**
This data exploration project focuses on analyzing Covid-19 data using various SQL skills such as joins, common table expressions (CTEs), temp tables, window functions, and aggregate functions. The analysis encompasses different aspects, including infection rates, death rates, vaccination progress, and comparisons between countries and continents.

**Skills Demonstrated:**
- Joins, CTEs, temp tables, window functions, and aggregate functions
- Creating views
- Converting data types
- Analyzing and interpreting Covid-19 data
- Developing insights into infection rates, death rates, and vaccination progress

**Conclusion:**
This project showcases a comprehensive analysis of Covid-19 data, providing valuable insights into the impact of the pandemic on different countries and continents. The use of SQL skills demonstrates a proficiency in handling and interpreting large datasets for meaningful conclusions.

**Title:** Data Cleaning in SQL Queries: [HERE](https://github.com/BovasTheAnalyst/Data-Analysis-Portfolio/blob/dc6abe45f739d77d2b65459382337a20695d6df9/Data%20Cleaning%20Portfolio%20Project%20Queries.sql)

**Overview:**
This SQL data cleaning project focuses on preparing and refining data from the "NashvilleHousing" table within the "PortfolioProject" database. The cleaning process involves standardizing date formats, populating missing property addresses, breaking down address fields, converting 'Y' and 'N' to 'Yes' and 'No' in the "SoldAsVacant" field, removing duplicates, and finally, deleting unused columns.

**Key Steps:**

1. **Standardize Date Format:**
   - Converts the "SaleDate" column to a standardized date format.
   - Handles cases where the update might not work by creating a new column ("SaleDateConverted") and updating it.

2. **Populate Property Address Data:**
   - Identifies records with missing property addresses.
   - Populates missing property addresses by joining the table with itself based on "ParcelID" and updating the null values.

3. **Breaking Out Address into Individual Columns:**
   - Splits the "PropertyAddress" column into separate columns for address and city, enhancing data organization.

4. **Breaking Out Owner Address:**
   - Utilizes the PARSENAME function to split the "OwnerAddress" into separate columns for address, city, and state.

5. **Change 'Y' and 'N' to 'Yes' and 'No':**
   - Converts values in the "SoldAsVacant" field to 'Yes' and 'No' for better clarity and consistency.

6. **Remove Duplicates:**
   - Identifies and keeps only unique records based on specified criteria using the ROW_NUMBER() window function.

7. **Delete Unused Columns:**
   - Removes unnecessary columns like "OwnerAddress," "TaxDistrict," "PropertyAddress," "SaleDate" to streamline the dataset.

8. **Importing Data Using OPENROWSET and BULK INSERT (Optional):**
   - Provides an alternative approach for importing data using OPENROWSET and BULK INSERT, which can be more advanced and visually appealing.

**Conclusion:**
This data cleaning project demonstrates a thorough process of standardizing, populating, and restructuring data to enhance its quality and usability. The SQL queries cover a range of cleaning tasks, showcasing skills in data manipulation and transformation.

