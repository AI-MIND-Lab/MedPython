# MedPython Learning Resources

Welcome to the MedPython Learning Resources!

This page provides free video tutorials to support your Python learning and help you apply programming concepts to biomedical research. Use these videos alongside the course notebooks, and try the exercises yourself before viewing the solutions.


### 1. Google Colab for Python Beginners

[▶ Watch YouTube Tutorial](https://youtu.be/5sgJsCah9bs)

An introduction to Google Colab, a free, browser-based environment for writing and running Python code without installing software.

### 2. Python Data Types Explained Visually

[▶ Watch YouTube Tutorial](https://youtu.be/0uY2qNAsAWs)

A visual introduction to Python’s core data types, including numbers, strings, lists, tuples, sets, and dictionaries.


### 3. Python Lists, Tuples, Sets, and Dictionaries: When to Use Each

[▶ Watch YouTube Tutorial](https://youtu.be/h-zcj4DmqHk)

Compare Python’s main collection types and learn when to use each, for example, to organize DNA sequences, gene annotations, or experimental results.

### 4. Python Dictionaries

[▶ Watch YouTube Tutorial](https://youtu.be/4t10v2QmTHU)

Learn about organizing and accessing data using key–value pairs. Connect this concept to storing gene names with their sequences or expression levels.

### 5. Nested Data Structures: How Python Organizes Complex Data

[▶ Watch YouTube Tutorial](https://youtu.be/o8jpNsXBBZk)

Explore structures that contain other structures, such as lists of dictionaries. Relate this to the course examples that combine gene names, sequences, and expression levels.

### 6. Practice Problems: Python Lists vs. Tuples vs. Sets

[▶ Watch Practice Problems](https://youtu.be/F1cvQYQ2Qts)

Practice choosing and working with lists, tuples, and sets. Pause each problem and attempt your own solution before continuing.

### 7. Python Functions: Three Key Practice Problems

[▶ Watch Practice Problems](https://youtu.be/hFIo05dSD0U)

Reinforce your understanding of functions through practice. Apply the same approach to reusable tasks such as calculating GC content or counting nucleotides.

### 8. Python F-strings

[▶ Watch YouTube Tutorial](https://youtu.be/H_TPIAEJl68)

Learn how to insert variables into text and format output, for example, displaying a gene name or a GC-content percentage.

### 9. Practice Problems: Python For Loops

[▶ Watch Practice Problems](https://youtu.be/TobtUSykK64)

Practice using loops to process collections. Connect this to examining each nucleotide in a sequence or calculating results for multiple genes.

### 10. Python Nested Loops

[▶ Watch YouTube Tutorial](https://youtu.be/ck1AzCDs0ss)

Explore how a loop inside another loop works. A biomedical example is processing several DNA sequences and then examining the nucleotides within each sequence.

> **Note:** Nested loops describe repeated operations; nested data structures describe how data is organized.

### 11. Python zip() Function

[▶ Watch YouTube Tutorial](https://youtu.be/1cG6RpAH9Xk)

Learn how to pair corresponding elements from multiple collections, for example, matching gene names with their sequences.

### 12. List Comprehensions

[▶ Watch YouTube Tutorial](https://youtu.be/DUnY6l482Lk)

Explore a concise way to create lists from existing collections. Connect this to calculating sequence lengths or filtering biological data.

### 13. Python Error Handling

[▶ Watch YouTube Tutorial](https://youtu.be/XN3udSTGAOM)

Learn the basics of handling errors so a program can respond appropriately to unexpected input. Relate this to checking for empty or invalid DNA sequences.

### 14. NumPy Arrays, Indexing, and Numerical Operations

[▶ Watch YouTube Tutorial — freeCodeCamp / Keith Galli](https://www.youtube.com/watch?v=QUT1VHiLmmI)

Learn how to create arrays, inspect their shapes, select rows and columns, and perform numerical calculations. Focus on indexing, statistics, and Boolean filtering, then apply these ideas to the notebook’s gene expression and patient temperature tables.

**Try it:** Select one patient’s measurements and one measurement time across all patients. Predict each result’s shape before running the code.

### 15. Mean, Variance, and Standard Deviation

[▶ Watch Visual Explanation — StatQuest](https://youtu.be/SzZ6GpcfoQY)

Build an intuitive understanding of averages and variability before calculating them in Python. Connect this to patients whose measurements have the same mean but different amounts of variation.

**Course connection:** Follow the notebook’s distinction between `ddof=0` and `ddof=1`. Use the convention requested in each exercise.

### 16. Creating and Customizing Plots with Matplotlib

[▶ Watch YouTube Tutorial — Corey Schafer](https://www.youtube.com/watch?v=UO98lJQ3QGI)

Learn to create line plots and customize their appearance. Apply these ideas to plotting temperature over time with informative labels, units, titles, and legends.

**Try it:** Plot P002 and P003 together. Explain why their equal means do not describe their different patterns over time.

### 17. Scatter Plots

[▶ Watch YouTube Tutorial — Corey Schafer](https://www.youtube.com/watch?v=zZZ_RCwp49g)

Learn to visualize relationships between two numerical variables. Connect this to comparing paired biological measurements and examining patterns alongside a correlation coefficient.

**Remember:** A visible association does not establish causation. Check the plotted data rather than relying only on a numerical summary.

### 18. Histograms

[▶ Watch YouTube Tutorial — Corey Schafer](https://www.youtube.com/watch?v=XDv6T4a0RNc)

Explore how histograms group measurements into bins to show their distribution. Compare this with a line plot, which preserves the order of measurements over time.

**Try it:** Change the number of bins and describe how the appearance changes. Do not interpret a plotting choice as a change in the underlying measurements.

### 19. Understanding Box Plots

[▶ Watch Visual Explanation — StatQuest](https://youtu.be/fHLhBnmwUM0)

Understand how box plots summarize a distribution. Relate this to comparing patients’ temperature measurements, while remembering that a box plot does not preserve time order.

Use the course notebook for the Python implementation and for overlaying individual measurements.

**Remember:** A point beyond a box plot’s whiskers does not, by itself, establish a measurement error or justify deleting the observation.

### 20. Drawing and Interpreting Heatmaps

[▶ Watch Visual Explanation — StatQuest](https://youtu.be/oMtDyOn2TCc)

Explore how heatmaps communicate patterns in numerical tables. Connect this to displaying patients as rows and measurement times as columns.

This video supports interpretation. Follow the notebook’s `imshow()` example for implementation, including tick labels, a shared color scale, and a labeled colorbar.

**Try it:** Find the unusual hour-8 measurement for P005. Explain what the color shows and what it cannot tell you about the cause.

### 21. Covariance and Pearson Correlation

[▶ Covariance — StatQuest](https://youtu.be/qtaqvPAeEJY)

[▶ Pearson Correlation — StatQuest](https://youtu.be/xZ_z8KWkhXE)

Understand how two measurements vary together and how Pearson correlation summarizes a linear relationship. Relate these explanations to the notebook’s paired numerical data.

**Remember:** Correlation does not establish causation, and a correlation near zero does not rule out a nonlinear relationship.

### 22. Introduction to pandas DataFrames and Series

[▶ Watch YouTube Tutorial — Corey Schafer](https://youtu.be/zmdjNSmRXF4)

Learn how pandas organizes tabular data using Series and DataFrames. Practice selecting rows and columns, accessing variables, and exploring datasets.

**Course connection:** Apply these concepts to the notebook's gene expression datasets, including selecting gene names, expression levels, and sample measurements.

### 23. Importing and Exporting CSV Files with pandas

[▶ Watch YouTube Tutorial — Corey Schafer](https://youtu.be/N6hyN6BW6ao)

Learn how to read and save CSV files using pandas, along with other common data formats.

**Try it:** Load a biomedical CSV file using `pd.read_csv()`, inspect its first five rows, and save a modified version using `df.to_csv()`.

### 24. Cleaning Data and Handling Missing Values

[▶ Watch YouTube Tutorial — Corey Schafer](https://youtu.be/KdmPHEnPJPs)

Learn how to identify missing values, convert data types, and clean datasets before analysis.

**Course connection:** Practice using `isna()`, `dropna()`, and `pd.to_numeric()` with biomedical measurements.

**Remember:** Replacing missing clinical measurements with zero may introduce misleading results. Choose a missing-data strategy based on what the missing values represent.

### 25. Grouping and Aggregating Data with pandas

[▶ Watch YouTube Tutorial — Corey Schafer](https://youtu.be/txMdrV1Ut64)

Learn how to group observations and calculate descriptive statistics using pandas.

**Try it:** Use `groupby()` and `agg()` to calculate sample counts, means, and standard deviations for each treatment group in the course dataset.

### 26. Understanding t-Tests and ANOVA

[▶ Watch Visual Explanation — StatQuest](https://youtu.be/R7xd624pR1A)

Understand how t-tests and ANOVA compare group means and how these statistical methods relate to linear models.

**Course connection:** Review the notebook's paired t-test, Welch independent t-test, and one-way ANOVA examples.

**Remember:** Select the statistical test based on the study design. Paired measurements from the same participants are different from measurements collected from independent groups.

### 27. Chi-Square Test of Independence

[▶ Watch Visual Explanation — Khan Academy](https://www.khanacademy.org/math/statistics-probability/inference-categorical-data-chi-square-tests/chi-square-tests-for-homogeneity-and-association-independence/v/chi-square-test-association-independence)

Learn how the chi-square test evaluates associations between categorical variables using observed and expected frequencies.

**Course connection:** Apply this concept to the notebook's responder analysis, where participants are classified as responders or nonresponders across three treatment groups.

**Try it:** Construct a contingency table using `pd.crosstab()` and perform the chi-square test using `stats.chi2_contingency()`.

### 28. Multiple Linear Regression

[▶ Watch Visual Explanation — StatQuest](https://youtu.be/zITIFTsivN8)

Learn how multiple linear regression examines the association between an outcome and several predictors simultaneously.

**Course connection:** Review the notebook's regression model predicting follow-up blood pressure using treatment group, baseline blood pressure, and age.

**Remember:** Regression coefficients describe associations conditional on the included predictors. Causal interpretation requires additional assumptions and an appropriate study design.

## Suggested Study Approach

1. Review the relevant course notebook section.
2. Watch the matching tutorial.
3. Pause and predict what the code will do.
4. Run a similar example in Google Colab.
5. Try the practice problems independently.
6. Explain your results in plain language, including what the data cannot establish.

