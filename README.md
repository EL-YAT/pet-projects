**Key Indicators in Diabetes Diagnosis**

File: diabetes.ipynb

Language: EN 

Technology Stack: Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, SciPy), Jupyter Notebook

Results:

Conducted comprehensive data preparation (cleaning, normalization) and analysis. Trained a Random Forest ML model to determine the significance of predictors. Achieved an acceptable F1-score of 0.78, with insulin and glucose levels identified as the most important predictors. The main challenge was handling a large number of missing values (~50% of data in one column). The most effective solution involved using an auxiliary "SVC" model.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Sales Analytics**

File: Аналитика продаж.pbix

Language: RU

Technology Stack: DAX, Power BI

Results:
1. Calculated revenue, profit, profitability, ABC analysis, average check, and logistics costs using measures.
2. Visualized these metrics over time, by customer segment, and by product hierarchy with drill-downs from category to subcategory to product, as well as regional distribution on a map.
3. Conducted an ABC analysis of products based on revenue.
4. Analyzed the performance of managers, including the number of orders processed, profit, and losses.
5. Performed RFM and ABC analysis of the customer base.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Online School**

Language: EN

Technology Stack: Python (Pandas, NumPy, SQLAlchemy, Faker), PostgreSQL, Redash, Docker, DBeaver, Jupyter Notebook

Product Description:

An online learning platform designed for IT professionals seeking to enhance their skills at their convenience. Students can purchase courses, enroll in them, and complete their training on their own schedule. The platform offers personalized discounts on courses. A course is considered completed when a student finishes at least 80% of the material and can then leave a review. Instructors create and manage courses on the platform and receive 30% of the revenue, regardless of discounts offered.

Results:

1. A comprehensive data warehouse for the online school was designed and implemented. The database includes 8 tables: students, professors, orders, reviews, enrollments, courses, course_orders, and course_assignments. The data model is available in the file db_model.png, and the table definitions are located in the db folder. The tables for students and professors were populated using GPT-Chat and are presented in separate .sql files, while the remaining tables were generated based on these using a Python script (online-school-tables.ipynb).

2. Four analytical dashboards were developed, each providing valuable insights into different aspects of the platform:

- Students Summary: Provides a comprehensive demographic profile of the students. It helps visualize key user characteristics, such as age, gender, and geographical distribution, offering deep insights into the platform’s audience.

- Courses Summary: Offers a thorough overview of the courses. It includes course ratings based on various metrics, a funnel showing the percentage of students who enroll in a course after purchase and complete it, as well as an analysis of average course completion time and student progress levels.

- Financial Metrics Summary: Provides financial analysis, including RFM analysis of the customer base. It allows tracking of financial performance, assessing profitability and customer loyalty, and identifying trends and patterns in financial data.

- Course Purchase Trends and ABC Analysis: Analyzes course purchases, revealing key trends and student preferences. It includes ABC analysis to identify the most profitable and purchased courses, with breakdowns by categories, and cohort analysis of repeat purchases, tracking customer behavior across different cohorts and identifying recurring buying patterns.

How to Improve the Project:

1. Set up triggers for automatic validation of data integrity and correctness when data is entered into the tables. This will help prevent input errors, ensure compliance with business rules, and maintain high data quality.

2. Add a field to the courses table to store the ID of the professor currently responsible for supporting the course, along with a flag indicating whether the course is currently supported by an professor.

3. Analyze the performance of professor.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**Club Attendance Analysis**

File: анализ_посещаемости_кружка.pdf

Language: RU

Technology Stack: Looker Studio, BigQuery, Google Sheets
