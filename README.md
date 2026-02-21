# IPL Toss Advantage: A Quantitative Study (1,000+ Matches)

## Project Overview
This study analyzes the "Toss Advantage" in the IPL using a dataset of 1,000+ matches. The goal was to determine if winning the toss is a genuine predictor of success or a statistical myth.

## Technical Workflow
- **Data Engineering:** Architected a pipeline to parse and clean 1,000+ nested JSON files using **Power Query**.
- **Data Integrity:** Applied a frequency threshold filter (n > 10) to remove high-variance outliers from minor venues.
- **Statistical Analysis:** Calculated league-wide means and standard deviations to measure venue-specific volatility.

## Key Results
- **League-Wide Mean:** 50.7% (The toss is statistically neutral at a macro level).
- **The Chasing Bias:** Teams winning the toss and choosing to **field** have a **53.1%** win rate, vs **46.3%** for batting first.
- **Venue Volatility:** A **Standard Deviation of 0.098** proves the toss impact is highly dependent on local environmental factors (dew, pitch wear).

## Repository Contents
- `IPL ANALYSIS.xlsx`: Full dataset, Power Query steps, and Pivot Tables.
- `Quantitative Analysis of the IPL.docx`: Final research report and executive summary.

## Technical Tools
- **Tools:** Microsoft Excel (Power Query, Pivot Tables)
- **Concepts:** Standard Deviation, Data Cleaning, JSON Parsing, Statistical Variance.
