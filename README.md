# School_District_Analysis
## Project Overview
The goal of our analysis is to determine the overall passing percentages of the students and determine whether or not there is a relationship between the budget per student. We learned that 9th graders at Thomas High School were reportedly altered, and we would like to delete the math and reading scores from the summary. Because some values are absent, we want to use all of the high school scores so that our overall figures are not affected.

### Results
- District Summary Total

![District_summary_df](https://user-images.githubusercontent.com/105666905/177876360-b17ed922-2618-4f8f-802f-ea78de29f16f.png)

- Thomas High School Summary(note that we removed 9th graders scores from math and reading 'nan')

![Thomas_high_school_summary](https://user-images.githubusercontent.com/105666905/177876553-4682c91c-052a-4133-acd3-19cc7a23f5de.png)

![Thomas_high_school_grades_removed_9th](https://user-images.githubusercontent.com/105666905/177878338-4be6b2bd-13ce-4603-b74e-60e3fef82595.png)


- Schools Summary

![image](https://user-images.githubusercontent.com/105666905/177878583-6735b929-426c-41bb-936a-2d7f96035695.png)

- Spending Ranges(Per Student)

![Spending_ranges_per_student](https://user-images.githubusercontent.com/105666905/177879399-d52357d2-3ff7-40d0-bb22-479e1b703452.png)


- Spending Ranges Bins

![Spending_ranges_per_student_bins](https://user-images.githubusercontent.com/105666905/177879543-45a6c6b1-80bf-44c3-a2ea-fbb231009bee.png)

- School Size

![school_size](https://user-images.githubusercontent.com/105666905/177879957-9c009dd5-deb2-4c29-b169-f3f98e2f3ecd.png)

- School Type

![school_type](https://user-images.githubusercontent.com/105666905/177880107-5ea535a4-b7fd-467a-8f26-84186bdbf0ef.png)

- Top 5 Schools

![top_schools](https://user-images.githubusercontent.com/105666905/177880609-dcf737e6-c9f4-4f50-9632-219139387355.png)

- Bottom Schools

![bottom_schools](https://user-images.githubusercontent.com/105666905/177880724-e71311c4-4816-437a-9dff-84b7d900d589.png)

## Results

When we compared the refactored analysis of removing the 9th grades from Thomas High School PyCitySchools, we found that our Disctrict Summary was impacted:
- Percentage Passing Math  went down .2% and reading went down .3%
- Percentage Overall passing went from 65% to 64.9

To some extent, the school summary for Thomas High School was affected:
- Percentage Passing Math went up to 97.0% from 93.3%
- Percentage Passing Reading went down 90.1% from 97.3%

Replacing the 9th graders form Thomas High Schools grade with a 'nan'  has an affect as it is a higher ranking school.
- Smaller budgets with high performance can be reduced now that the school is accused of cheating and is analyzing Spending Ranges (Per Student)
- Overall, the school's performance remains unaffected, therefore we may conclude that the 9th graders would have likely scored in the similar range.

Replacing the ninth-grade scores affect the following;

- The Average Math Score went from 79 to 78.9 %
- The Average Reading Score remains 81.9 %
- Percentage Passing Math decrease from 75 - 74.8%
- Percentage Passing Reading also 86% - 85.7%
- The Overall Passing went from 65 - 64.9%

## Summary
1. The data for Thomas High School's ninth graders will now be a "NaN." The more data we have to base our decisions on, the more precise our decisions may be in the future.
2. The school district witnessed less than a 1% fluctuation in its overall passing percentage, therefore the punishment for the high school should not be too severe.
3. One issue that may be affected is that the Spending Ranges (Per Student) are less precise now that a complete school's 9th graders grades are absent.
4. We detected adjustments in math and reading scores, but nothing so extreme that our data is no longer flush.
