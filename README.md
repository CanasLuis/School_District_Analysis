# School_District_Analysis

##Overview of the School District Analysis: We´ve been given with a detail of the School Districts, this information contains the total of the schools and a very complete detail of the grades and scores for both reading and math subjects. The main purpose of this is to have a detail summary of what schools are having the best scores and if it is related with the financial support they receive. We can also analyze the overall passing scores, which is the students with scores higher than 70 for both math and reading. 
After we finished our first analysis, we were noticed that reading and math grades for Thomas High School ninth graders appear to have been altered, so it is important to make adjustments in order to not being affected by that.

##Results
Firsteable, we replaced the information that was altered by NaN´s, so we don´t have any affection in the overall results. This means that we won´t consider 9th grade scores for Thomas High School, that will lead us to different things, as follows:

-How is the district summary affected? When we take don´t consider the information of 9th grade from Thomas High School, our total data is reduced, we started with 39,170 and we now will work with 38,709. This might be considered as a very low reduction, but we will see how this can impact the main results of our analysis.

-How is the school summary affected? we used to have four different grades: 9th, 10th, 11th and 12th, now, for THS school we are no considering 9th grade anymore, even if this is a minor change, our results will be slightly different, as we will see below.

-How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? in the first analysis, Thomas High School was in the top 2 of overall passing percentage, now that we have done the update, it almost goes to top 3 of this percentage. Even with the dishonesty in a part of the information, the school seems to be doing things very good in the rest of the grades.

-How does replacing the ninth-grade scores affect the following:

-Math and reading scores by grade

We started with a % Passing math of 93.27% and a % Passing reading of 97.30%, that gave us an Overall passing percentage of 90.94:
![ths_previous_summary](https://user-images.githubusercontent.com/108499271/181599627-4637368b-acad-4d37-82b5-3f77ac0e9fe8.png)

Once we updated our information, the Passing math percentage is shown as 93.18% and the reading percentage is 97.018%, with a final overall passing 90.63%:

![ths_updated_summary](https://user-images.githubusercontent.com/108499271/181599660-c224e984-03a9-460e-b072-6855f1489972.png)

-Scores by school spending
According to the results, Thomas High School is not the school with more spending per student amounts, however its ubicated among the top overall percentages scores, which means the school is very effective in using its own resources. Thomas High School is ubicated in the range $631 - $645 per student.
![spending_ranges](https://user-images.githubusercontent.com/108499271/181604216-74a4e62f-bc43-4c35-bc40-f160e1830538.png)


-Scores by school size
There are 1,635 students in Thomas High School, which allocates them in the medium size, it is important to mention that this range is the one with the higher Overall passing percentage, in addition, the schools with more than 2000 students seems to have more difficulties with the passing scores. 

![school_size](https://user-images.githubusercontent.com/108499271/181604561-925e93e4-e081-477a-8fb7-ef43382af4e7.png)

-Scores by school type
Thomas High School is a Charter type, the analysis is also showing that these schools have the better scores among their students:
![School_type](https://user-images.githubusercontent.com/108499271/181605435-8adfe6c0-9ada-461e-bdc9-bdf3e8837bd1.png)

##Summary
In summary we can confirm that Thomas High School has a very good teaching level, and it is being reflected on the results and stadistics, this school is part of the groups with higher passing rates and in the top 5 by itself. Even with the information issue for 9th grade students. 

The main changes that we had to do were to make the scores for 9th graders as NaN (Not a Number), after that, we had to obtain the new students without the 9th graders in order to obtain the passing percentages for 10th, 11th and 12th grades. 
Furthermore, the Overall passing rates also had to be adjusted, considering just the math and reading passing percentages for 10th, 11th and 12th grades.

Finally, we have to consider that the budget amount for this school remains the same, we are just leaving the scores from 9th grade students outside our final analysis, but the school still has the students. 
