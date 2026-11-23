# MediBuddy Insurance Data Analysis

**Exploratory data analysis of health insurance claims using Python, Pandas and Matplotlib.**

## 1. Project Overview

This project analyses health insurance data to investigate factors associated with insurance claim amounts. It explores customer demographics, lifestyle characteristics and geographic information to understand how these variables relate to insurance costs.

The objective is to derive business insights that could support insurance pricing, risk assessment, customer segmentation and wellness initiatives at MediBuddy.

## 2. Business Questions

The analysis addresses eight questions:

1. Does gender matter for extending policies?
2. What is the average amount spent per policy?
3. Should policies differ by geographic location?
4. Does the number of dependents affect claims?
5. Does BMI influence insurance claims?
6. Is smoking status important?
7. Does age affect insurance claims?
8. Can MediBuddy offer discounts based on BMI and health status?

## 3. Technology Stack

| Technology | Application |
|---|---|
| Python | Data analysis |
| Pandas | Data loading, merging and manipulation |
| Matplotlib | Data visualisation |
| Jupyter Notebook | Analysis and documentation |
| Microsoft Excel | Source datasets |

## 4. Dataset Description

The project uses two Excel datasets containing 1,338 records each.

**Insurance Data Price**
- Policy number
- Age
- Sex
- BMI
- Charges in INR

**Personal Details**
- Policy number
- Number of children
- Smoking status
- Region

The two datasets are merged using the common `Policy no.` field to create the analysis dataset.

*Note: The original Excel datasets are excluded from this public repository through `.gitignore`. They are retained locally.*

## 5. Methodology

The analysis follows these steps:

1. Imported the required Python libraries.
2. Loaded the two Excel datasets using Pandas.
3. Merged both datasets using the policy number.
4. Examined descriptive statistics.
5. Grouped insurance charges by gender, region, number of children and smoking status.
6. Calculated correlations between BMI, age and insurance charges.
7. Created bar charts and scatter plots to explore relationships.
8. Compared average claims for customers with BMI below 25 and those with BMI of 25 or above.

## 6. Key Findings

The supplied analysis report identifies the following findings:

- **Gender:** Average claims were ₹13,956 for males and ₹12,569 for females. The report concludes that gender is not a strong constraint.
- **Average claim:** The reported average claim amount was ₹13,270.
- **Region:** The Southeast region recorded the highest average claims.
- **Dependents:** The report identifies higher claims among customers with more children.
- **BMI:** Higher BMI was associated with higher insurance claims.
- **Smoking:** Smokers were reported to claim nearly four times more than non-smokers.
- **Age:** Older customers were associated with higher claim amounts.
- **BMI-based discounts:** Customers with BMI below 25 had lower average claims in the analysis.

These findings describe patterns in the supplied dataset and do not establish causation.

## 7. Business Recommendations

Based on the findings reported in the analysis, potential business opportunities include:

1. **Wellness incentives:** Explore incentives that encourage healthier lifestyle choices.
2. **Preventive healthcare:** Promote preventive healthcare and wellness programmes.
3. **Risk assessment:** Use demographic and lifestyle patterns as inputs for further insurance risk analysis.
4. **Customer segmentation:** Explore customer segments based on age, smoking status, BMI and geographic region.
5. **Discount strategies:** Evaluate BMI-related wellness discounts through further actuarial and regulatory review.

## 8. Repository Structure

```text
medibuddy-insurance-data-analysis/
│
├── Dataset/
│   ├── Medibuddy Insurance Data Price (1) (2).xlsx
│   └── Medibuddy insurance data personal details (1) (2).xlsx
│
├── Python/
│   └── medibuddy_insurance_analysis.ipynb
│
├── Reports/
│   └── Medibuddy Report.docx
│
├── .gitignore
└── README.md
```

## 9. Limitations

- The analysis is based on 1,338 policy records.
- The dataset may not represent the broader insurance customer population.
- Observed relationships do not establish causal relationships.
- The analysis is exploratory and does not constitute a validated insurance pricing model.
- BMI-based discounts would require additional actuarial, legal and regulatory assessment.

## 10. Conclusion

This project demonstrates how Python-based exploratory data analysis can help investigate factors associated with health insurance claims.

By examining demographic, lifestyle and geographic variables, the analysis identifies patterns that could support further research into insurance risk assessment, customer segmentation and wellness-focused initiatives.

---

**Project:** MediBuddy Insurance Data Analysis  
**Domain:** Health Insurance Analytics  
**Tools:** Python | Pandas | Matplotlib | Jupyter Notebook