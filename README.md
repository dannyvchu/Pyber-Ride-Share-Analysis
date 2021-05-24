# PyBer-Analysis

## Project Overview
PyBer, a ride sharing company, has tasked me with performing some exploratory analysis to create a variety of different visualizations to showcase the relationship between a variety of different variables:

1. The type of city:
	- Rural
	- Suburban
	- Urban
2. The total number and percentages of drivers
3. The total number and percentages of riders.
4. The total amount and percentage of fares

By showing PyBer the connections and insights related to these variables, they will be able to more confidently know how to improve access to their ride sharing services and be more accurately determine affordable pricing for their service.

## Resources
- Data: 
	- resources/city_data.csv
	- resources/ride_data.csv
- Software: 
	- Python 3.7.10
	- Jupyter Notebook
	- Pandas Library
	- Matplotlib Library
	- NumPy Library

## Results
After removing the Thomas High School 9th grade students' data, we can compare the new data against the old data set and try to see if there were any significant changes.
#### District Summary
Before change:
![district_summary_old](resources/district_summary_old.png)

After change:
![district_summary_new](resources/district_summary_new.png)

Looking at the overall district data, we can see that the overall impact to the district due to the change is negligible, with percentages decreasing only by a few tenths of a percent at most.

#### School Summary
Top 5 schools before change:
![top_schools_old](resources/top_schools_old.png)

Top 5 schools after change:
![top_schools_new](resources/top_schools_new.png)

Similarly to the results from the district summary, we can see that the changes had an insignificant impact on the school metrics. Again the largest changes are only a few tenths of a percent. Relative to the other top performing schools, Thomas High School still remained second even after the changes.

#### Math and Reading Scores

The only thing effected for the math and reading scores here is in the new data, all of the 9th grade math and reading scores have been removed.

#### School Spending

Before:
![school_spend_old](resources/school_spend_old.png)

After:
![school_spend_new](resources/school_spend_new.png)

Thomas High School is within the $630-644 spending range. The only two metrics effected here are '% Passing Reading' and '% Overall Passing' which only decrease by a negligible 0.1%.

#### School Size

Before:
![school_size_old](resources/school_size_old.png)

After:
![school_size_new](resources/school_size_new.png)

Thomas High School is within the Medium (1000-2000) range. The difference between before and after the change are nearly identical when taking into account school size.

#### School Type

Before:
![school_type_old](resources/school_type_old.png)

After:
![school_type_new](resources/school_type_new.png)

The two data frames are identical here.

## Summary

By removing the 9th grade students' data of Thomas High School from the analysis, we were able to see a drop in performance for certain metrics, albeit a very insignificant one. 

- The changes affected the overall district slightly, causing a small decrease in all the percentage columns. 
- For schools in the spending ranges of $630-644, there was a slight drop in the '% Passing Reading' and '% Overall Passing' columns. 
- Taking into account school sizes, there was a slight drop in '% Passing Reading'.
- As for the school type metric, the data was identical.

As we can clearly see, the new changes to the data resulted in an inconsequential difference in the data, which leads me to believe that perhaps there was little to no alteration to the Thomas High School standard test results.