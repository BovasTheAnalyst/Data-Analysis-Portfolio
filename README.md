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

- 🐘 SQL

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

### 3. BRITISH AIRWAYS Data Science Project [HERE](https://github.com/BovasTheAnalyst/Data-Analysis-Portfolio/commit/5261e07c719b2c8f4f07813b1eaf2ca0a60d9d6e#diff-97436da600ac1f5185124da4e91cf86f7d500da6875d06766ec17d00cfbb766e)

This project involves scraping and analyzing review data of British Airways. Here's a brief summary of the project:

- Utilized Python and various libraries such as Pandas, NumPy, and Scikit-learn within Jupyter Notebook for data analysis and model development.
- Conducted exploratory data analysis (EDA) to identify patterns, trends, and correlations within the customer dataset.
- Preprocessed data by handling missing values, outliers, and feature engineering to enhance model performance.
- Employed machine learning algorithms including regression, classification, and ensemble methods to build predictive models.
- Evaluated model performance using appropriate metrics such as accuracy, precision, recall, and F1-score.
- Implemented cross-validation techniques to ensure model generalization and prevent overfitting.
- Interpreted model results to extract actionable insights into customer behavior and purchasing decisions.
- Created visualizations using libraries like Matplotlib and Seaborn to effectively communicate findings.
- Developed a presentation in PowerPoint to convey project objectives, methodology, findings, and recommendations to stakeholders.
- Practiced effective communication skills by presenting insights in a clear and concise manner, tailored to the audience's level of understanding and interest.



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

##  Certifications

### -> Accenture North America Data Analytics and Visualization Job Simulation on Forage - January 2024: [HERE](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/Accenture%20North%20America/hzmoNKtzvAzXsEqx8_Accenture%20North%20America_HKAadNakNpdcWwiaz_1705042852427_completion_certificate.pdf)

- Advised a hypothetical social media client through a comprehensive simulation as a Data Analyst.
- Cleaned, modeled, and analyzed 7 datasets in Excel to uncover content trends, presenting key insights
  through a PowerPoint deck and video to inform strategic decisions for both the client and internal
  stakeholders.

### -> PwC Switzerland Power BI Job Simulation on Forage - January 2024: [HERE](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/PwC%20Switzerland/a87GpgE6tiku7q3gu_PwC%20Switzerland_HKAadNakNpdcWwiaz_1705657040919_completion_certificate.pdf)

- Advanced skills in creating impactful Power BI dashboards, honed through job simulation and client
  interaction.
- Strong communication skills showcased in providing concise insights and suggestions through emails.
- Applied analytical problem-solving to HR data, uncovering root causes for executive-level gender balance
  issues.

### -> British Airways's Data Science job simulation on Forage - February 2024: [HERE](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/British%20Airways/NjynCWzGSaWXQCxSX_British%20Airways_HKAadNakNpdcWwiaz_1707845992977_completion_certificate.pdf)

- Completed a simulation focussing on how data science is a critical component
  of British Airways success.
- Scraped and analysed customer review data to uncover findings.
- Built a predictive model to understand factors that influence buying
  behaviour.


