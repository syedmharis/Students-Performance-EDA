# Students-Performance-EDA-DM-
DATA MINING Assignment 2 EDA
EDA On Students performance in exams
Performed By Syed Muhammad Haris
Marks secured by the students in college
Main Goal:
To understand the influence and effect of various factors like economic, personal and social on the students performance in exams so you can assist your children in a better way,
Inferences would be :
1. How to imporve the students performance in each test ?
2. What are the major factors influencing the test scores ?
3. Effectiveness of test preparation course?
4. Other inferences

#Which dataset you've selected?
I have selected Student Performance in Exam to perform EDA (Exploratory data 
Analysis) on it.
# What analysis you've done in the starter code?
I have imported the required libraries
import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib. pyplot as plt
After importing I’ve loaded the dataset into a variable called df. Then I have 
examined does the dataset contains Null values. After that I looked the 
summary of the dataset and examined the data type of each column in my 
Dataset.
Then I performed my Preprocessing Part. First, I examined the number of rows 
and columns. To manage noisy data in the data set I have dropped the rows 
that have any Null Values now time to start EDA (Exploratory Data Analysis).
The Analysis done by me contains:
1) Analysis of Gender of the students.
2) How to improve the students’ performance in each test?
3) Analysis of what are the major factors influencing the test scores.
4) Analysis on student performance based on their religion.
5) Analysis Effectiveness of test preparation course.
6) Analysis of passed students in each subject.
7) Analysis of status of courses whether courses are completed before 
examination or not.
8) Analysis of how parents' education affects students' score
9) individual score of three subject by gender.

# What information you got?
The information I have derived from my Analysis is given further below:
1) There are more female students than male students.
2) Group c has the highest number of students according to ethnicity.
3) 677 students are pass in math’s and 323 are fail.
4) 700 students are pass in reading and 254 fail.
5) 719 are pass in writing.
6) Students who passed all the subjects are 719.
7) We obtain the following grades based on percentages.
F 281
B 261
C 228
A 198
D 32
8) Most of the students who are pass in writing are also pass in reading.
9) If the parental education is above masters then student is performing good
10) The individual score of three subject by gender is not much scattered
