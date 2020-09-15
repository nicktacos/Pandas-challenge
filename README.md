# Pandas-challenge

# PyCitySchools
## Setup
Import pandas as pd
Read both csv files (school and student) in the Resources file and combine them to make a new csv (school)

## District Summary
Calculate number of schools using .nunique
Calculate the number of students using .count
Calculate the total budget of all the schools using .sum
Calculate the average math and reading scores using .mean
Calculate the percent of students passing math, reading, and overall using .loc as a condition, .mean and dividing by the total number of students
Putting all into a DataFrame using pd.DataFrame and created a library

## School Summary
Set the index to the school name and grouped by the school name using .groupby
Added the category school type
Count Students per school using .count
Added the category school budget
Divide budget by school size to find budget per student
Find averages and percentages like District Summary
Put into DataFrame with pd.DataFrame

## Top Performing Schools
Use the DataFrame above and sort values by Overall Passing % using sort_values and set ascending to False
Use .head() to only post the top 5

## Bottom Performing Schools
Same as the previous exercise except set ascending to True

## Math Scores by Grade
Find averages of math scores by grade and school by using .loc in the grade column to find 9th, 10th, 11th, and 12th. and group them by school name
Find averages by using .mean()
Put into DataFrame

## Reading Scores by Grade
Same as above but use column reading_scores instead of math_scores

## Scores by School Spending
Set bins to a certain spending type
Create bin names 
Create column for the bins by dividing budget by school size
Calculate averages and percentages as above exercises
Put into DataFrame

## Scores by School Size
Same as above but different bins were made according to school size

## Scores by School Type
Group schools by type using .groupby
Calculate averages and percentages as before
