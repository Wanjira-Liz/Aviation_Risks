✈️ Phase 1 Project-Aviation Safety Analysis by Wanjira_Nyamburaby Wanjira_Nyambura

📌 Project Goal
This project was designed to help the company identify the lowest-risk aircraft types and flight conditions to guide strategic decision-making as they expand into aviation. Using civil aviation accident data from the National Transportation Safety Board (NTSB), I analyzed over 90,000 incidents to find safety patterns across aircraft make, engine type, flight purpose, and environmental conditions.

🧠 Business Problem
The aviation division is exploring the purchase of aircraft for private and commercial use. However, leadership lacks insights into the potential safety risks of different aircraft types. This project aims to deliver actionable recommendations that reduce liability, guide safer purchases, and improve operational policies.

📊 Data Source
Dataset: NTSB Aviation Accident Data (1962–2023)

Format: CSV

Size: 90,348 rows, 31 columns

Scope: U.S. and international waters, civil aviation only

🧹 Data Cleaning and Preparation
Steps included:

Dropped irrelevant columns (e.g. Event ID, coordinates, registration numbers)

Filled missing values using mean for numeric and mode for categorical variables

Engineered new fields:

Make_Model – a merged aircraft identifier

Severe_Injuries – total of fatal + serious injuries

Year – extracted from Event.Date

Removed inconsistent entries like "none", "unknown", "n/a"

📈 Key Exploratory Insights
Landing and takeoff are the most accident-prone flight phases

Personal-use flights had the highest number of severe injuries

Single-engine reciprocating aircraft appear most frequently in accidents

Poor weather conditions (IMC) are strongly linked to fatality rates

A small group of specific aircraft models were consistently linked to higher fatality and destruction rates

✅ Final Business Recommendations
1.Favor Multi-Engine, Turboprop or Jet Aircraft Over Single-Engine Reciprocating Investigate engine type performance and maintenance records.
2.Avoid Aircraft with High Fatality & Destruction History
3.Prefer Aircraft Commonly Used for Instructional or Business Flights 
4.Choose Aircraft Designed for Stability in IMC 
5.Focus training and safety protocols on high-risk flight phases

📂 Files Included
File	Description
PROJECT_BY_WANJIRA(1).ipynb	Cleaned, well-commented analysis notebook
cleaned_aviation(1).csv	Exported dataset for Tableau/dashboard use
aviation_analysis_by_wanjira.pdf	Notebook PDF for grading or presentation
presentation.pdf	Business-facing non-technical slide deck (if applicable)

📊 Tableau Dashboard
You can explore the interactive dashboard here:
[https://public.tableau.com/app/profile/elizabeth.nyambura/viz/Phase1Project_17535452151590/Dashboard1]
(Includes KPIs of Injuries, Safest Aircraft by injuries, Aircraft Damage by make_model, flight phase, and year. Filtered by flight phase, year, aircraft category and damage.)

🧭 Conclusion
This project fulfills the objective of helping a non-technical stakeholder identify low-risk aircraft for acquisition. By cleaning, exploring, and visualizing historical aviation data, I uncovered the patterns that matter most in preventing severe accidents.
The business can now move forward with data-backed safety protocols, training investments, and procurement strategies.

🙋‍♀️ About Me
Wanjira_Nyambura
Data Science Student | Actuarial Science graduate | Entrepreneur | Investments Enthusiast
Email: wanjiranyambura33@gmail.com

💬 Questions?
For questions, feedback, or collaboration, please reach out via GitHub or Email.
