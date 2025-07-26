🌍 **Global AI Job Market & Salary Trends Dashboard (2025)**

This project explores global AI job listings from over 50 countries to extract actionable insights on salary trends, job roles, required skills, and remote work opportunities using Power BI. The dataset was sourced from Kaggle and cleaned, transformed, and visualized to help understand hiring dynamics and in-demand roles in the global AI industry.

📁 **Dataset Overview**

**Source:** [Kaggle Dataset - Global AI Job Market & Salary Trends 2025]

**Size:** 15,000+ job listings

**Fields Included:**

Job Title

Company Location

Employment Type

Experience Level

Remote Ratio

Salary (in various currencies)

Required Skills

Application Deadline & Posting Date

Company Size

🧹** Data Cleaning & Transformation**

We used Power Query Editor and Python (basic steps) to clean and structure the data for analysis:

✅ Skill Extraction: Split required_skills into individual rows to analyze frequency.

✅ Salary Normalization: Converted salaries to PKR (Pakistani Rupee) based on the salary_currency column using fixed exchange rates.

✅ Time Calculations: Derived days_remaining by subtracting posting_date from application_deadline.

✅ Data Type Fixes: Reformatted columns to proper data types for Power BI compatibility.

📊 **Power BI Dashboard Features**

We built a multi-page Power BI dashboard to visualize key findings:

✨ **Dashboard Highlights**:

📌 **Most In-Demand Job Roles by Country**

NLP Engineer was the top-listed AI job in multiple countries.

🧠** Most Commonly Required Skill**

Python ranked as the most demanded programming language in AI job listings globally.

💼 **Application Duration Trends**

On average, jobs remained open for 15–20 days, providing a 2–3 week application window.

💰 **Country-Wise Highest Salary Roles**

Canada: Computer Vision Engineer

Austria: MLOps Engineer

Denmark: AI Software Engineer

🌐 **Remote Work Insights**

“AI Software Engineer” had the highest number of fully remote jobs, showing a global shift towards hybrid and flexible work environments.

📈 **Skills Gained**

Data Cleaning & Transformation (Power Query, Excel)

Power BI Dashboard Development

Data Normalization (Currency Conversion)

Time-Series Analysis

Insight Generation & Storytelling with Data
