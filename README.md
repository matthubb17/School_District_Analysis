# School_District_Analysis

## Project Overview:

The goal of this project was to help, Maria to analyze data on student funding along with analyzing students test scores. As a result of some potential academic dishonesty at Thomas High School, I was instructed to rerun the data and to omit the data that could be a result of academic dishonesty.

## Resources:

**Data Source:** [Resources](https://github.com/matthubb17/School_District_Analysis/tree/main/Resources)

**Challenge File:** [Challenge](https://github.com/matthubb17/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb)

**Software:** Python 3.9.7, Jupyter Notebook

## Results:

As a result of the potential academic dishonesty at Thomas High School, I replaced the math and reading scores with NaNs for all 9th graders at the school. 

* By replacing the 9th graders scores for both math and reading we saw the below changes to the data for Thomas High School:
	- The overall passing % for the district fell slightly as a result of this change along with the passing % for Thomas High School
	- We saw that by using the NaNs Thomas high school dropped out of the top 5 schools list.
	- Other schools data were not affected by this change.
	- One school that was not originally in the top 5 schools jumped into the top 5 as a result of Thomas High School dropping out.

* By omitting the 9th graders scores from the data we saw the below changes to the data for Thomas High School:
	- The overall passing percentages of Thomas High School fell slightly due to omitting the scores.
	- The average math and reading scores for Thomas High School also fell as a result of omitting the scores.
	- Despite some changes we did still see the school rankings for top 5 and bottom 5 remain unchanged as Thomas High School still fell in as a top 5 school even though we were now only looking at their 10th - 12th graders.


## Challenge Summary:

### You can see the below results that were pulled after omitting the 9th Graders from Thomas High School:


## District Summary:

- The below summary is a high level overview of the perfomance of the district for which this data is comprised of. You can see the results of omitting the scores of 9th graders from Thomas High School below.

![District Summary](https://github.com/matthubb17/School_District_Analysis/blob/main/Resources/District%20Summary.png)


## School Summary:

![School Summary](https://github.com/matthubb17/School_District_Analysis/blob/main/Resources/School%20Summary.png)

## High and Low Performing Schools:

- Thomas High School remained in the 2nd slot and only saw their average math and reading scores slightly impacted by removing the 9th graders.

![High Performing Schools](https://github.com/matthubb17/School_District_Analysis/blob/main/Resources/Top%205%20Schools%20Based%20on%20Passing%20Rate.png)

![Low Performing Schools](https://github.com/matthubb17/School_District_Analysis/blob/main/Resources/Bottom%205%20Schools%20Based%20on%20Passing%20Rate.png)


## Math & Reading Scores by Grade:

- The only impact on this data was for Thomas High School to not have data for their 9th grade students as discussed above (this is not shown in the screenshot as I am only showing a shorter list of the full dataframe.)

![Math Scores](https://github.com/matthubb17/School_District_Analysis/blob/main/Resources/Math%20Scores%20by%20Grade.png)

![Reading Scores](https://github.com/matthubb17/School_District_Analysis/blob/main/Resources/Reading%20Scores%20by%20Grade.png)


## Scores by School Spending:

- For the $630-$644 grouping we saw a slight change in the data as this is where Thomas High School falls. This change was fairly small and only changed less than 0.1 percent.

![School Spending](https://github.com/matthubb17/School_District_Analysis/blob/main/Resources/Scores%20by%20School%20Spending.png)


## Scores by School Size:

- Thomas high school falls in the medium category. This data changed less than 1 % point.

![School Size](https://github.com/matthubb17/School_District_Analysis/blob/main/Resources/Scores%20by%20School%20Size.png)


## Scores by School Type:

- Thomas is a charter school and falls into this category. We saw that the change for charter schools scores changed once again by less than 0.1%.

![School Type](https://github.com/matthubb17/School_District_Analysis/blob/main/Resources/Scores%20by%20School%20Type.png)
