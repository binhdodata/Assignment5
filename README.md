# Assignment5
Project Description
In this project, we analyze data from an animal study conducted by Pymaceuticals, Inc., a pharmaceutical company specializing in anti-cancer medications. The study aimed to screen potential treatments for squamous cell carcinoma (SCC), a form of skin cancer. The dataset contains information on 249 mice with SCC tumors who received various drug regimens. The study spanned 45 days, during which tumor development was observed and measured. Our goal is to generate tables, figures, and summary statistics to provide a comprehensive analysis of the study results.

Files
mouse_metadata.csv: Contains metadata for each mouse, including Mouse ID, Drug Regimen, Sex, Age (in months), and Weight (in grams).
study_results.csv: Contains the observed tumor volume and timepoint measurements for each mouse at different treatment timepoints.
Installation
Clone the repository to your local machine.
Ensure you have Python 3.x and the following libraries installed:
Pandas
NumPy
Matplotlib
Run the Jupyter Notebook or Python script to perform the analysis.
Usage
Open the Jupyter Notebook file or run the Python script to execute the code cells.
Follow the step-by-step instructions provided in the notebook or script.
Review the generated plots, tables, and summary statistics to gain insights from the data.
Tasks
This project consists of the following tasks:

Data preparation: Merge the mouse metadata and study results into a single DataFrame, handle duplicate data, and create a cleaned DataFrame.
Generate summary statistics: Calculate mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.
Create bar charts and pie charts: Visualize the total number of mice and timepoints for each drug regimen using bar charts, and display the distribution of female and male mice using pie charts.
Calculate quartiles, find outliers, and create a box plot: Calculate quartiles and interquartile range (IQR), identify potential outliers, and create a box plot showing the final tumor volume distribution for different treatment regimens.
Create a line plot and a scatter plot: Generate a line plot of tumor volume vs. time point for a single mouse treated with Capomulin, and create a scatter plot of mouse weight vs. average observed tumor volume for the Capomulin regimen.
Calculate correlation and regression: Calculate the correlation coefficient and perform linear regression analysis between mouse weight and average observed tumor volume for the Capomulin regimen.
Requirements
The project requirements include:

Data preparation: Merging datasets, handling duplicates, and creating a cleaned DataFrame.
Summary statistics: Calculation of mean, median, variance, standard deviation, and SEM of tumor volume.
Visualization: Creation of bar charts, pie charts, box plots, line plots, and scatter plots.
Quartiles and outliers: Calculation of quartiles, identification of potential outliers, and box plot generation.
Correlation and regression: Calculation of correlation coefficient and linear regression analysis.