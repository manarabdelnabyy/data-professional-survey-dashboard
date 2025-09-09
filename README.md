# data-professional-survey-dashboard
Interactive Power BI dashboard analyzing global data professional survey responses, including demographics, salaries, job satisfaction, and programming language preferences.
# 📊 Data Professional Survey Dashboard  

This repository contains a **Power BI dashboard** analyzing survey responses from data professionals worldwide. The goal of this project is to uncover insights into **demographics, career paths, salaries, job satisfaction, and programming language preferences** of people working in the data industry.  

---

## 🔍 Project Overview  

The dashboard provides:  
- 🌍 **Demographics** – country distribution of survey takers.  
- 💰 **Average Salary by Job Title** – comparison across different roles (Data Analyst, Data Scientist, Data Engineer, etc.).  
- 💻 **Favorite Programming Languages** – breakdown of popular tools like Python, R, SQL, etc.  
- 🚪 **Difficulty Entering the Field** – how easy/difficult professionals found it to break into data.  
- ⚖️ **Work-Life Balance & Salary Satisfaction** – survey averages on job happiness.  

---

## 📂 Repository Contents  

-  
- `survey_data.csv` → dataset used (or placeholder/sample if dataset is private).  
- `images/dashboard_preview.png` → dashboard preview screenshot.  


---

## 🛠️ Tools & Technologies  

- **Power BI Desktop** – for dashboard development.  
- **Power Query** – for data cleaning and transformation.  
- **Data Visualization** – KPIs, treemaps, bar charts, and gauges to highlight insights.  
- **Dax Calculations** :
 -- Average Age of Survey Takers
Average Age = AVERAGE(Survey[Age])

-- Count of Survey Takers
Count of Survey Takers = COUNTROWS(Survey)

-- Happiness with Work-Life Balance
Avg Work Life Balance = AVERAGE(Survey[Work_Life_Balance])

-- Happiness with Salary
Avg Salary Happiness = AVERAGE(Survey[Salary_Happiness])

-- Average Salary by Job Title
Avg Salary = AVERAGE(Survey[Salary])

-- Favorite Programming Language Count
Language Count = COUNTROWS(Survey)

---

## 🚀 Key Insights  

- Majority of survey takers are from the **United States, India, and the United Kingdom**.  
- **Data Analysts** dominate the salary reporting in this dataset.  
- **Python** is the most popular programming language among professionals.  
- Average age of survey takers is **29.8 years old**.  
- Many found it **moderately difficult** to enter the data field.  
- **Happiness with work-life balance (5.33/10)** is higher than **happiness with salary (4.27/10)**.  

---

## 📌 How to Use  

1. Clone this repository.  
2. Open `Data_Professional_Survey.pbix` in **Power BI Desktop**.  
3. Load the dataset (if not already connected).  
4. Explore the interactive dashboard.  

---

## 🎯 Purpose  

This project demonstrates skills in:  
- Data visualization with **Power BI**.  
- Designing **interactive dashboards**.  
- Communicating insights effectively with data.  

---  

✨ If you like this project, feel free to **star ⭐ the repository** and connect with me!  
