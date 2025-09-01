# Bike Buyers Dashboard 🚲 Excel Data Analysis Project
Excel dashboard analyzing the Bike Buyers dataset from Kaggle. Includes data cleaning, pivot tables, and visualizations to identify factors influencing bike purchases.  

## 🎯 Project Overview
I just started doing data analysis projects to sharpen my skills.  
The goal of this project is to help bike sellers understand which factors influence whether customers buy a bike or not.

## 🗝️ Data Source
• **Dataset:** Bike Buyers  
**•** <a href="https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Excel%20Project%20Dataset.xlsx"> Data Set Link <a/>  
**• Format:** `.xlsx` 

## 🧼 Data Cleaning 

Here's the steps I followed to prepare the data:  
- **Removed duplicates** to ensure clean records.  
- **Standardized text values:**  
  - Gender column: replaced `M/F` with `Male/Female`.  
  - Marital Status: replaced `M/S` with `Married/Single`.  
- **Converted income values** from currency to number format to allow easy calculations.  
- **Grouped commute distances** into categories using a nested `IF` formula:  
  - `0-1` or `1-2 Miles` → *Short Distance*  
  - `2-5` or `5-10 Miles` → *Intermediate Distance*  
  - `10+ Miles` → *Long Distance*  
- **Grouped ages** into categories:  
  - `< 31` → *Adolescent*  
  - `31–55` → *Middle Age*  
  - `> 55` → *Old*  
- **Verified data integrity** to ensure no duplicates or inconsistent values after cleaning.
  
## Data Visualization 
### a) Pivot Tables
I start creating pivot tables to summarize data and prepare for visualization, with the focus in these features:    
`Gender 👩‍🦱👨`  `Age category 🎂`  `Marital Status 💍`  `Cars owned 🚗`  `Commute distance 🚶‍♂️`  `Income 💵`  

### b) Charts
Now, from pivot tables I created the following charts:  
![Males purchased slightly more bikes (only 2.2% difference)](https://github.com/mounatounakti/DataAnalysis_BikeBuyers/blob/3105cb16ffaac7281c9d78e71694f1dbdba068ed/Src/1.png)  
→ Males purchased slightly more bikes (only 2.2% difference).  
 
→ Middle-aged people purchase bikes far more than adolescents or older customers.  
→ Married males purchase more bikes than married females, but single females purchase more than single males.  
→ People with short commutes purchase more bikes than those with longer commutes.  
→ People who own 2 cars are surprisingly top bike buyers.  
→ Purchases peak around $60,000 income, then decline as income rises; males consistently purchase slightly more than females.  

## Conclusion

- The most likely bike buyers are **middle-aged** customers with around **$60k income**, **short commutes**, and **2 cars.**  
- Gender differences are small overall, but **marital status** changes the pattern.  
