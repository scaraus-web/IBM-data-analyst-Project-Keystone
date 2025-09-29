# IBM Data Analyst Capstone Project: Developer Technology Preferences & Usage

**Tools:** Python (pandas) • Jupyter Notebooks • Google Looker Studio  
**Live Dashboards:**  
- [Programming Languages](https://lookerstudio.google.com/reporting/83281144-61b5-49b0-8a9b-e97c872bf3cb/page/p_0c7q2qnptd)  
- [Databases](https://lookerstudio.google.com/reporting/83281144-61b5-49b0-8a9b-e97c872bf3cb/page/p_lrxuxtamtd)  
- [Platforms & Frameworks](https://lookerstudio.google.com/reporting/83281144-61b5-49b0-8a9b-e97c872bf3cb/page/p_z8kakffntd)  

---

## Problem Statement
The global developer ecosystem evolves rapidly, with programming languages, databases, and platforms constantly shifting in popularity.  
This project answers:  
- Which technologies dominate current usage?  
- What do developers *want* to learn next?  
- How do preferences differ by age, location, and education?  
- What strategic skills and tools will stay relevant in the future?

---

## Methods

### 1. Data Preparation
- Removed missing values and duplicates.  
- Transformed comma-separated survey responses into unique values per column.  
- Cleaned dataset saved to [`data/df_cleanLAB26.csv`](./data/df_cleanLAB26.csv).  

### 2. Analysis & Visualization
- **Python (pandas):** Cleaning and preparation → [Jupyter Notebook](./notebook/Cleaning_survey_data_for_Keystone_project.ipynb)  
- **Google Looker Studio:** Interactive dashboards showing language, database, and platform trends.  
- **PDF Presentation:** [Developer Technology Preferences and Usage Patterns](./presentation/Developer%20Technology%20Preferences%20and%20Usage%20Patterns.pdf)


---

## Key Insights

- **Languages:**  
  - JavaScript dominates both current use and future preference.  
  - Rust and Go are rapidly rising in demand.  

- **Databases:**  
  - PostgreSQL is the clear leader, followed by MySQL and MongoDB.  
  - Redis and Supabase show strong growth potential.  

- **Platforms & Frameworks:**  
  - AWS, Azure, and Google Cloud remain dominant.  
  - Modern frameworks like Next.js, Vue.js, and FastAPI are gaining traction.  

- **Demographics:**  
  - Age 25–34 developers drive most trends.  
  - USA, India, Germany, UK lead global participation.  
  - 63% of respondents hold at least a Bachelor’s degree.  

---

## Repository Contents
- `data/` → Cleaned CSV file  
- `notebooks/` → Jupyter notebook for data wrangling  
- `presentation/` → PDF project presentation  
- `assets/` → Dashboard screenshots (optional for README preview)  

---

## Contact
**Author:** Serge Caraus  
- [GitHub](https://github.com/scaraus-web)  
- [LinkedIn](https://www.linkedin.com/in/serge-caraus-8922b177/)  

---

*This capstone project demonstrates end-to-end data analysis: data cleaning, visualization, and storytelling with actionable insights for developers, managers, and educators.*
