1. Outline
Introduction
Story of Data
Data Preprocessing & Splitting
Pre-Analysis (Exploratory Insights)
In-Analysis (Deeper Patterns & Findings)
Post-Analysis (Insights & Conclusions)
Visualizations & Dashboards
Recommendations & Strategic Observations
Conclusion
References & Appendices
2. Introduction
Objective: To analyze online food ordering behaviors and identify how demographic and location factors influence customer satisfaction and service delivery.
Problem Statement: Despite growing online ordering trends, businesses lack detailed insights into which customer types are most satisfied or experience more issues.
Data & Tools: The dataset includes user demographics, order status, and feedback. Microsoft Excel was used for cleaning, pivot analysis, and dashboard visualizations.
3. Story of Data
Data Source: The dataset is from kaggle.com
Collection Method: Structured extraction via internal databases.
Data Structure:
Rows: Each row represents one customer’s profile or order status.
Columns: Attributes like age, gender, income, education, pin code, order status, feedback score.
Key Features:
Demographics: Age, marital status, income.
Behavior: Order status, feedback.
Geography: Latitude/longitude, pin code.
Limitations: Potential bias in self-reported feedback; no time-series (date of order) or menu item data.
4. Data Preprocessing & Splitting
Cleaning:
Removed incomplete rows with missing feedback or location.
Standardized income brackets and education levels for consistency.
Handling Missing Values: Used median imputation for income; removed rows with null geographic data.
Transformations:
Created new categorical variables: e.g., “High Income,” “Urban Area” using pin code data.
Grouped feedback scores into sentiment categories (e.g., Positive, Neutral, Negative).
Splitting: Segmented customers by:
Independent variables: Demographics (age, income, marital status).
Dependent variable: Order status or satisfaction.
Industry Context: Food tech / delivery services.
Stakeholders: Marketing teams, operations managers, UX designers.
Value to Industry: Helps in personalizing offers, refining delivery routes, and targeting customer segments more effectively.
5. Pre-Analysis
Trends Identified:
Younger customers (❤0) placed more orders but reported lower satisfaction.
Customers from urban pin codes showed fewer delivery issues.
Potential Correlations:
Positive sentiment increased with income.
Family size had a weak relationship with negative feedback.
Initial Insights:
Some professions (e.g., IT) had consistently higher feedback scores.
Geographic regions closer to distribution hubs had better service outcomes.
6. In-Analysis
Unconfirmed Patterns:
Women aged 25–35 in urban zones gave the highest satisfaction ratings.
Customers with graduate-level education reported more delivery complaints (hypothesis: higher expectations?).
Recommendations:
Customize offers for younger users to increase satisfaction.
Investigate service gaps in regions with recurring negative feedback.
Techniques in Excel:
PivotTables for demographic–feedback cross-analysis.
COUNTIFS and AVERAGEIFS for group statistics.
Conditional formatting for geographic segmentations.
7. Post-Analysis & Insights
Key Findings:
Age and location are the most significant predictors of satisfaction.
Middle-income customers in semi-urban zones had the highest loyalty (repeat orders + positive feedback).
Comparison to Initial Hypotheses:
Contrary to assumptions, income had less impact than education on feedback.
Urban customers were more likely to report issues despite faster delivery times.
8. Data Visualizations & Dashboards
Charts Included:
Bar chart: Feedback score by age group.
Pie chart: Order status by region.
Heat map: Satisfaction score distribution across pin codes.
Dashboards:
Created an interactive Excel dashboard with filters for age, gender, and location.
Explanation:
The heat map highlights underserved areas with high negative sentiment despite high order volumes.
9. Recommendations & Observations
Actionable Insights:
Launch targeted support in high-volume, low-satisfaction zones.
Test promotions aimed at young professionals with high churn risk.
Business Optimizations:
Adjust delivery routing in low-rated regions based on pin code clusters.
Introduce post-order surveys customized by age and education level.
Unexpected Findings:
Users with higher education levels were more likely to leave neutral or negative feedback, possibly due to higher service expectations.
10. Conclusion
Key Learnings:
Customer satisfaction is multifaceted demographics, location, and order status interact in complex ways.
Limitations:
No timestamps or item-level order data limits time-series or product-specific analysis.
Future Research:
Incorporate time of day, type of food ordered, and historical order frequency for deeper behavioral profiling.
11. References & Appendices
References:
https://drive.google.com/file/d/1IxLa-N2vvgjP-ML-DkbrH0UzkCCT7ol5/view?usp=sharing Data used![Amalazone dashboard](https://github.com/user-attachments/assets/8d9ccca6-75c8-4ef9-bd8d-293939dd0296)
