# matplotlib_challenge
Name
Pymaceuticals - The Power of Plots – Kent Rodgers

Description
Pymaceuticals Inc., is  a burgeoning pharmaceutical company based out of San Diego. Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. As a senior data analyst(s) at the company, we have been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. We have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

Key Deliverables
1.	Check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.
2.	Use the cleaned data for the remaining steps.
3.	Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.
4.	Generate a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows  the number of total mice for each treatment regimen throughout the course of the study. These plots should look identical.
5.	Generate a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study. These plots should look identical.
6.	Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.
7.	Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style. All four box plots should be within the same figure. 
8.	Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.
9.	Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.
10.	Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.
11.	Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.

Topline (3 Key) Takeaways
1. Based on initial results the Capomulin and Ramicane drug regimens are promissing
2. Weight and tumor volume are highly correlated, the study assessment should be expanded to ensure participant weight was properly managed in study
3. Ten (10) drug regimens, including Placebo, were evaluated over 45 timepoints
  3a. Twenty-five (25) mice per study except in the Stelasyn regimen which had 24 participants
  3b. Mice participants were nearly evenly divided between male and female
  3c. Additional data should be gathered to ensure participant weight was properly distributed between regimens

Grader ... please note.	There were no statistical outliers in the four targeted drug regimens, Capomulin, Ramicane, Infubinol, and Ceftamin based on two separate calculations. I understand the project required us to flag outliers in the box and whisker chart using green triangles. I placed the flagging logic into the box and whisker charts to show competency and effort but my max timepoint data frame did not support presenting. I double checked my final tumor volume logic but do not see a shortcomiing in the approach. Open to evaluation and feedback. 

Visuals
Please reference the Pymaceuticals Pitchbook for visuals and key takeaways. 

Installation
The Jupyter Notebook was run using Microsoft Edge instead of the recommended Google Chrome
The Notebook was run in the recommended PythonData environment with the following key installs: Pandas, nb_conda_kernels, numpy and scipy

Support
Please reference the Denver University GitLab repository for class materials and instructions.

Roadmap
Not applicable

Contributing
Not applicable

Authors and acknowledgment
I appreciate having a tutor and class instructor available to help me break through on how to better utilize groupby structure for more efficient results.

License
Not applicable

Project status
Project objectives and deliverables achieved. Please note that a for-loop process was not used in the formation of the quartiles and IQR calculations as suggested. These calculations were done on a study-by-study basis. My final efforts at doing the outlier calculations are documented in a separate section to demonstrate effort. 
