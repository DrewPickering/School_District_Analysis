# School_District_Analysis

Project Overview

A school districts chief data scientist is tasked with preparing all standardized test data for analysis, reporting, and to present the data to provide insights about performance trends and patterns.  Analysis will be conducted on school funding and student test scores.  The analysis will assist the school board and district Superintendent in making decisions about school budgets.

Create district and school summaries:
  Calculate the top 5 and bottom 5 performing schools.
  Calculate the average math score received by students in each grade level at each school.
  Calculate the average reading score received by students in each grade level at each school.
  Calculate the school performance based on the spending per student.
  Calculate the school performance based on the size of the school.
  Calculate the school performance based on the type of school.

Resources
	Data Source: schools_complete.csv and students_complete.csv
	Software: Python: 3.7, Jupyter Notebook, and Pandas

Summary
The analysis of the election is included in the included files
 


Challenge Overview

It has been discovered that the ninth graders at Thomas High School have incorrect math and reading scores.  The School District would like to have the school and district analysis rerun with the nineth graders from Thomas High School still included in the data, but with their scores set to NaN. 

Analysis has been recreated and the updated data has been compared to the original analysis:
 1.	New Top 5 performing schools and New Bottom 5 performing schools
 2.	Recalculated average math score received by students in each grade level at each school.
 3.	Recalculate average reading score received by students in each grade level at each school.
 4.	Recalculated school performance based on the spending per student.
 5.	Recalculate the school performance based on the size of the school.
 6.	Recalculate the school performance based on the type of school.
 
Challenge Summary
The updated analysis of the school district data shows: Additional Charts and comparisons can be viewed in the included files

The district overall passing performance dropped from 65% to 64% of all students.  The Ninth graders’ scores from Thomas High were remove from this statistic and therefore their impact prior to removing their scores had a slightly outsized positive impact on district performance.  Also, district average math scores and passing percentage dropped after removing the Thomas High ninth graders’ scores.

Thomas High School had been ranked as #2 in the district based on % of Overall students passing, but after removing test scores from their ninth grade students their position dropped to #8. As ranked by % Overall Passing.  The removed scores did not remove the students, and all ninth grade students were marked as not passing since their scores, now replaced with “NaN” did not meet the > 70 criteria for passing.  Although Thomas High’s average test scores were only slightly changed their passing percentages were dramatically reduced.
 
Replacing the Thomas High math scores caused their “by Grade” scores to be replaced entirely with NaN for their whole class.  Their impact on the overall ninth grade class test scores across the district has eliminated, however as with the school analysis they would contribute to a reduction in district ninth graders passing percentages.

Schools with a per student spending on $630 to $644 have a 7% decrease in overall passing as a result of the updated analysis.

Medium sized schools with a population of 1000-2000 students realized a 6% drop in their overall passing percentages.  Average test scores had minor impacts due to updated analysis.

Charter schools dramatically outperformed the district schools, but as a result of the analysis the charter school type has a reduction in overall passing percentage 3% from 90% down to 87%.  Also, withing the school rankings it should be noticed that all charter schools out performed all district schools, however after the updates Thomas High dropped to the worst performing charter school as measured by Overall Passing %, but still remained better than the best district school in the rankings.  
