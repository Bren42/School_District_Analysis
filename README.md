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

However lets look at some of these areas more specifically to see if these assumptions hold up.

