# Pewlett_Hackard_Analysis
## Analysis Overview
Pewlett Hackard is a large company boasting several thousand employees and has been around for a long time. As baby boomers begin to retire at a rapid rate, Pewlett Hackard is looking towards the future in two ways. First, it's offering retirement packages for those who meet certain criteria. Second, it's starting to think about which positions will need to be filled in the near future. The number of upcoming retirements will leave thousands of job openings. 

After creating a database, importing data, and using SQL to query the database, Pewlett Hackard's HR Analyst has a few more tasks for me. He wants me to determine the number or retiring employees per title, and identify employees who are eligible to participate in a mentorship program.

## Results
### The table below shows a snippet of each individual that qualifies for retirement in the near future
![unique_titles](https://github.com/dgeroux/Pewlett_Hackard_Analysis/blob/main/unique_titles.png)
### The table below shows the number of retiring employees per title
![retiring_titles](https://github.com/dgeroux/Pewlett_Hackard_Analysis/blob/main/retiring_titles.png)
### The table below shows a snippet of each individual that qualifies for the mentorship program
![mentorship_eligibility](https://github.com/dgeroux/Pewlett_Hackard_Analysis/blob/main/mentorship_eligibility.png)

From these tables, we can see that there are four key takeaways:
..* The vast majority of retirees will be either a Senior Engineer or Senior Staff
..* As a result, Senior Engineer and Senior Staff positions have the greatest priority when it comes to deciding which roles the company would like to fill.
..* Among those that are retiring, there are 1,549 employees that qualify for the mentorship program.
..* There are more people retiring than there are potential mentors, which means that the company would have to create an efficient program that can cover the disparity between the number of people retiring and the number of people who can be trained to fill these positions.

## Summary
To determine how many roles will need to be filled as the "silver tsunami" begins to make an impact, we can create a table to categorize the retirees into age groups. The company can hire (internally or externally) the amount of people that would be retiring, assuming that the retirement age is 65. Currently, we have a list of people who were born between 1952 and 1955. Therefore, we would have a different hiring quota for each of the following four years.

If we look at the current projection of potential mentors and the amount of people retiring, we do not have enough retirees to mentor the next generation of employees. Moving forward, we can create a query that gives us a list of people who are retiring at the end of the current year (and for each following year). From there, the company can prioritize how many younger employees need to be trained to fill up the retired positions. It would also be beneficial if we created a query that grouped mentor-eligible employees into position titles. With this table, the company can plan the mentorship program, specifically, how many mentees a mentor can take on to fulfill the retired roles. 
