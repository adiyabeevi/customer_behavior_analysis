#  Customer Behavior Statistics Project

##  Objective
The goal of this project is to analyze customer behavior using statistical tools in Python and find insights related to spending patterns, churn, and campaign effectiveness. We use descriptive and inferential statistics to draw useful conclusions from the dataset.

---

##  Dataset Columns
- `CustomerID`
- `Gender`
- `Region`
- `PurchaseAmount`
- `ProductCategory`
- `Churn` (Yes/No)
- `CampaignGroup` (A/B)

---

##  Tools & Libraries Used
- Python
- Pandas
- Numpy
- Seaborn & Matplotlib
- Scipy.stats

---

## Process Followed

1. **Data Loading**  
   Loaded the dataset using Pandas.

2. **Descriptive Statistics**  
   Calculated mean, median, and mode of PurchaseAmount.

3. **Outlier Detection**  
   Used boxplots and IQR method to identify outliers.

4. **Skewness & Kurtosis**  
   Measured shape of data distribution.

5. **Gender-based Spending Analysis**  
   Compared average PurchaseAmount between Male and Female using t-test.

6. **ProductCategory vs Churn**  
   Used countplot to check churn distribution across product types.

7. **Region-wise Spending**  
   Performed ANOVA to see if PurchaseAmount differs across regions.

8. **Campaign Performance**  
   Compared CampaignGroup A vs B on average PurchaseAmount.

9. **Normality Check**  
   Plotted histogram and Q-Q plot to check if data follows normal distribution.

10. **Central Limit Theorem (CLT)**  
    Demonstrated how sample means form a normal distribution.

11. **Confidence Interval**  
    Calculated 95% confidence interval for average PurchaseAmount.

---

## Conclusion

Here used simple statistics and visual tools to uncover key customer behavior patterns:
- Found average spending and outliers.
- Saw differences between genders and regions.
- Identified churn trends and campaign performance.
- Applied CLT and built confidence intervals for better decision-making.

These insights help understand customer behavior and support data-driven business strategies.

---

##  Author
**Name**: Adiya Beevi S 
**Organization**: Entri Elevate  


