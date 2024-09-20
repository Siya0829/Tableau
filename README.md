<img width="1440" alt="TABLEAU PROJ" src="https://github.com/user-attachments/assets/ffd77e07-ced7-404d-b842-7ce03bc5aa7e">


You can view the Loan Default dasboard in Tableau Public https://public.tableau.com/app/profile/siya.chugh/viz/LOanDefaultDashboard/Dashboard

### Loan Fraud Analysis Tableau Dashboard

#### Problem Statement:
The purpose of this dashboard is to identify potential cases of loan fraud by analyzing different loan attributes, including Loan-to-Value (LTV) ratio, credit score, loan approval status, and the purpose of the loan. By setting specific filters and conditions, the dashboard uncovers potential areas of concern like high LTV loans, low creditworthiness, loans approved without prior review, and suspicious patterns in loans based on credit score.

---

### Dashboard Components and Analysis:

#### 1. High LTV Loans (Potential Fraud - Inflated Property Values)
   - Objective: Identify loans with an LTV (Loan-to-Value) ratio above 80%, which may indicate potential fraud through inflated property values.
   - Data Filter: Loans with LTV > 80.
   - Insight: Loans with high LTV ratios can indicate either borrower risk due to a low down payment or potential manipulation of property values to secure a higher loan amount.
   - Visuals/Filters Used: LTV ratio > 80 filter applied to highlight such cases. This section uses bar graphs/heat maps to show the distribution of these loans across different regions or loan types.

#### 2. Loans Approved Without Prior Review (Low Creditworthiness)
   - Objective: Identify loans that were approved without prior review or for borrowers with low credit scores.
   - Data Filter: 
     - Loans approved without prior review.
     - Loans where borrowers have low creditworthiness, based on credit scores below a certain threshold (e.g., below 600).
   - Insight: These cases represent loans approved in circumstances where either the review process was bypassed, or the borrower’s creditworthiness did not warrant approval. This can indicate potential fraud due to lax controls.
   - Visuals/Filters Used: The dashboard includes a table or heatmap showing loans that fall under these conditions, with color-coded risk indicators for easy identification.

#### 3. Loan Purpose Based on Credit Score and Pre-Approval Status
   - Objective: Categorize the approved loans based on their purpose, showing the credit score range of the borrowers and whether the loans were pre-approved or not.
   - Data Filter:
     - Segmentation of loans based on credit score categories.
     - Filter for whether the loan was pre-approved.
   - Insight: This analysis provides insights into the relationship between the loan purpose (e.g., home loans, personal loans) and the borrower’s credit score and approval status. Loans with poor credit scores that were pre-approved might warrant further investigation.
   - Visuals/Filters Used: The dashboard uses a combination of stacked bar charts or pie charts to show the breakdown of loan purposes across different credit score ranges and pre-approval statuses.

#### 4. Low Credit Score with High Loan Value
   - Objective: Focus on loans with a credit score between 500-700 and a loan value greater than 26 lakhs, as these may be riskier loans that require further scrutiny.
   - Data Filter:
     - Filtered for loans where the credit score is in the range of 500-700.
     - Loan value is greater than 26 lakhs.
   - Insight: Borrowers with low credit scores receiving high-value loans may indicate leniency in the loan approval process or potential fraudulent activities.
   - Visuals/Filters Used: This analysis uses scatter plots or bar charts to show the correlation between loan values and credit scores, highlighting cases that meet the risky criteria.

---

### Steps Followed:
1. Data Preparation:
   - Imported loan data into Tableau.
   - Cleaned and transformed the data to ensure accuracy, handling any missing values or inconsistencies.
   - Calculated necessary metrics such as LTV ratio and filtered the data based on credit scores and loan approval statuses.

2. Dashboard Creation:
   - High LTV Loans: Created a chart to show loans with LTV > 80, categorizing them by loan type or region.
   - Loans Approved Without Review: Filtered loans based on approval status and credit score, and displayed them using conditional formatting.
   - Loan Purpose by Credit Score: Segmented loans based on purpose, credit score, and pre-approval status, visualized using pie charts or bar charts.
   - Low Credit Score with High Loan Value: Applied filters to show only loans with a credit score between 500-700 and a loan value greater than 26 lakhs, visualized using scatter plots.

3. Conditional Formatting:
   - Applied color-coding to easily identify areas of concern.
   - For example, loans with LTV > 80 were marked in red, and low credit scores were flagged for easy recognition.

---

### Results:
- Identified several high-risk loans based on LTV ratio and low creditworthiness.
- Uncovered a number of loans that were approved without prior review, which could potentially point to gaps in the loan approval process.
- Highlighted cases where pre-approved loans were given to individuals with low credit scores, signaling potential approval irregularities.
- Isolated loans with low credit scores (500-700) and high loan values (above 26 lakhs), warranting further investigation.

---

### Conclusion:
This dashboard effectively helps to detect potential loan fraud by identifying loans with risky characteristics. By focusing on LTV, credit scores, and loan approval statuses, the analysis reveals potential fraud hotspots, such as inflated property values or loans approved without sufficient review. This can assist in tightening controls and ensuring that loan approvals are based on sound creditworthiness.

---

