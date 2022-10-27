# Pewlett-Hackard-Analysis

## Overview
In this project I am usigng ERD's, pgAdmin, and SQL to make a database to find the total number of employees retiring for a comapny. With this analysis I am able to communicate to the human resource team how many positions should be filled up in the future to keep operations running as smoothly as possible. On top of filling up positions in the future, the company can also prepare for creating andn budgeting retirement packages for those individuals leaving. 

## Results
By creating the unique_titles table I was able to determine exactly how many employees will be eligible for retirement and organize them by their titles. I was careful to take into consideration to remove duplicates since some employees may have transferred between differencet departments. The query returned that at least 90,000 employees will retire in the future. That's a lot of positions that need to be filled up. 
![Capture](https://user-images.githubusercontent.com/112291075/198364590-9d6c9ef5-a443-44ad-87b4-838376aef8df.PNG)

Pewlett-Hackard came up with an idea to create a mentorship program, where eligible retiring employees can mentor new hires to make the transition as seamless as possible. In this table, mentorship_eligibility, I made a criteria that employees born in 1965 and working at Pewlett-Hackard would be eligible to participate. A grand total of 1,550 employees would be eligible for this initiative.
![Capture1](https://user-images.githubusercontent.com/112291075/198365820-8b676db2-e6b5-48e4-b060-9df3860036fe.PNG)

## Summary
In conclusion I would suggest to Pewlett-Hackard that they should statrt preparing for this massive retirement wave and proactively start filling up positions little by little. Especially beginning with the departments that have the most total retirees, since that is the area that will be affected the most it should be a priority. One last thing I would recommend is to incentivise the mentorship program and announce it as early as possible to get as many employees on-board. Since it is an option I cannot guarantee that all 1,550 would want to participate if they choose not to. So it would be wise to make the most out of those that are eligible to participate.
