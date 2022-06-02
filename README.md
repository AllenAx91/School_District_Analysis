# School_District_Analysis 🏫 

## 1. Overview 

The school board has asked us to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. The authorities believe that the source file ([students_complete.csv](https://github.com/AllenAx91/School_District_Analysis/blob/main/Resources/students_complete.csv)) shows signs of academic dishonesty. Specifically, the reading and math grades for Thomas High School ninth-graders. After replacing the values and repeating the school district analysis, the board needs a report to describe how these changes affected the overall analysis.

## 2. Analysis

Repeating the analysis using NaNs has marginally affected the results on Maths and Reading. However, once the values are rounded off, the difference is barely recognizable. The overall score has also changed but not enough to make a huge difference. More details of the analysis have been listed below. 

### 2.1. District summary 

_Initial Analysis_
![](https://github.com/AllenAx91/School_District_Analysis/blob/main/Resources/districtsummary_Old.png)'
_Analysis using NaNs_
![](https://github.com/AllenAx91/School_District_Analysis/blob/main/Resources/districtsummary_New.png)

### 2.2. Overall School summary and Thomas High School’s performance 

The initial school summary reported Thomas High School's scores to be less than 70% but the inclusion of NaN's to replace the scores of the ninth grade has improved its scores to over 90%. Otherwise, the school summary remains unaffected. 

_Updated School summary using NaNs_
![](https://github.com/AllenAx91/School_District_Analysis/blob/main/Resources/School_Summary.png)

### 2.3. Effect of NaNs

It is clear from the below results that only Math scores, reading scores and the overall scores were affected. As a result, small changes have been recorded in the below analysis. 

  2.3.1) Scores by school spending: Scores in the $631-645 category has increased
  
![](https://github.com/AllenAx91/School_District_Analysis/blob/main/Resources/Spending.png)

  2.3.2) Scores by school size: Scores in the Medium (1000-1999) category has increased
  
![](https://github.com/AllenAx91/School_District_Analysis/blob/main/Resources/Size.png)

  2.3.3) Scores by school type: Scores in the Charter category has increased
  
![](https://github.com/AllenAx91/School_District_Analysis/blob/main/Resources/Type.png)

## 3. Summary

There was no substantial difference in the district and school summary due to the changes in ninth graders’ math and reading scores at Thomas High School. Relative to other schools, Thomas High School's performance improved by approximately 20%. However, the inclusion of NaNs did not make a big change to Scores by school spending, size and type.

_Initial Analysis_
![](https://github.com/AllenAx91/School_District_Analysis/blob/main/Resources/THS_new.png)
_Analysis using NaNs_
![](https://github.com/AllenAx91/School_District_Analysis/blob/main/Resources/THS_old.png)


