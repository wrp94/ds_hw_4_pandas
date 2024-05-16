# ds_hw_4_pandas

## Homework for Module 4 -  Pandas

In this assignment, I used Pandas to merge and analyze data from two datasets containing school information. This involved using groupby's and locates as well as creating summary tables to view aggregated data.

## Submission

[PyCitySchools](PyCitySchools/PyCitySchools.ipynb)

### Analysis

The first thing I did was to calculate the overall passing percentage for each school. This made it easy to sort the schools to get an overview of their performances. I noticed the highest performing schools were charter schools while the lowest performing were all district schools. This is probably due to the math scores since the average scores for the district schools were about 10 points lower than for the highest performing schools.

The next step was to see how the schools' budget affected student performance. Here I found that the schools who spend the most per student actually have much worse performance on math tests while also trailing in reading. It is also worth noting that these schools that spend more per student are district schools. It is possible that the difference in performance was due to the smaller size of the charter schools.

After grouping the schools by size, it is clear that the larger schools are struggling for some reason. It would be interesting to look at how average class sizes effect the success rates for students.

Finally, just to confirm the trend that I saw throughout my analysis, I grouped the schools by type and found a large performance gap between charter schools and district schools.
