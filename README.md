# Data_Analysis_Final_Project
**Is a file malicious?** <br>
**By: Nicole Shklover and Ariel Hedvat**<br><br>

This was the final project for a Statistics and Data Analysis with R course at Tel Aviv University. <br><br>

In this project we handeled the different phases of a data analysis project: <br>
1. Data Import (reading the data into R).
2. Data Tidying (arranging the data into something we can work with)
3. Understanding the data:
  a. Transforming variables.
  b. Visualizing (using ggplot2 to show distribution of variables, relationships between variables, and to hypothesize).
  c. Modelling: using a few of the tools we have learned during the course (like hypothesis testing, regression, analysis of variance, etc.) to examine our hypothesis.
4. Communicating our findings via a written report.


We were provided with information regarding various features of Portable Executable (PE) files and were asked to create a classifier capable of predicting the likelihood of a given file being malicious. This prediction is supposed to be based on a dataset of 60,000 files that had already been categorized.<br>
Portable Executable (PE) files are executable file formats used in various operating systems. The term "Portable Executable" signifies that the file format is not tied to a specific architecture, making it versatile across different systems.<br>
Our process involved data analysis, preprocessing, training multiple models, and ultimately selecting the best one, determined by the highest AUC score (on the validation dataset). <br><br>
Using an AdaBoost classifier, we achieved a test AUC score of 0.8834 and recieved a grade of 91 on the project.
The project's code is implemented using Python in Jupyter Notebook.<br><br>
