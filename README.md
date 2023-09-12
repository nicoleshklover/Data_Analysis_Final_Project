# Data_Analysis_Final_Project
**College tuition, diversity and pay** <br>
**By: Nicole Shklover and Ariel Hedvat**<br>
date: 10.06.2022 <br><br>

This was the final project for a Statistics and Data Analysis with R course at Tel Aviv University. <br><br>

In this project we handeled the different phases of a data analysis project:
1. Data Importing (reading the data into R).
2. Data Tidying (arranging the data into something we can work with)
3. Understanding the data: <br>
  a) Transforming variables. <br>
  b) Visualizing (using ggplot2 to show distribution of variables, relationships between variables, and to hypothesize). <br>
  c) Modelling: using a few of the tools we have learned during the course (like hypothesis testing, regression, analysis of variance, etc.) to examine our hypothesis. <br>
4. Communicating our findings via a written report. <br><br>

First we selected a dataset on which we performed the project.<br>


We were provided with information regarding various features of Portable Executable (PE) files and were asked to create a classifier capable of predicting the likelihood of a given file being malicious. This prediction is supposed to be based on a dataset of 60,000 files that had already been categorized.<br>
Portable Executable (PE) files are executable file formats used in various operating systems. The term "Portable Executable" signifies that the file format is not tied to a specific architecture, making it versatile across different systems.<br>
Our process involved data analysis, preprocessing, training multiple models, and ultimately selecting the best one, determined by the highest AUC score (on the validation dataset). <br><br>
Using an AdaBoost classifier, we achieved a test AUC score of 0.8834 and recieved a grade of 91 on the project.
The project's code is implemented using Python in Jupyter Notebook.<br><br>
