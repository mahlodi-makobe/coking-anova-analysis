Coking ANOVA Analysis
This R program analyzes the coking dataset from the ISwR package using a two-way ANOVA model. The goal is to quantify the effect of oven width, temperature, and their interaction on time to coking.

Dataset
The coking dataset contains 18 observations on oven width (3 levels), temperature (2 levels), and time to coking measured in minutes. It can be loaded from the ISwR package.

Analysis
The program conducts an exploratory data analysis, then fits a two-way ANOVA model with time as the response and width, temperature, and their interaction as predictors. Hypothesis testing is performed to assess the significance of effects. Diagnostics check model assumptions.

Files
coking-anova.R : Main R script with analysis
coking-anova-output.pdf : PDF report with analysis summary, plots, tables, interpretation

Usage
To run the analysis:

Install required R packages: ISwR, MASS, car, ggplot2
Set working directory to folder containing the R script
Run coking-anova.R script
Key Findings
Width, temperature, and their interaction all have statistically significant effects on time to coking
Wider widths increase time
Higher temperatures decrease time
The effect of temperature depends on width
