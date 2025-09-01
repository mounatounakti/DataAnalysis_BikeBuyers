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
  - `0-1` or `1-2 Miles` → `Short Distance`  
  - `2-5` or `5-10 Miles` → `Intermediate Distance`    
  - `10+ Miles` → `Long Distance`    
- **Grouped ages** into categories:  
  - `< 31` → `Adolescent`    
  - `31–55` → `Middle Age`  
  - `> 55` → `Old`  
- **Verified data integrity** to ensure no duplicates or inconsistent values after cleaning.
  
## 📊 Data Visualization 
### 1. Pivot Tables
I start creating pivot tables to summarize data and prepare for visualization, with the focus in these features:    
`Gender 👩‍🦱👨`  `Age category 🎂`  `Marital Status 💍`  `Cars owned 🚗`  `Commute distance 🚶‍♂️`  `Income 💵`  

### 2. Charts
Now, from pivot tables I created the following charts:  
![1](https://github.com/mounatounakti/DataAnalysis_BikeBuyers/blob/3105cb16ffaac7281c9d78e71694f1dbdba068ed/Src/1.png)   
→ Males purchased slightly more bikes (only 2.2% difference). 

 ![2](https://github.com/mounatounakti/DataAnalysis_BikeBuyers/blob/6e4eccf2db385e8e14f3dbb4e9cd58b94c6cf6dc/Src/2.png)  
→ Middle-aged people purchase bikes far more than adolescents or older customers. 

 ![3](https://github.com/mounatounakti/DataAnalysis_BikeBuyers/blob/6e4eccf2db385e8e14f3dbb4e9cd58b94c6cf6dc/Src/3.png)  
→ Married males purchase more bikes than married females, but single females purchase more than single males. 

 ![4](https://github.com/mounatounakti/DataAnalysis_BikeBuyers/blob/6e4eccf2db385e8e14f3dbb4e9cd58b94c6cf6dc/Src/4.png)  
→ People with short commutes purchase more bikes than those with longer commutes.

 ![5](https://github.com/mounatounakti/DataAnalysis_BikeBuyers/blob/6e4eccf2db385e8e14f3dbb4e9cd58b94c6cf6dc/Src/5.png)  
→ People who own 2 cars are surprisingly top bike buyers.  

 ![6](https://github.com/mounatounakti/DataAnalysis_BikeBuyers/blob/6e4eccf2db385e8e14f3dbb4e9cd58b94c6cf6dc/Src/6.png)  
→ Purchases peak around $60,000 income, then decline as income rises; males consistently purchase slightly more than females.  

## Conclusion

- The most likely bike buyers are **middle-aged** customers with around **$60k income**, **short commutes**, and **2 cars.**  
- Gender differences are small overall, but **marital status** changes the pattern.  
