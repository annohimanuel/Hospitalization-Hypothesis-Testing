# Project Requirements: Hospitalization Hypothesis Testing

## Objective
Perform statistical hypothesis tests to determine whether patient characteristics and clinical measures are associated with hospitalization outcomes. The project must demonstrate correct test selection, assumption checking, and interpretation suitable for healthcare decision-making.

## Key Questions to Answer
- Which numeric clinical variables differ significantly between hospitalized vs non-hospitalized groups?
- Which categorical attributes are significantly associated with hospitalization status?
- Are findings statistically significant, and are they practically meaningful?

## Required Workflow Deliverables
1. **Data ingestion**
   - Load dataset and verify schema, shape, and types

2. **Data quality checks**
   - Check missing values, duplicates, impossible values (if applicable)

3. **Exploratory analysis**
   - Summary statistics by group
   - Visual diagnostics (histograms, boxplots, group comparisons)

4. **Hypothesis test design**
   - For each variable, define:
     - Null hypothesis (H0)
     - Alternative hypothesis (H1)
   - Choose appropriate test:
     - Two-sample t-test (numeric)
     - Chi-square (categorical)
     - Non-parametric alternative if assumptions fail (optional but acceptable)

5. **Assumption checks**
   - Evaluate normality and variance considerations for numeric tests
   - Confirm contingency table validity for chi-square tests

6. **Execution + reporting**
   - Report p-values and significance decisions at α = 0.05
   - Include effect size or group differences when possible
   - Summarize results in a clean table (variable, test, p-value, decision)

7. **Interpretation**
   - Translate results into healthcare-relevant statements:
     - direction of difference/association
     - implications for screening, intervention, or operational planning

## Success Criteria
- Correct mapping of variable types to hypothesis tests
- Transparent assumptions and defensible methodology
- Clear, decision-oriented interpretation of results (not just p-values)
