# 📊 Data-Analysis-Portfolio
Welcome to my GitHub portfolio! This repository showcases my projects and contributions to the open source community.
## About Me
I am a dedicated and detail-oriented data analyst with a passion for transforming raw data into meaningful insights. With a solid foundation in data scraping, analysis, visualization, and cleaning, I specialize in extracting valuable information from diverse datasets. My analytical skills, combined with proficiency in SQL, Python, Tableau, Excel, and Power BI, empower me to uncover patterns, trends, and actionable insights that drive informed decision-making. I have successfully applied my skills in various projects. This experience has honed my ability to tackle complex analytical challenges and deliver valuable results. In the dynamic field of data analysis, I am committed to staying updated with the latest technologies and methodologies. I actively seek opportunities for professional development to enhance my skill set and contribute effectively to data-driven decision-making.
## Skills
### Data Analysis

- 📉 Exploratory Data Analysis

- 📊 Data Visualization

- 🧹 Data Cleaning

- 🕸️ Data Scraping


### Programming

- 🐍 Python

- 🐘 SQ
L
### Tools

1.Tableau: I use Tableau to create interactive and visually appealing data visualizations that facilitate understanding and decision-making.

2.Excel: Excel is one of my go-to tools for data analysis, manipulation, and reporting. I am proficient in using advanced Excel functions and features.

3.Power BI: I leverage Power BI to create dynamic reports and dashboards, providing stakeholders with clear and actionable insights.

## 🚀 Projects

### 1. Title: Covid-19 Data Exploration and Analysis:[HERE](https://github.com/BovasTheAnalyst/Data-Analysis-Portfolio/blob/a4abc0f194a8d53a7438322ea711a68c3a236706/COVID%20Portfolio%20Project%20-%20Data%20Exploration.sql)

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

### 2. Title: Data Cleaning in SQL Queries :[HERE](https://github.com/BovasTheAnalyst/Data-Analysis-Portfolio/blob/54146ac2e692467d8320917d26bfd32bbbef00f5/Data%20Cleaning%20Portfolio%20Project%20Queries.sql)

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

### 3. Title: Automating Crypto Website API Pull Using Python: [HERE](https://github.com/BovasTheAnalyst/Data-Analysis-Portfolio/blob/65b615869efeadd7b18648cc6f2c70668c577118/Automate%20API%20Extraction%20%2B%20Appending%20Data%20%2B%20Extra%20--%20Project.ipynb)

This project involves using the CoinMarketCap API to retrieve cryptocurrency data, process it, and visualize trends over time. Here's a brief summary of the project:

1. **API Integration:**
   - The project starts by making requests to the CoinMarketCap API to retrieve the latest cryptocurrency listings.
   - The requests are made in a loop to collect data at regular intervals.

2. **Data Processing:**
   - The retrieved data is normalized and converted into a Pandas DataFrame for easy analysis.
   - The DataFrame is continuously updated with new data in each iteration of the API calls.

3. **Data Visualization:**
   - The project utilizes Seaborn and Matplotlib for data visualization.
   - It creates a line plot showing the price trends of a specific cryptocurrency (Bitcoin in this case) over time.

4. **Additional Analysis:**
   - The project calculates and visualizes the mean percentage changes in cryptocurrency prices over different time intervals (1 hour, 24 hours, 7 days, 30 days, 60 days, and 90 days).
   - The data is reshaped and transformed to facilitate the creation of a categorical plot showing these percentage changes.

5. **Data Storage:**
   - The project demonstrates how to store the collected data in a CSV file for future reference.
   - It includes code snippets for both creating a new CSV file and appending data to an existing one.

6. **Enhancements:**
   - There are code snippets for setting display options, such as showing all columns in the Pandas DataFrame and controlling the display format of floating-point numbers.

7. **Automation:**
   - The API calls are automated to run in a loop at regular intervals (every minute in this case).
   - The project provides an example of how to stop the loop after a specific number of iterations.

8. **Note:**
   - There's a note about addressing potential issues with data retrieval and the use of the Anaconda Prompt command to adjust data rate limits.

Overall, the project provides a comprehensive example of working with cryptocurrency data through an API, performing data analysis and visualization, and implementing automation for continuous data collection.

### 4. Title: Power BI Dashboard Project: Data Professional Survey Breakdown: [HERE](https://www.novypro.com/project/data-professionals-survey-breakdown-dashboard)

Welcome to the "Data Professional Survey Breakdown" Power BI dashboard project! This interactive dashboard provides a comprehensive overview of data professionals from various countries, offering insightful breakdowns and visualizations. Here's a brief description of the project:

## Project Overview:

This Power BI dashboard is the result of a detailed survey conducted among data professionals worldwide. The goal was to collect and analyze data related to the demographics, skills, and preferences of individuals working in the field of data.

## Key Features:

### -> Geographic Distribution:

Explore an intuitive map representation showcasing the distribution of data professionals across different countries. The map provides a quick and visually appealing overview of the global presence of data experts.

### -> Demographic Insights:

Dive into demographic details such as age, gender, and education level of data professionals. Interactive charts and graphs break down these demographics, allowing for a nuanced understanding of the diverse workforce in the data industry.

### -> Skills and Expertise:

Gain insights into the varied skill sets possessed by data professionals. The dashboard highlights the most in-demand skills and technologies, providing valuable information for both professionals and employers in the data field.

### -> Data Cleaning Process:

Data integrity is crucial, and this project emphasizes it by showcasing the use of Power Query for data cleaning. The Power Query tool efficiently handles data cleaning tasks, ensuring the accuracy and reliability of the survey results.

### -> Dynamic Filtering:

Interact with the data dynamically through filters, enabling users to tailor their exploration based on specific criteria. Whether focusing on a particular country, skill set, or demographic, users have the flexibility to extract the most relevant insights.

This Power BI dashboard serves as a valuable resource for anyone interested in understanding the landscape of data professionals, from their geographical distribution to the skills that drive the industry forward. Explore the data, uncover trends, and gain a deeper appreciation for the diverse and dynamic world of data professionals!