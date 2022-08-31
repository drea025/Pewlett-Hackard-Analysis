# Pewlett-Hackard-Analysis

## Overview of Project

The purpose of this analysis is to conduct a Database analysis for Pewlett Hackard with detailed information on the number of future retirees from all departments currently working at the company to be able to prepare a plan to hire new staff and also to prepare a mentorship initiative. 


## Results
- With the retirment_titles table we are able to see every eligible for retirement employee and how long they have worked at each position over the course of their career.

- Our retiring_titles shows us the a majority of the employees of retirment age (57,668/90,398 = 64%) have senior titles.

To download: [unique_titles.csv](https://github.com/nicoserrano/Pewlett-Hackard-Analysis/files/6736136/unique_titles.csv)

- The unique titles table that we created is showing the most recent title for employees of retirment age.

- Out of those employees leaving, there are 29,414 Senior Engineers, 28,254 Senior Staff, 14,222 Engineers, 12,243 Staff, 4,502 Technique Leaders, 1,761 Assistant Engineers, and 2 Managers. 

![retiring_titles_pic](https://user-images.githubusercontent.com/83378141/123863229-53d63100-d8f7-11eb-952e-6dcc7c9655e2.png)

To download: [retiring_titles.csv](https://github.com/nicoserrano/Pewlett-Hackard-Analysis/files/6736122/retiring_titles.csv)

- Created the mentorship_eligibility table by joining the employees, department employees, and titles tables. In this case, the criterion for the join was that the employees were born in 1965 and that they were currently working at PH, in order for them to apply to the retiring/mentorship package. There were 1,549 employees eligible 

To download: [mentorship_eligibility.csv](https://github.com/nicoserrano/Pewlett-Hackard-Analysis/files/6736217/mentorship_eligibility.csv)

- Out of those eligible employees, there are 402 Engineers, 392 Senior Staff, 332 Staff, 290 Senior Engineers, 77 Technique Leaders, and 56 Assistant Engineers. 

![title_mentorship_eligibility_pic](https://user-images.githubusercontent.com/83378141/123863289-651f3d80-d8f7-11eb-9245-56a49dd010c0.png)

To download: [title_mentorship_eligibility.csv](https://github.com/nicoserrano/Pewlett-Hackard-Analysis/files/6736245/title_mentorship_eligibility.csv)

## Summary

Ideally, as the silver tsunami approaches the idea would be to prepare and be on the look for 13,505 employees. This number represents the number of people that are currently working at the company. The plan is to offer these people the mentorship program so that they can keep mentoring new employees.At the moment at Pewlett Hackard, 64 percent of their employees are getting ready for retirement or being redirected to their mentorship initiatives, which will mean that they are likely going to need an extensive hiring process in the upcoming years. Since a significant amount of future retirees hold Senior positions the mentorship program should provide a capacitation buffer for the extensive expertise that will be leaving the company in the years to come. 
