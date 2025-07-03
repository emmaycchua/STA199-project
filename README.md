# Gender Pay Gap and Workforce Representation (2013-2016)

Website: [https://sta199-s25.github.io/project-STA1NANA/](https://sta199-s25.github.io/project-STA1NANA/)  
Course: STA 199 – Introduction to Data Science and Statistical Thinking (Duke University)  
Team: Ellie Armstrong, Nikki Caparrelli, Emma Chua, Stephanie Sensel


**Overview**

This project investigates how the gender pay gap varies across job categories and with female representation in the workforce using U.S. labor statistics from 2013–2016. The research analyzes trends in female wages as a percentage of male wages, especially in male-dominated vs. female-dominated occupations.



**Research Question**

How does the gender pay gap vary across major job categories and levels of female workforce representation?



**Data**

Primary dataset: U.S. Bureau of Labor Statistics and U.S. Census data (2013–2016)
- Observations: 2,089 workforce-year combinations across 301 occupations
- Variables analyzed:
  - `major_category` (broad occupation)
  - `percent_female` (share of women in occupation)
  - `wage_percent_of_male` (female earnings as % of male earnings)
  - Median earnings by gender
  - Workforce counts by gender



**Methods**

Three linear models were developed:

1. Simple Linear Model: 
   - Predictor: `percent_female`  
   - Finding: A modest positive relationship between female representation and relative wages

2. Additive Model:
   - Predictors: `percent_female` + `major_category`  
   - Finding: More explanatory power, with significant job category effects

3. Interaction Model (Selected): 
   - Predictors: Interaction between `percent_female` and `major_category`  
   - Finding: Strongest explanatory model (Adjusted R² ≈ 14.4%), showing nuanced differences across job types
   - Revealed that in certain male-dominated fields (e.g. Engineering, Construction), increasing female representation did not necessarily improve wage equity — contrary to our initial hypothesis.


  
**Summary**

This project shows that the gender pay gap is not uniform — it varies significantly by occupation type and gender composition of the workforce. Even within sectors with greater female representation, wage gaps can persist, and in male-dominated fields, representation alone may not be enough to reduce disparity.
