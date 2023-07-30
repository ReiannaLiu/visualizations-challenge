# visualizations-challenge

This repository contains an analysis of a mouse study dataset conducted for testing different drug regimens. The dataset includes information about the tumor volume and treatment regimens for various mice in the study. The main goal of this analysis is to gain insights from the data and visualize the results using various plots and charts.

1. Prepare the Data
\
Before diving into the analysis, we will first prepare the data by merging the mouse_metadata and study_results DataFrames into a single DataFrame. We will also identify and remove any duplicate time points associated with a mouse ID to ensure data accuracy.

2. Generate Summary Statistics
\
In this step, we will calculate summary statistics for each drug regimen. The statistics will include mean, median, variance, standard deviation, and SEM of the tumor volume. We will create a DataFrame that presents the results with the drug regimen names in the index column.

3. Create Bar Charts and Pie Charts
\
Next, we will generate bar charts and pie charts to visualize the distribution of mice across different drug regimens and genders. The bar charts will show the total number of mice for each drug regimen, while the pie charts will display the distribution of female versus male mice in the study.

4. Calculate Quartiles, Find Outliers, and Create a Box Plot 
\
We will focus on four promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. For each of these regimens, we will calculate the final tumor volume for each mouse. Then, we will determine the quartiles, interquartile range (IQR), and identify potential outliers for each regimen. To visualize the distribution of final tumor volumes, we will create a box plot with highlighted outliers.

5. Create a Line Plot and a Scatter Plot 
\
To analyze the tumor volume over time for a specific mouse treated with Capomulin, we will create a line plot. Additionally, we will generate a scatter plot that depicts the relationship between mouse weight and average observed tumor volume for the entire Capomulin treatment regimen.

6. Calculate Correlation and Regression 
\
For the Capomulin treatment regimen, we will calculate the correlation coefficient between mouse weight and average tumor volume. Additionally, we will perform a linear regression analysis to model the relationship between these variables. The regression model will be plotted on top of the scatter plot.

7. Final Analysis 
\
In this section, we will provide a comprehensive analysis of the mouse study data, including insights gained from the generated plots and charts. We will summarize key findings and observations from the analysis.

Feel free to explore the code and visualizations in this repository to gain a deeper understanding of the mouse study dataset and its results. If you have any questions or feedback, please don't hesitate to reach out!
