# HW3

Since I finished the homework in ipynb, it is difficult to indicate which line is the answer. So I will indicate the number of cells instead.

## Problem 1

Import and explore the data: cell 2
Rank and visualize the states that take in the most federal funding: cell 3, 4, 26

![Vis](https://github.com/stiangithub/HW3/blob/master/pr1.png )

Which states spend the most federal funding per student? Cell 6, 7. DC, Alaska, Vermont, Lousiana, New Mexico are top five states that spend the most federal funding per student.

## Problem 2

Visualize the relationship between school districts’ total revenue and expenditures.
Cell 8, 9, 10
![Vis](https://github.com/stiangithub/HW3/blob/master/pr2.png )

Which states have the most debt per student?
Cell 11
South Dakota has the highest debt per student.

## Problem 3

I choose the ALL_MTH00PCTPROF_1516 from math result. Function impute() in cell 21 is my solution. First, I transfer all NAN to "nan". For items like "50-59", I take the average of them to replace them, like 54.5 to replace "50-59"; for item including an "L", I take the average between 0 and this number to replace it; and for item including an "G", I take the average between it and 100 to replace it; for item with a "PS", I transfer them into "nan" as well.

Then, for all "nan" items, I replace them using numbers generated from a normal distribution where mu is the average and sigma is the std of other numbers of this column. 
![Vis](https://github.com/stiangithub/HW3/blob/master/pr3.png )

## Problem 4

Cell 24, 25.

The money is $8340345450. 

My solution is to cut 15% budget for all districts. And the table is shown as cell 25.

## Problem 5

If we are gonna cut 15% of our budget, I suggest that we should cut 15% for every school district. If we are gonna cut same amout (total cut/number of school district) for each school district, it would be unfair to some small school districts like their remaining budget may be negative. But if we are gonna cut from districts with high budget per students, it still maybe unfair because these districts maybe due to some reasons need more helps from the Federal, cutting their budget may increase the gap between them and other districts. So the most fairest way is to cut same portion from each district.
