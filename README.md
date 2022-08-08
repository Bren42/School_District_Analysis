# School_District_Analysis
## **Overview of Analysis**
The purpose of this analysis was to review each school in the district to find patterns of success and what criteria that success was predicated off of. This was done in an effort to determine where next years school budgeting or resources should be allocated.

There are a few key items we need to address before we proceed with the summary of the analysis. The original analysis had to be refactored after there were questions about the integrity of the Thomas High School ninth grade scores. We will address how we refactored this and what the outcome changes were.

## **Results**
### Impact of Thomas High Updates
Prior to going over the analysis and presenting our findings we will first show a comparison of the original high level summary, and the summary as adjusted with the removal of the Thomas High 9th grade scores.

## Original District Summary
![This is an image](https://github.com/Bren42/School_District_Analysis/blob/main/resources/original_summary.png)

## District Summary post Thomas High adjustment

![This is an image](https://github.com/Bren42/School_District_Analysis/blob/main/resources/school_district_summary1.png)

As you can see between these two outputs the overall summary to the school districts has had little impact after removing the 9th graders from Thomas High.
- Overall Passing dropped from 65% to 64.9%
- Passing Reading went from 86% to 85.7%
- Passing Math went from 75% to 74.8%

So in terms of the overall summary little impact is seen here.

Here we will review changes to the per school summary based on the original ouputs and the adapted output with Thomas 9th removed.

### Original per school summary
![This is an image](https://github.com/Bren42/School_District_Analysis/blob/main/resources/per_school_summary1.png)

### New per school summary
![This is an image](https://github.com/Bren42/School_District_Analysis/blob/main/resources/per_school_summary_fixed.png)

What we can see in this data is that although we see some changes the impact overall is not very large.

- Thomas Highs math passing percentage went from 93.27% to an 93.18%
    - less than a half percent decrease. 
- Thomas Highs reading passing percent decreased from 97.30% to 97.01%
    - again less than a half percent overall change.
- Overall passing percentage went from 90.94% to 90.63%


### How did this impact Thomas High's standing against the other schools?

Overall the impact was minimal. In our review of the top five schools by performance Thomas high was listed as the second best performing school with a 90.94% overall passing rate, once you removed the ninth grade scores they were still rated as number two in performance with a 90.63% overall passing percentage.

## Analysis Summary
Lets start by first looking at the top 5 and bottom 5 schools overall and then we can begin to dive further into the analysis.

### **Top Schools**
![This is an image](https://github.com/Bren42/School_District_Analysis/blob/main/resources/top_schools.png)

### **Bottom Schools**
![This is an image](https://github.com/Bren42/School_District_Analysis/blob/main/resources/bottom_schools.png)

As we can see in this initial comparison between the top five schools and bottom five schools we can see some early patterns emerging in the data.
- All of the top five schools are charter schools, inversely all of the bottom five schools are district schools. 
- The top five schools also have a lower average per student spending. The average per student spending is $606 for the top five schools, wereas for the lowest five schools the average per student is $646
- The lowest five schools have much larger total student sizes.
    - Lowest five average student count:3852
    - Top five schools average student count:1641
- The academic area that the lowest schools are lowest in is math. Where are reading scores are relatively comparable with only a 3% swing, math suffers. Math scores between the lowest five and top five schools have a 29 percentage point swing between them.

So from this simple view we can make a couple of assumptions at this point:
1. Charter schools are outperforming district schools.
2. Spending is not a direct factor in success as the top five schools have a much lower per student spending and a much higher overall passing percentage.
3. School size does seem to have a relational impact as all of the lowest five schools have a much larger student body.
4. Math scores are the area that the lowest five schools seem to struggle with. 

However lets take a look at schools from a few perspectives


## School Scores by Type

So first we will look at scores by type of schools:

![This is an image](https://github.com/Bren42/School_District_Analysis/blob/main/resources/type_score.png)

So in this breakout we see a clear pattern, it would seem that charter schools clearly outperform the district schools. We also saw this in the top five and bottom five school breakouts as the top five were all charter and the bottom five were all district. However we need to find some other correlation beyond school type. 

## School Scores by Spending

![This is an image](https://github.com/Bren42/School_District_Analysis/blob/main/resources/scores_by_spending.png)

As we can see in the above image spending does not seem to be the driver of high or low school passing scores. Although we do have two schools in this output that are in the top five schools overall, we also have three schools that are in the bottom five. Those three schools, Bailey, Figueroa, and Ford not only have low scores but they also have the highest budgets. So in this case we cannot make a direct claim that low scores are due to per student spending.

This is again confirmed in the per student spending breakout:
![This is an image](https://github.com/Bren42/School_District_Analysis/blob/main/resources/per_student_spending.png)

## School Scores by Size

![This is an image](https://github.com/Bren42/School_District_Analysis/blob/main/resources/summary_school_size.png)

School size definetely has an impact on scores, and so far this seems to be one of the more significant drivers of success/failure. The small and medium schools have a minor difference overall, almost all their averages are within 1 percentage point. When we swing over to large schools though we see far greater declines in math scores, 24 points on average. 

Lets look at a breakout of schools though to see if the pattern of school size impacting scores continues.

![This is an image](https://github.com/Bren42/School_District_Analysis/blob/main/resources/school_size_score.png)


As we can see in the data above only one large category school had a decent overall passing percentage at 90%, and of all the schools in the large category it was the smallest, almost coming in at a medium category. We can also see that the type of schools that have the lowest scores, district, are also all in the large category. 

## Final Outcomes
Based on the data we have reviewed and the outcomes we are seeing it would seem that the biggest factor in a schools outcomes are driven in part by school size. A further analysis on what factors related to the size of school could be driving this, i.e. class size, resources, etc. could lead us to better improvements.





