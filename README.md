This project investigates the comparative effectiveness of **single-task learning (STL)** and **multi-task learning (MTL)** approaches in predicting generalised symptom severity among individuals with schizophrenia using smartphone-based digital phenotyping data from the **CrossCheck dataset**.

## Research Objective

While multi-task learning is commonly assumed to improve predictive performance by leveraging shared representations across tasks, this study critically evaluates whether that assumption holds in **real-world mental health data**, which is often sparse and highly personalised.

The objective of this research is to determine whether **single-task models can outperform multi-task models** under such conditions.

## Methodology

The study employs both single-task and multi-task variants of the **Least Absolute Shrinkage and Selection Operator (LASSO)**:

- **Single-task model:** LassoCV  
- **Multi-task model:** MultiTaskLassoCV  

Model performance was evaluated using **Root Mean Square Error (RMSE)** to measure prediction accuracy. The **Wilcoxon signed-rank test** was applied to assess the statistical significance of performance differences between models.

## Key Findings

Results indicate that:
- **Single-task learning models outperform multi-task learning models** when predicting generalised symptom severity in sparse datasets.
- Multi-task learning may introduce noise rather than shared benefit when applied to highly personalised mental health data.

These findings challenge prevailing assumptions in digital mental health modelling and highlight the importance of model selection based on data characteristics rather than convention.

## Impact and Relevance

This work contributes to:
- Improved understanding of AI model performance in digital mental health applications
- Development of more accurate personalised symptom prediction tools
- Evidence-based decision-making in healthcare-focused machine learning systems

## Author

**Olajumoke Akinremi**  
Data Scientist | Digital Health Researcher | Founder – Data for Social Impact
