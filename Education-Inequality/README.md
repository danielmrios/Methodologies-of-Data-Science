# Education Inequality Project

This project addresses the inequality of educational opportunity in U.S. high schools. 

Here we will focus on average student performance on the ACT or SAT exams that students take as part of the college application process. Is school performance predicted by socioeconomic factors?

## Data
The primary data set is the EdGap data set from EdGap.org. This data set from 2016 includes information about average ACT or SAT scores for schools and several socioeconomic characteristics of the school district: https://www.edgap.org/#5/37.875/-95.977

Located: EdGap_data.xlsx

The secondary data set is basic information about each school from the National Center for Education Statistics: https://nces.ed.gov/ccd/pubschuniv.asp

Located: https://drive.google.com/file/d/1HvW2w-o2XZzCm4KTvnb1Bb3BvoAa14BP/view?usp=sharing

## Data Preparation
Data preparation involved exploring the data for the question, addressing outliers, and creating a train-test split for analysis.

Notebook: Education_Data_Preparation (Located in main repository)

Clean training data: x_train.csv, y_train.csv

Clean testing data: x_test.csv, y_test.csv

## Data Analysis
Data analysis involved exploring the updated dataframe, deriving correlation of variables, and conducting regression modeling to predict ACT score

Analysis book: education_inequality_analysis (Located in main repository)
