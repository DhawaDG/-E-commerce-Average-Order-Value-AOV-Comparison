# 🛒 A/B Testing Project: E-commerce Average Order Value (AOV) Comparison

## 🧪 Overview
This project investigates whether a new website feature or design leads to a significant increase in the Average Order Value (AOV) for an e-commerce platform. We use A/B testing and statistical hypothesis testing to compare the AOV between control and treatment groups.

## 🗂️ Project Details
- **Project ID:** 3 
- **Title:** E-commerce Average Order Value  
- **Method:** Welch’s t-test  
- **Data Type:** Continuous  
- **Control Group:** Standard checkout  
- **Treatment Group:** Optimized checkout flow  
- **Time Spent:** 2–3 hours  
- **Difficulty Level:** Beginner  

## 🎯 Objective
To determine if the new feature or design increases the average order value compared to the original.

## 📊 Hypotheses
- **Null Hypothesis (H₀):** The mean AOV is the same for both control and treatment groups.
- **Alternative Hypothesis (H₁):** The treatment group has a higher mean AOV.
- **Type I Error Rate (α):** 0.05
- **Test Type:** Right-tailed t-test (one-tailed)

## 🧰 Tools & Libraries
- Python
- NumPy
- Pandas
- SciPy (`scipy.stats.ttest_ind`)
- Matplotlib / Seaborn (for visualization)

## 📁 Dataset Structure
The dataset contains order values for users in two groups:
- `group`: Either control or treatment
- `order_value`: Numeric value representing the order amount

## 📈 Results
- Conducted Welch’s t-test to compare the mean AOV between control and treatment groups.
- Used `alternative='greater'` in `scipy.stats.ttest_ind` to test if the treatment group has a higher mean AOV.
- Evaluated the p-value against α = 0.05 to determine statistical significance.
- There is no difference  between **Controlled:Continuous Standard checkout and Treatment: Optimized checkout flow** of E-commerce Average Order Value.
- There's a 18.68% probability of seeing at least a $1.53 difference by random chance alone, even if the optimization had no real effect.
-  0.040 cohen's d indicates a negligible effect size backed by  While the treatment shows a nominal 1.7% lift, this tiny effect

## 📚 Key Concepts Learned
- Designing and conducting A/B tests for e-commerce metrics
- Comparing average order values using Welch’s t-test
- Setting up and interpreting one-tailed hypothesis tests
- Calculating and understanding p-values and effect sizes (Cohen’s d)
- Using Python libraries (NumPy, Pandas, SciPy) for statistical analysis
- Visualizing group differences to support findings
- Evaluating practical vs. statistical significance in business decisions

## 🔗 References
- [Trustworthy Online Controlled Experiments - Ron Kohavi](https://www.scribd.com/document/711189937/Kohavi-Diane-Tang-Xu-Trustworthy-Online-Controlled-Experiments-A-Practical-Guide-to-AB-Testing-2020)
- [Practical Statistics for Data Scientists](https://github.com/DhawaDG/Email-Newsletter-Signup-Optimization/blob/master/reference%20book/Practical%20Statistics%20for%20Data%20Scientists%20(%20PDFDrive%20).pdf)
- [SciPy t-test Documentation](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.ttest_ind.html)

## 🚀 Next Steps
- Experiment with different sample sizes and order value distributions
- Visualize group differences with boxplots or confidence intervals
- Apply this method to real transaction data

---
📂 [**+20 AB Testing Projects →**](https://github.com/DhawaDG/AB_Testing_Project/blob/main/README.md)

