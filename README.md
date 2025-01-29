# Pymaceuticals Inc. Clinical Study Analysis
OverviewThis project analyzes data from a preclinical study conducted by Pymaceuticals, Inc., a pharmaceutical company specializing in anti-cancer treatments. The study examines the effectiveness of different drug regimens in treating squamous cell carcinoma (SCC) in mice. The primary focus is on evaluating the performance of the company's drug of interest, Capomulin, compared to other treatments.

## Dataset
The study includes data on 249 mice treated with various drug regimens over 45 days, tracking tumor development through multiple time points. The dataset consists of two files:
- Mouse_metadata.csv: Contains metadata on each mouse, including gender, age, weight and treatment regimen.
- Study_results.csv: Includes tumor volume measurements and time points for each mouse.

## Objectives
The analysis aims to:
  1. Prepare and clean the dataset.
  2. Generate summary statistics.
  3. Visualize the data using bar charts, pie charts, box plots, line plots, and scatter plots.
  4. Identify potential outliers and analyze tumor volume distributions.
  5. Perform correlation and regression analysis to explore relationships between mouse weight and tumor volume.

## Methodology
**1. Data Preparation**
  - Merged Mouse_metadata.csv and Study_results.csv into a single DataFrame.
  - Identified and removed duplicate time points for the same mouse.
  - Verified the number of unique mice in the cleaned dataset.
**2. Summary Statistics**
  - Calculated mean, median, variance, standard deviation, and standard error of the mean (SEM) for tumor volume across different drug regimens.
**3. Data Visualization**
  - Bar Charts: Displayed the total number of observations for each drug regimen using both Pandas and Matplotlib.
  - Pie Charts: Illustrated the distribution of male and female mice in the study using both Pandas and Matplotlib.
  - Box Plots: Showed the distribution of final tumor volumes for the four most promising treatments (Capomulin, Ramicane, Infubinol, Ceftamin) and identified outliers.
  - Line Plot: Tracked tumor volume changes over time for a selected mouse treated with Capomulin.
  - Scatter Plot: Examined the relationship between mouse weight and tumor volume for the Capomulin treatment group.
**4. Correlation and Regression Analysis**
  - Calculated the correlation coefficient between mouse weight and tumor volume.
  - Performed a linear regression analysis and plotted the regression line on the scatter plot.

## Results
  - Capomulin and Ramicane demonstrated the most promising results in reducing tumor volume.
  - The linear regression model indicated a strong correlation between mouse weight and tumor volume for the Capomulin treatment group.
  - Identified potential outliers in the tumor volume data for certain treatments.
## Technologies UsedPython
  - Pandas
  - Matplotlib
  - NumPy
  - SciPy
## How to Run the Analysis
  - Clone this repository:
     `git clone https://github.com/dagimg16/Data-Visualization.git`
  - Install dependencies:
    `pip install pandas numpy matplotlib scipy`
  - Run the Jupyter Notebook to execute the analysis.

## Acknowledgments
  - Thanks to SMU and my instructors for guiding me through this learning journey!
  - And a big thank you to everyone checking out this project.

## License
  - Feel free to use and modify this script for your own learning.
