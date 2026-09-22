# ApexPlanet Data Analytics Internship - Task 4

## Data Storytelling & Statistical Validation

This repository contains Task 4 of the ApexPlanet Data Analytics Internship.

The objective of this task was to combine insights from the previous analytical tasks into a cohesive business story and validate key findings using statistical hypothesis testing.

## Task Objectives

- Synthesize insights from Tasks 1-3
- Build a clear business narrative
- Perform statistical hypothesis testing
- Interpret p-values and confidence intervals
- Create a stakeholder-focused presentation
- Translate analytical findings into business recommendations

## Hypothesis Testing

### Test 1: High Value vs Medium Value Customers

**Null Hypothesis (H0):**  
There is no statistically significant difference in average transaction value between High Value and Medium Value customers.

**Alternative Hypothesis (H1):**  
There is a statistically significant difference in average transaction value between the two segments.

### Results

- High Value mean: 285,366.39
- Medium Value mean: 115,524.68
- Mean difference: 169,841.71
- t-statistic: 26.73
- p-value: 1.23 × 10^-85
- 95% confidence interval: [157,341.67, 182,341.75]

Since the p-value is below 0.05, the null hypothesis was rejected.

This indicates a statistically significant difference in transaction value between the two customer segments.

---

### Test 2: Male vs Female Customers

**Null Hypothesis (H0):**  
There is no statistically significant difference in average transaction value between male and female customers.

**Alternative Hypothesis (H1):**  
There is a statistically significant difference between the two groups.

### Results

- Male mean: 141,807.34
- Female mean: 136,883.21
- Mean difference: 4,924.13
- t-statistic: 0.68
- p-value: 0.495
- 95% confidence interval: [-9,231.58, 19,079.85]

Since the p-value is greater than 0.05, the null hypothesis was not rejected.

There is insufficient statistical evidence to conclude that average transaction value differs by gender.

## Key Business Findings

- High-value customers contribute substantially more revenue than medium-value customers.
- Gender alone does not appear to be a strong predictor of transaction value.
- Customer segmentation provides stronger business value than demographic targeting based only on gender.
- High-value customers should receive greater focus in retention and loyalty strategies.
- Medium-value customers represent an opportunity for upselling and cross-selling.

## Business Recommendations

- Prioritize retention strategies for High Value customers
- Develop upselling campaigns for Medium Value customers
- Use customer value segmentation rather than gender-based targeting
- Monitor high-performing product categories and geographic markets
- Continue using statistical testing to validate major business decisions

## Tools Used

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Looker Studio
- PowerPoint
- Git
- GitHub

## Repository Structure

```text
ApexPlanet-Data-Analytics-Task-4/
├── notebooks/
│   └── task4_hypothesis_testing.ipynb
├── presentation/
│   └── Task4_Data_Storytelling_Statistical_Validation.pptx
├── assets/
└── README.md
