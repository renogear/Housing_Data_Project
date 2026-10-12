# U.S. Housing Market Explorer

A project exploring how home values change across U.S. metropolitan areas over time.

I’m building this while taking UC Berkeley’s Data 8 course to practice Python, data analysis, visualization, and statistical reasoning. The project will grow from a Jupyter notebook into an interactive housing market dashboard.

## Main Questions

- How have typical home values changed over time?
- How do those changes differ across metro areas?
- What do monthly trends show that annual averages might hide?
- How do housing values relate to income and other local characteristics?

## Planned Features

- Explore all available historical dates.
- Select a metro area and a specific date range.
- Switch between monthly values and annual summaries.
- Compare multiple markets over matching periods.
- Calculate dollar changes and percentage changes.
- Display graphs with explanations of the findings and limitations.

## Data

The starting source is [Zillow Research Housing Data](https://www.zillow.com/research/data/).

We use the metro-level Zillow Home Value Index (ZHVI) for all homes, mid-tier, smoothed and seasonally adjusted.

ZHVI measures typical home values. It is not the sale price of an individual property or the average price of homes sold during a month.

The original dataset contains identifying columns followed by monthly date columns. We will preserve the full monthly history and create organized tables for analysis.

Additional datasets will be introduced when needed. Sources, download dates, coverage, and processing decisions will be documented.

## Progress and Learning Roadmap

### Foundation

- [x] Define the initial project goal.
- [x] Create a GitHub repository and Codespace.
- [x] Load the Zillow dataset in a notebook.
- [ ] Set up and verify the notebook environment in Codespaces.
- [ ] Inspect geographic units, date coverage, and missing values.
- [ ] Organize one metro into Date and Home Value columns.
- [ ] Write a reusable function to organize other metros.

### Analysis and Visualization

- [ ] Calculate annual average values and valid month counts.
- [ ] Flag incomplete years.
- [ ] Calculate monthly and year-over-year changes.
- [ ] Compare changes between annual averages.
- [ ] Create line graphs, bar charts, histograms, and scatterplots.
- [ ] Compare markets using filtering, grouping, pivots, and joins.
- [ ] Write findings supported by the analysis.

### Statistics and Data 8 Concepts

- [ ] Explore randomness, probability, sampling, and bias.
- [ ] Simulate sampling distributions.
- [ ] Test hypotheses using appropriate statistics and p-values.
- [ ] Practice comparing distributions and total variation distance.
- [ ] Study A/B testing, permutation tests, and causal reasoning.
- [ ] Use bootstrap estimates and interpret confidence intervals.
- [ ] Explore standard deviation, normal distributions, the Central Limit Theorem, and sample size.
- [ ] Study correlation, standard units, and linear regression.
- [ ] Evaluate least-squares predictions and residuals.
- [ ] Explore regression inference and prediction intervals.
- [ ] Build and evaluate nearest-neighbor classifiers.
- [ ] Practice conditional probability and Bayes’ rule.

These investigations may use additional housing data or clearly labeled simulations. Each method will be used only when its assumptions fit the question and data.

### Final Product and Extensions

- [ ] Document methods, results, limitations, and setup instructions.
- [ ] Build an interactive dashboard.
- [ ] Introduce pandas and SQL.
- [ ] Explore reproducible data updates and additional prediction models.

## Analysis Guidelines

- Keep monthly data available even when creating annual summaries.
- Distinguish average home values from rates of change.
- Record the number of valid months behind each annual average.
- Compare markets over matching dates.
- Distinguish metro areas from cities and national totals.
- Do not treat consecutive months as independent observations.
- Do not interpret correlation as proof of causation.
- Evaluate prediction methods on data not used for training.

## Workflow

Each checkpoint follows the same process:

1. Define the question.
2. Understand the method.
3. Write and run the code.
4. Check the output.
5. Explain the result and its limitations.
6. Commit the progress to GitHub.
