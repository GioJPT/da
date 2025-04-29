**2nd project**

# Customer Segmentation 

## Introduction
This Project involved designing a customer segmentation dashboard using PowerBI, based on RFM (Recency, Frequency, Monetary) analysis. The original business request came through a series of internal emails discussing the need to identify and engage 'best customers' through targeted marketing campaigns. The goal was to buils a data-driven solution that enabled segmentation, highlights key customer behaviours, and supports personalised outreach.

# Project objectives
The primary objective was to help the marketing team understand customer value and engagement. Specifically, the project aimed to:
- Segment customers based on RFM scoring
- Highlight which segments contribute the most revenue
- Identify at-risk and lapsed customers
- Present insights in a visual, interactive dashboard for non-technical users
This wouls allow business users to make informed decisions about targeting and retention strategies.

# Process and Methods
The project began with the development of an SQL query that extracted core customer metrics: 
- **Recency**: How recently a customer made a purchase
- **Frequency**: How often they purchased
- **Monetary**: Total amount spent

Customers were scored from 1 to 3 in each dimension and then assigned a segment label based on their total RFM score (e.g., 'Fashionistas', 'Lapsed Customers', 'At-Risk Buyers'). Once the scoring logic was verified, I exported the dataset and loaded it into Power BI.
Using Power BI, I built a dashboard with:
- KPI cards for revenue and total customeres
- A pie chart for customer distribution
- A line graph for purchases over time
- Gender analysis per segment
- A geographic map to show city-level concentration

Filters were added for segment and date to enable dynamic exploration.

# Insights & findings
Several Key insights emerged:
- A large proportion of custoemrs were in 'Lost Causes' or 'At-Risk Buyers' segments
- Surprisingly, 'Lapsed Customers' still contributed the highest revenue, indicating past high-value engagement
- 'Fashionistas' (top customers) were few and responsible for relatively little revenue - suggesting they may be newly acquired
- The purchase trend showed clear seasonal peaks, particularly in mid-2022 and early 2023
- Gender data showed a male-dominated customer base, through some segments had more balance

# Challenges Encountered
There were several technical and analytical challenges:
- The customer count (574bn) initially appeared inaccurate - a formatting or aggregation issue that needed fixing
- Balancing detailed SQL logic with business clarity took iteration
- Some user data (gender, location) had missing or unknown values
- Visual layout choices had to be made to maintain clarity while still providing depth

# Lessons Learned
This project reinforced several key lessons:
- **RFM analysis is a powerful tool** to uncover value beyond just purchase frequency
- **Power BI enables clear storytelling**, but requires thoughtful layout and interaction design
- **Segmentation must be paired with action** - data without follow-through (e.g., targeted emails) limits impact
- **Understanding the business ask clearly** (via the email thread) was just as important as writing SQL

# impact and future improvements
The dashboard provides a clear framework for marketing to:
- Target top spenders for loyalty campaigns
- Re-engage at-risk or lapsed users with personalised offers
- Test campaigns by gender or city segments
For future improvement, I would add:
- KPIs for growth and churn
- A customer lifetime value (CLV) projection
- Integration with email automation platforms for closed-loop targeting

# Conclusion
This project was a valuable experience in translating business needs into a data product. The dashboard answers the original stakeholder question - who are our best customers - while also uncovering deeper behavioural patterns. I've strengthened my skills in SQL, Power BI, and data storytelling, and learned how to align data work with strategic marketing goals.
