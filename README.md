# Customer CreditCard Transaction Analysis

## Project Overview

This project focuses on analyzing and gaining insights from **Customer creditcard Transaction** data over a 2-year period to help improve business decision-making. By using tools like **SQL**, **Power BI**, and **DAX**, the project highlights key metrics, identifies patterns in customer behavior, and provides actionable business insights.



## Technologies Used
- **SQL** for data extraction, cleaning, and transformation.
- **Power BI** for interactive data visualization and dashboard creation.
- **DAX** for creating dynamic measures and KPIs in Power BI.
- **PostgreSQL** for data storage and integration.

## Data Description

The dataset contains the following key tables:

1. **Transaction Data (`credit_card.csv`)**:
   - Includes transaction details such as **client number**, **card type**, **transaction amount**, and **credit limits**.
   - Key columns: `client_Num`, `card_Category`, `annual_fees`, `interest_earned`, `total_trans_amt`, `total_trans_vol`, etc.

2. **Customer Data (`customer_details.csv`)**:
   - Contains customer demographics, such as **age**, **income**, **gender**, **education level**, and **marital status**.
   - Key columns: `Client_Num`, `customer_age`, `gender`, `income`, `customer_job`, `state_cd`, etc.

## Steps Involved

### 1. **Data Collection & Integration**:
   - Imported the data from **CSV files** into **PostgreSQL** to handle large datasets effectively.
   - Cleaned and transformed the data using **SQL** queries to ensure data consistency and accuracy.

### 2. **Data Transformation & Enrichment**:
   - Created new columns and calculated measures using **DAX** in Power BI:
     - `Revenue`: Combined **annual fees**, **interest earned**, and **transaction amounts**.
     - `Week_no`: Extracted week number from the date to track performance over time.
     - `AgeGroup` and `IncomeGroup`: Segmented customers into distinct groups based on age and income.
   
### 3. **KPI Definition & Tracking**:
   - Defined and tracked essential KPIs:
     - **Revenue**
     - **Interest Earned**
     - **Transaction Volume**
     - **Customer Satisfaction Score (CSS)**

### 4. **Dashboard Creation**:
   - Created **interactive dashboards** in **Power BI** for **transaction analysis** and **customer analysis**:
     - Visualized KPIs and key insights.
     - Added **filters** and **slicers** ( week number, age group, card type gender) for user interactivity.

### 5. **Data Insights**:
   - Analyzed the data and extracted insights on **card activation**, **revenue contribution by gender and income**, and **transaction trends**.
   - Developed actionable recommendations for improving **customer engagement** and reducing **delinquency rates**.



## Dashboards & Visualizations

1. **Transaction Analysis**:
   - Visualized key metrics like **revenue**, **transaction volume**, and **card activation**.
   - Allowed users to filter data by **card type**, **quarter**, **gender**, and **customer age groups**.
   
2. **Customer Analysis**:
   - Provided insights on **customer income groups**, **satisfaction scores**, and **behavior patterns**.
   - Used **slicers** to visualize weekly trends in **customer engagement** and **revenue generation**.

## Setup & Installation

To replicate this project or use the code:

### Prerequisites:
- **PostgreSQL** for data storage.
- **Power BI** for data visualization.
- SQL client to run queries and manage data.
- Access to **CSV files** (`credit_card.csv` and `customer_details.csv`).

### Steps:
1. Clone this repository or download the dataset files.
2. Load the data into **PostgreSQL** and execute the necessary SQL queries to clean and preprocess the data.
3. Import the data into **Power BI** and apply the **DAX formulas** for dynamic calculations.
4. Customize the dashboard as needed to generate specific insights.

## Key Findings

- **Total Revenue**: $55M
- **Interest Earned**: $8M
- **Total Transaction Amount**: $46M
- **Card Activation Rate**: 57.47%
- **Delinquent Accounts**: 6.07%
- **Gender Insights**: Male customers contribute $31M in revenue, while female customers contribute $26M.
- **Income Insights**: High-income males show significantly higher card usage compared to low-income males.
- **Card Type**: **Blue** and **Silver** card types together account for **93%** of total transactions.
- **Geographic Insights**: TX, NY, and CA together contribute to **68%** of the transactions.

## Insights & Recommendations

### **Insights**:

1. **Overall Revenue and Interest Generation**:
   - **Total Revenue**: $55M
   - **Interest Earned**: $8M, indicating a strong contribution from interest.
   - **Total Transaction Amount**: $46M, showing high transaction volume, but room for improvement in customer engagement.

2. **Customer Gender Insights**:
   - **Male customers** generate **$31M** in revenue, while **female customers** contribute **$26M**.
   - **Male customers** show higher spending; however, there's potential for increasing female customer engagement.

3. **Income Group Behavior**:
   - **High-income males** tend to spend more on credit cards compared to low-income males.
   - **Low-income groups** show low engagement with credit cards, suggesting an opportunity to improve usage rates in this segment.

4. **Geographic Insights**:
   - **TX, NY, and CA** contribute to **68%** of total transactions.
   - Expansion in underrepresented regions could help capture more market share.

5. **Card Activation Rate**:
   - **Card Activation Rate** is only **57.47%**, indicating a large portion of cards remain unused.
   - The business could improve customer onboarding processes to boost activation.

6. **Delinquency Rate**:
   - **Delinquency Rate** is **6.07%**, indicating some customers are not paying within 30 days.
   - This is a concern for credit risk management and requires intervention.

7. **Card Type Distribution**:
   - **Blue** and **Silver** card types account for **93%** of total transactions, while other card types have lower engagement.
   - Reevaluating the offerings for **Gold** and **Platinum** cards might increase adoption.

### **Recommendations**:

1. **Increase Card Activation Rate**:
   - Implement targeted **activation campaigns** with **incentives** for customers to activate their cards within the first 30 days.
   - Use automated **reminders** and **personalized offers** to boost card activations.

2. **Focus on Female Customers**:
   - Launch **targeted marketing** for female customers, offering products or rewards tailored to their preferences.
   - Partner with female-oriented brands or offer discounts related to family or lifestyle needs.

3. **Expand Low-Income Group Engagement**:
   - Introduce **affordable credit card options** with lower fees and simpler terms.
   - Provide **financial literacy programs** to educate low-income customers on the benefits of credit card usage.

4. **Expand in Underrepresented Regions**:
   - Increase outreach efforts in **TX**, **NY**, and **CA**, where there's already significant market penetration, while expanding into **underrepresented regions**.
   - Use region-specific campaigns and targeted advertisements to boost brand awareness.

5. **Lower Delinquency Rate**:
   - Introduce **payment reminders**, **flexible payment options**, and **early payment discounts** to help reduce the delinquency rate.
   - Offer **financial counseling** and **credit restructuring** to customers struggling with payments.

6. **Enhance Higher-Tier Card Appeal**:
   - Improve the **value proposition** for **Gold** and **Platinum** cards with **exclusive rewards**, **higher cashback**, and **premium services**.
   - Create targeted marketing campaigns to promote higher-tier cards, emphasizing unique benefits.

7. **Implement Predictive Analytics**:
   - Use **predictive modeling** to forecast customer behaviors and identify potential risks.
   - Use insights to develop **personalized offers**, improve **customer retention**, and reduce **churn**.


## Conclusion

This project demonstrates my proficiency in **data cleaning**, **SQL querying**, and **data visualization**. By analyzing **customer** and **transaction** data, I was able to derive **actionable insights** to help businesses improve their **customer retention**, optimize **card usage**, and refine **financial strategies**.

This project further enhanced my skills in **Power BI**, **DAX**, and **SQL** and has prepared me to contribute effectively as a **Data Analyst**.
