# OB-StatSketch — Complete Features

**An Interactive, Offline Inferential Statistics Learning and Graphing Lab**

**Version: 2.8**

OB-StatSketch is a free, standalone application for learning statistics, performing inferential analyses, and producing statistical graphs. It combines an interactive Learning Hub, individual statistical tools, and a Thesis Playground for research analysis in one offline HTML file.

Version 2.8 includes:

- **28 main statistical tools**
- **17 direct-entry analysis options in Thesis Playground**
- **13 research graph types**
- **12 learning chapters and 39 progressive lessons**
- **9 probability distribution choices**
- **3 visual themes**

Some analyses are available in both the main tools and Thesis Playground. These figures describe the available tools and entry points, not the number of distinct statistical methods.

## 1. Comprehensive Statistics Learning Hub

A structured educational program with **12 chapters and 39 progressive lessons**, moving from foundational concepts to more advanced inference.

### Topics

1. Foundations of inferential statistics
2. Probability and probability distributions
3. Sampling distributions and the Central Limit Theorem
4. Point estimation and confidence intervals
5. Hypothesis testing and statistical decision-making
6. Comparing population means
7. Analysis of variance and experimental design
8. Categorical data and chi-square inference
9. Correlation and regression
10. Nonparametric statistical methods
11. Statistical power and sample-size planning
12. Resampling, Bayesian concepts, and multiple testing

### Learning capabilities

- Guided visual lessons and Full Reading mode
- Interactive graphs, live sliders, and resettable experiments
- Step-by-step mathematical explanations and worked examples
- Guidance on assumptions, interpretation, and common misconceptions
- Knowledge checks and numerical practice with feedback
- Expandable chapters, lesson search, and bookmarks
- Individual learning progress tracking
- Links to relevant calculators, including examples with values already populated

> Advanced topics covered in lessons are not necessarily available as full research calculators.

## 2. Thesis Playground

A dedicated research workspace with a direct workflow:

**Choose an analysis → Enter values → Click Draw → Review the results and graph**

Dataset import is optional. Depending on the method, researchers can enter summary statistics, individual observations, paired measurements, or frequency tables.

### Research Roadmap

Record the research question, hypothesis, study design, and research notes.

### Data & Codebook

Import CSV data, preview records, and inspect variables.

### Quick Analysis

Access **17 direct-entry analysis options**:

1. One-sample mean confidence interval
2. Welch’s independent two-sample t-test
3. Paired t-test
4. One-proportion Wilson confidence interval
5. Two-independent-proportion Z test
6. Pearson correlation
7. Spearman rank correlation
8. Simple linear regression
9. Multiple linear regression
10. One-way ANOVA
11. Tukey HSD / Tukey–Kramer comparisons
12. Chi-square goodness-of-fit test
13. Chi-square independence test
14. Cronbach’s alpha
15. Anderson–Darling normality analysis
16. Sample-size planning for estimating a mean
17. Forest plotting of supplied effect estimates and confidence intervals

### Graph Gallery

Create **13 types of research graphs** from manually entered or supported imported data.

### Results & Reports

Retain analysis results, review calculation history, and export research reports, result summaries, and project files.

### Method Guide

Get preliminary method suggestions based on the research objective, outcome type, and study design.

Thesis Playground has its own collapsible navigation section, with direct submenu links to analyses and graph types.

## 3. Confidence Interval Calculators

- One population mean using Z or Student’s t
- One population proportion using Wilson or normal/Wald intervals
- Difference between two independent means using Welch’s t
- Difference between two means using Z when population standard deviations are known
- Mean difference for paired observations
- Difference between two independent proportions using a normal approximation
- Population variance and standard deviation using chi-square critical values

Outputs include interval limits, critical values, standard errors, margins of error where applicable, calculation steps, and graphical interpretation.

## 4. Distribution Plotter & Critical Values

The dedicated Distribution Plotter supports **nine distribution choices**:

| Distribution | Parameters |
| --- | --- |
| Normal | Mean and standard deviation |
| Standard Normal Z | Fixed mean of 0 and standard deviation of 1 |
| Student’s t | Degrees of freedom |
| Chi-square | Degrees of freedom |
| F | Numerator and denominator degrees of freedom |
| Uniform | Minimum and maximum |
| Exponential | Rate |
| Binomial | Number of trials and success probability |
| Poisson | Expected count |

### Plotting capabilities

- Overlay up to three distributions with separate parameter settings.
- Display continuous density curves or discrete probability bars.
- Shade left tails, right tails, central regions, intervals between values, or both tails.
- Calculate probabilities from supplied cutoffs.
- Calculate critical values from supplied probabilities.
- Distinguish significance levels and tail probabilities from numerical x-axis cutoffs.
- Display probability and critical-value cards matching the selected settings for the primary distribution.
- Load five example presets, including comparisons of Z and Student’s t.
- Export graphs as PNG or SVG.

### Additional references

- Z, t, chi-square, and F critical-value calculator
- Normal-versus-t comparison graphs
- Offline Student’s t critical-value tables
- CSV export for supported reference tables

Critical values are calculated locally without requiring external statistical tables.

## 5. Hypothesis Testing

- One-sample Z-test
- One-sample t-test
- Welch’s independent two-sample t-test
- Paired t-test in Thesis Playground
- Two-independent-proportion Z test in Thesis Playground
- One-sided and two-sided alternatives in supported calculators
- Test statistics and p-values
- Critical regions and rejection boundaries
- Significance levels and statistical decisions
- Explanations of Type I and Type II errors

Interpretations distinguish statistical evidence from practical importance and identify the assumptions relevant to each method.

## 6. ANOVA & Multiple Comparisons

- One-way ANOVA for independent groups
- Balanced two-way factorial ANOVA
- Main effects and interaction analysis
- ANOVA tables, F statistics, degrees of freedom, and p-values
- Group comparison graphs
- Holm-adjusted pairwise comparisons
- **Tukey HSD and Tukey–Kramer pairwise comparisons**

### Tukey comparison capabilities

- Analyze **2–12 independent groups**.
- Enter raw observations or summary statistics: group mean, sample standard deviation, and sample size.
- Use Tukey HSD for equal sample sizes and Tukey–Kramer for unequal sample sizes.
- Calculate pairwise mean differences, adjusted p-values, and simultaneous confidence intervals.
- Display pooled mean square error, error degrees of freedom, and the studentized-range critical value.
- Draw pairwise difference intervals against a zero-reference line.
- Transfer group observations directly from one-way ANOVA results.
- Export comparison tables as CSV.
- Export comparison graphs as PNG or SVG.
- Review method-specific assumptions and educational explanations.

> Both Tukey methods assume independent observations, normal within-group errors, and a common population variance. Tukey–Kramer accommodates unequal sample sizes, not unequal population variances.

## 7. Categorical Data Analysis

- Chi-square goodness-of-fit testing
- Chi-square independence testing for 2×2 tables
- Larger row-by-column contingency tables in Thesis Playground
- Observed and expected frequency calculations
- Chi-square statistics, degrees of freedom, and p-values
- Observed-versus-expected bar charts
- Contingency-table residual heatmaps
- Warnings about low expected frequencies and approximation limitations

## 8. Nonparametric Statistics

- Mann–Whitney U test for independent groups
- Wilcoxon signed-rank test for paired observations
- Kruskal–Wallis H test for multiple independent groups
- Spearman rank correlation in Thesis Playground
- Rank-based results, supporting graphs, and interpretation guidance

These implementations use documented p-value approximations. Method-specific cautions are provided rather than presenting every result as an exact test.

## 9. Correlation & Regression

- Pearson correlation with a significance test and approximate confidence interval
- Spearman rank correlation with an approximate significance test
- Simple linear regression
- **Multiple linear regression using ordinary least squares with 2–5 numerical predictors**
- Regression coefficient estimates
- Standard errors, t statistics, p-values, and coefficient confidence intervals
- R² and adjusted R²
- Overall model F-test and root mean square error for multiple regression
- Scatterplots with fitted lines
- Pearson correlation heatmaps
- Coefficient confidence-interval plots

The application includes guidance on model assumptions and cautions against interpreting association as proof of causation.

## 10. Normality Testing & Distribution Diagnostics

- Normal Q-Q plots
- **Anderson–Darling normality statistic and approximate p-value**
- User-selected significance level
- Explanatory interpretation of normality results
- Standalone normality analysis in Thesis Playground
- Histograms and descriptive summaries
- Visual outlier inspection
- Selectable box-plot quartile conventions:
  - Linear interpolation — type 7
  - `(n + 1) × p` interpolation — type 6

The selected quartile convention is identified in the output.

For Anderson–Darling testing, this implementation reports a p-value only with at least eight observations and warns about repeated values.

> A large normality-test p-value does not prove normality. Diagnostic results should be interpreted alongside the study design, graphical evidence, and assumptions of the intended analysis.

## 11. Questionnaire Reliability & Survey Graphs

- **Cronbach’s alpha** for internal consistency
- Corrected item–total correlations
- Item variance summaries
- Respondent and item counts
- Item–total correlation graphs
- Five-category diverging Likert charts

Questionnaire calculations use individual response data.

> Cronbach’s alpha alone does not establish questionnaire validity or unidimensionality.

## 12. Research Graph Gallery

Thesis Playground provides **13 graph types**:

| Graph | Purpose |
| --- | --- |
| Histogram | Examine the distribution of numerical observations |
| Grouped box plots | Compare medians, spread, and potential outliers |
| Individual-value plots | Show the actual observations within groups |
| Violin plots | Compare smoothed group distributions |
| Normal Q-Q plots | Examine consistency with a normal distribution |
| Scatterplots with fitted lines | Explore numerical relationships |
| Paired trajectories | Show before-and-after measurements by individual |
| Group mean interval plots | Compare means and confidence intervals |
| Correlation heatmaps | Display Pearson correlations among variables |
| Observed-versus-expected bars | Compare categorical frequencies |
| Diverging Likert charts | Summarize five-category questionnaire responses |
| Contingency-table residual heatmaps | Examine departures from expected counts |
| Effect-estimate forest plots | Present supplied estimates and confidence limits |

Researchers can enter values directly, edit figure titles and subtitles, enlarge graphs, and export PNG or SVG files.

Analysis-specific figures, including Tukey comparison plots, are also available from their calculators.

> Forest plots display supplied estimates and confidence limits. They do not perform a pooled meta-analysis.

## 13. Sample Size & Statistical Power

- Sample-size calculations for estimating means and proportions in supported tools
- Required sample size for a specified margin of error
- Margin-of-error versus sample-size graphs
- Z-test power calculations
- Approximate two-group power and sample-size planning
- Interactive exploration of significance level, effect size, and sample size
- Confidence-interval coverage simulations

Planning outputs identify the assumptions and approximations used.

## 14. Random Number & Trial Randomization Lab

- Random integer generation
- Random decimal generation
- User-defined result counts and numerical ranges
- Unique values without replacement
- Participant ID shuffling
- Balanced two-arm assignments
- Reproducible seeds displayed with the results
- Copy-to-clipboard functionality
- CSV export

The same seed and settings reproduce the same sequence.

> The randomizer is intended for educational and general experimental use. It is not a validated regulated clinical-trial randomization system.

## 15. Data & Design Studio

- CSV import
- Direct data entry and pasting
- Dataset preview
- Numerical variable selection
- Descriptive statistics
- Data transfer into supported calculators
- Histogram and Q-Q inspection
- Visual outlier inspection
- Experimental run-order randomization
- Randomized block designs
- Two-level factorial design generation
- Statistical method-selection assistance

Users can work with individual observations or use summary statistics in calculators that support them.

## 16. Interactive Statistical Practice

- Guided worked examples
- Numerical calculation exercises
- Immediate answer feedback
- Step-by-step explanations
- Live sliders and graph updates in educational experiments
- Reset controls for restoring teaching examples
- Classroom worksheets
- Separate instructor answer keys
- Connections between lessons, experiments, calculators, and practice

## 17. Statistical References & Help

- Searchable glossary with more than 70 statistical symbols and terms
- Explanations of x̄, μ, σ, s, n, α, β, degrees of freedom, p-values, and related notation
- Clickable symbol explanations
- Input information icons
- Formula references
- Statistical critical-value tables
- **The Science Behind** lessons in Guided and Full Reading modes
- **What is new?** page covering v2.8 and the previous three releases: v2.7, v2.6, and v2.5
- **Why OB-StatSketch was created?** page containing the project’s origin story and author biography

## 18. Exporting, Reporting & Reproducibility

- Download graphs as PNG images.
- Download scalable SVG graphs.
- Export supported results, tables, and randomization outputs as CSV.
- Generate printable analysis reports containing numerical results, formulas, graphs, and interpretations.
- Retain Thesis Playground analysis history.
- Export HTML research reports.
- Export CSV summaries of retained research results.
- Save and reopen JSON project files containing supported data and analysis settings.
- Include the embedded icon, application version, and LinkedIn address in exported graphs.

> Project exports can contain entered research data. Store and share these files according to the confidentiality requirements of your research.

## 19. Customizable Appearance

Three selectable themes apply to the interface and exported graphs:

- **Classic:** Blue and teal.
- **Zest:** Bright Electric Citrus colors with light backgrounds.
- **Pink Lemonade:** Light Blush & Berry colors with darker text and graph accents.

## 20. Offline & Portable Architecture

- Entire application contained in one HTML file
- Embedded branding and logo
- No installation required
- No account required
- No server required
- No external JavaScript libraries or stylesheets required
- Local statistical calculations, graph generation, and data processing
- Offline access to learning materials, references, and help pages
- Responsive layouts for desktop and mobile screens

External reference, GitHub, and LinkedIn links require an internet connection only when opened.

Local progress and preference storage depend on browser support and settings.


## 21. Navigation & Usability

- Hamburger navigation menu
- Collapsible main-menu sections
- First navigation section expanded by default
- Nested Thesis Playground links to workspaces, analyses, and graph types
- Expand-all and collapse-all icon controls
- Expandable learning chapters
- Searchable learning content and bookmarks
- Calculator inputs preserved when switching tools
- Small red **New** badges outside dropdowns
- Clear analysis names without “New” appended to dropdown options
- Input validation, calculation steps, and explanatory results

## Scope & Interpretation

OB-StatSketch supports the methods listed above. It is not a complete implementation of every method introduced in the Learning Hub.

Advanced methods such as structural equation modeling, mixed-effects models, survival analysis, and full meta-analysis are not included in version 2.8.

Users should review each method’s assumptions and limitations before interpreting results. Summary statistics alone cannot establish independence, reveal outliers, or describe the full distribution of the underlying observations.

## Who Is OB-StatSketch For?

**Students:** Learn inferential statistics through worked examples and interactive visualizations.

**Educators:** Demonstrate concepts, explore parameter changes, and prepare classroom exercises.

**Researchers:** Run supported analyses, examine uncertainty, and prepare graphs and reports for research papers and dissertations.

**Self-learners:** Study statistics without installing specialized statistical software.

## Getting Started

1. Download `OB-StatSketch_v2.8_Offline.html`.
2. Open the file in a modern web browser.
3. Begin with the Learning Hub, select an individual statistical tool, or open Thesis Playground.
4. Enter values or import data where supported.
5. Draw graphs, review calculations, and export results.

No installation or internet connection is required for the application’s calculations and learning materials.

## Technology

OB-StatSketch is built using **HTML5, CSS3, JavaScript, and SVG**.

It is distributed as a single self-contained HTML file for offline use.

## Developer

**Omar M. Badreldin**

[LinkedIn](https://www.linkedin.com/in/omarbadr) | [GitHub](https://github.com/ByOmarBadr)

*Vibe coded with ❤️ for Data and AI by Omar M. Badreldin*
