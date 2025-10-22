#1. Project Title :

Insurance Risk & Claims Analysis Dashboard
A dynamic Power BI dashboard that delivers a comprehensive overview of insurance policies, claim distributions, and customer demographics—helping insurance analysts uncover trends in claim amounts, risk categories, and policyholder profiles.

2. Purpose :

The Insurance Risk & Claims Analysis Dashboard is an interactive and data-driven Power BI report designed to visualize and monitor insurance portfolio performance. It enables insurance companies to analyze policy distribution, claim frequency, and customer risk profiles across demographics, vehicle attributes, and coverage zones.
The purpose of this dashboard is to empower stakeholders to make informed decisions on risk management, customer segmentation, and premium strategy optimization.

3. Tech Stack :

The dashboard was built using the following tools and technologies:
• 📊 Power BI Desktop – Core platform for designing and visualizing the dashboard.
• ⚙️ Power Query – Used for data cleaning, transformation, and preparation.
• 🧮 DAX (Data Analysis Expressions) – Created calculated measures for KPIs such as Average Claim Frequency and Average Claim Amount.
• 🧩 Data Modeling – Established relationships among policy, claims, and demographic data tables for accurate cross-filtering.
• 📁 File Format – Developed in .pbix, exported as .png for presentation.

4. Data Source :

Source: Internal Insurance Policy & Claim Database
The dataset includes information on:

Policyholder demographics (age group, gender, education, marital status)

Vehicle information (car make, year, and usage type)

Claim statistics (claim frequency, claim amount, and total policies)

Coverage details (zones, risk levels, and customer categories)

The structured dataset allows for trend and correlation analysis across multiple customer and vehicle dimensions.

5. Features :
   
• Business Problem

Insurance companies often struggle to quickly identify high-risk customer groups, claim trends by region, and the distribution of policies by demographic factors. Traditional tabular reports fail to present the holistic view required for strategic decision-making.

• Goal of the Dashboard

To build an interactive analytical tool that helps:

Visualize insurance claim and policy trends.

Compare claim frequencies and amounts across demographics and car types.

Understand risk distribution by geography and education level.

Support data-driven strategies for pricing, marketing, and fraud prevention.

• Walkthrough of Key Visuals
🔹 KPI Overview (Top Left)

Total Policies: 37,542

Total Claim Amount: $187.8M

Average Claim Frequency: 0.5

Average Claim Amount: $5K

Gender Split: Male 18.7K | Female 18.8K
These top-level KPIs summarize the entire insurance portfolio at a glance.

🔹 Policies by Car Use (Donut Chart)

Displays the distribution between Commercial (7K) and Private (30K) vehicle policies—indicating a higher concentration in private use.

🔹 Policies by Car Make (Bar Chart)

Highlights the top car brands insured, with Ford (3.3K) and Chevrolet (3.0K) leading, providing insights for brand-based risk assessment.

🔹 Policies by Coverage Zone (Donut Chart)

Breakdown by region type—Urban, Rural, Suburban, Highly Urban, Highly Rural—each holding around 7K–8K policies, indicating well-distributed customer coverage.

🔹 Policies by Age Group (Bar Chart)

Reveals that most policyholders fall within 26–55 years, with ~7.1K policies in each group, useful for targeting age-based marketing.

🔹 Policies by Car Year (Line Chart)

Tracks the trend of insured vehicles by manufacturing year from 1990–2020, showing a peak around the early 2010s.

🔹 Policies by Kids Driving (Column Chart)

Analyzes policies based on the number of children driving, identifying negligible data beyond one child driver.

🔹 Policies by Education (Pie Chart)

Displays education distribution—Bachelors (49.81%) being the largest, followed by Masters (27.81%) and High School (15.02%).

🔹 Claim Amount by Education & Marital Status (Matrix Table)

Provides a cross-sectional view of claim amount distribution.
Key Insights:

Singles have the highest total claim amount ($96.3M).

Married individuals claim around $50.6M, suggesting stability in claims.

Bachelor’s degree holders represent the largest contributor ($31.1M married, $38.7M single).

• Business Impact & Insights

📈 Customer Insights: Identifies high-claim demographics and car brands for better underwriting strategies.

🧠 Risk Management: Helps assess which zones and age groups pose higher claim risks.

💡 Marketing Optimization: Enables personalized insurance offerings based on education, age, and marital status.

💰 Financial Planning: Visualizes average claim amounts to predict future liabilities and optimize pricing models.

🌍 Strategic Decision-Making: Provides a consolidated view of the insurance ecosystem, driving data-backed decisions for growth and risk reduction.

6. Screenshot :

Dashboard Preview:
![Insurance Risk & Claims Analysis Dashboard](https://raw.githubusercontent.com/adnanspartan/insurance-risk-analysis/main/assets/Snapshot%20of%20the%20Dashboard.png)
