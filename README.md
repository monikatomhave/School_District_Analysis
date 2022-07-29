# School_District_Analysis
Module 4

Overview of the school district analysis: 

     The purpose of this analysis is to help prepare all standardized test data for analysis, reporting, and presentation to provide insites on performance trends and patterns.  These insights are used to inform discussions and startegic decisions at the school and district level. We are analyzing student funding and student standardized test scores. We are to aggregate the data and showcase trends in school performance to help the school board and superintendant make decisions on school budgets and priorities. 
     
Results: Using bulleted lists and images of DataFrames as support, address the following questions.

        The are 461 9th grade students from Thomas High School that were removed from the data set because of possible academic dishonesty.
    
    * How is the district summary affected?
        total student count went from 39,170 down to 38,709
        average passing math went from 74.98% to 74.76%
        average passing reading went from 85.81% to 85.66%
        overall passing math and reading went from 65.17% to 64.9%
        
        So with the 9th grade from Thomas High School, the percentages were slightly higher,
        but overall, for the district, very close to the same when removing their scores. 
        
        
    
    * How is the school summary affected?
         Thomas High School math w/9th grade             93.272171
         Thomas High School reading w/ 9th grade         97.308869
         Thomas High School overall w/ 9th grade         90.948012
         
         Thomas High School math wout/9th grade          93.185690
         Thomas High School reading wout/ 9th grade      97.018739
         Thomas High School overall wout/ 9th grade      90.630324
         
         For Thomas High school, the scores do go down, but not even by a half of a percent, for each math, reading, or overall
         percentages. 
    
    * How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
         Before taking the 9th graders out, Thomas High school ranked second on overall passing poercentage among all 15 schools with a 
         90.9.  After removing the 9th grade scores and rerunning the data, Thoams High School is still ranked second according to overall
         passing percantege, it jsut went down to a 90.6.

    * How does replacing the ninth-grade scores affect the following:
        * Math and reading scores by grade
        * Scores by school spending
        * Scores by school size
        * Scores by school type
        
        Replacing only the 9th graders from one school does not affect the overall school spending, school size and school type enough to 
        change any of the data.
        
        
Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

        Since the overall total of students for the whole district went down by 461 students for the 9th grade from Thomas High School, that 
        is only 1.1% less of the entire students analyised.  Overall the percentages for the district as well as the highg school were only 
        affected by around .3% difference before versus after that number of students was removed from the dataset.  Overall, if any budget 
        decisions are based off these scores, I would not recommend cahnging any budget distribution based off of the scores changing. 
        Thomas high school was still ranked second in overall passing percentage out of the 15 schools that were in the district.  