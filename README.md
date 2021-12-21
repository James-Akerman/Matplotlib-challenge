# Matplotlib-challenge

## Background

In this Monash University Data Analytics Boot Camp/Trilogy Education Services homework, I imaged I was a data analyst who'd joined a finctional company called Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego. Pymaceuticals specialises in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, I was given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumour growth were treated through a variety of drug regimens. Over the course of 45 days, tumour development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. I was tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also asked for a top-level summary of the study results.

## Tasks

* My tasks included the following

  * Cleaning the data

  * Generating a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumour volume for each drug regimen.

  * Generatinga a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows  the number of total mice for each treatment regimen throughout the course of the study.

  * Generating a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.

  * Calculating the final tumour volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

  * Generating a box and whisker plot of the final tumour volume for all four treatment regimens and highlight any potential outliers in the plot by changing their colour and style, using Matplotlib.
  
  * Selecting a mouse that was treated with Capomulin and generate a line plot of tumour volume vs. time point for that mouse.

  * Generating a scatter plot of mouse weight versus average tumour volume for the Capomulin treatment regimen.

  * Calculating the correlation coefficient and linear regression model between mouse weight and average tumour volume for the Capomulin treatment. Plotting the linear regression model on top of the previous scatter plot.

  * Looking across all previously generated figures and tables and write at least three observations or inferences that can be made from the data
