# **AtliQ Grands – End-to-End Hospitality Analytics (Power BI)**







### **Project Context**



This project is an end-to-end business intelligence case study developed to demonstrate applied data analytics skills relevant for postgraduate study in Data Science and Analytics.



The case is based on a simulated hospitality dataset representing AtliQ Grands, a luxury hotel chain operating across major Indian cities. The objective was to translate a real-world business problem into actionable insights using data modeling, analytics, and visualization.







### **Problem Statement**



AtliQ Grands experienced declining revenue and market share due to:



* Increasing competition
* Ineffective pricing and revenue management decisions
* Lack of in-house analytics capability



Management sought to incorporate Business Intelligence to improve pricing efficiency, reduce revenue leakage, and support strategic decision-making.







### **Analytical Objectives**



* Design a star-schema data model suitable for hospitality analytics
* Create dynamic KPIs using DAX
* Build an executive-level dashboard for decision support
* Independently explore business questions beyond base project requirements







### **Tools and Techniques**



* Power BI Desktop
* DAX (Data Analysis Expressions)
* Star Schema Data Modeling
* Interactive dashboards and report page tooltips
* Business-oriented data storytelling







### **Key Metrics Implemented**



* Revenue
* Occupancy Percentage
* ADR (Average Daily Rate)
* RevPAR (Revenue per Available Room)
* DSRN, DBRN, DURN
* Cancellation Percentage
* Realization Percentage
* Average Rating
* Week-on-week performance metrics



All metrics were implemented as dynamic DAX measures responsive to slicers and filters.







### **Dashboard Structure**



##### **Main Dashboard (Executive View)**



Designed for senior management to:



* Monitor overall business performance
* Track trends across key hospitality KPIs
* Review property-level performance
* Consume summarized business insights without technical complexity







##### **Independent Business Insights (Analytical View)**



An additional analytical page created beyond the guided tutorial scope to demonstrate independent reasoning and problem-solving.



Key analytical questions addressed include:



* **Pricing Efficiency by City**

Cities with similar occupancy levels exhibit significant variation in RevPAR, indicating pricing inefficiencies rather than demand constraints.



* **Revenue vs Cancellation Impact**

Higher cancellation rates are associated with lower revenue in certain cities, suggesting revenue leakage driven by booking volatility.



* **Weekend vs Weekday Performance**

Higher weekend RevPAR is driven primarily by increased utilization rather than ADR increases, highlighting opportunities for dynamic pricing optimization.



Each visual is paired with written insights emphasizing interpretation over reporting.







### **Advanced BI Features**



* Report page tooltips for weekly trends including Revenue, RevPAR, Occupancy, ADR, DSRN, and Realization
* Hidden tooltip pages to maintain professional report structure
* Consistent visual theme with restrained design choices
* Clear separation between reporting and analytical exploration







### **Academic and Professional Relevance**



This project demonstrates:



* Applied data analytics in a business context
* Ability to frame and answer analytical questions
* Proficiency in BI tools and data modeling
* Clear communication of insights for decision-makers



The project is intended as a portfolio artifact for MSc Data Science and Analytics admissions.







### **Repository Contents**



* Dashboard/ – Power BI (.pbix) file
* Data/ – Simulated hospitality dataset structured using a star schema:

  * dim\_date.csv
  * dim\_hotels.csv
  * dim\_rooms.csv
  * fact\_bookings.csv
  * fact\_aggregated\_bookings.csv

* Screenshots/ –
  * business_insights.png
  * main_dashboard.png
* README.md – Project documentation







### **Key Takeaways**



* Effective analytics begins with well-defined business questions
* Visualizations should support decision-making rather than decoration
* Communicating insights is as critical as computing metrics

