# Pewlett-Hackard-Analysis
Prepared by Robert Gallagher

## Overview

The purpose of this project is to look at the number of people retiring from Pewlett Hackard and what roles these people will be leaving so that the company can successfully manage the transition.  The initial databases diagram and the SQL code used to set up the initial databases are below:

### Database structure and additonal table creation

[Database Schema Code](schema.sql)

![](analysis\EmployeDB.png)

[Additional Tables](Employee_Database_challenge.sql)

## Results

- There are a signifcant number of employees retiring.  Here is a count by employee title:

![](analysis\Count_of_employees_retiring_by_role.png)

- As you can see from the above list a significant number of senior empolyees are reaching retirement age.

- To help address this Pewlett Hackard is looking to start a mentorship role where some of the older employees take on a part time role instead of retiring immediatly.  The following csv file is a list of all employees eligible for this.

[Mentorship Eligible Employees](Data\mentorship_eligibilty.csv)

- A detailed list of all employees retiring and thier current title is contained in the following csv:

[List of Retiring Employees](Data\unique_titles.csv)

## Summary

### Number of retiring roles and mentorship conclusions
- As seen in the table above there are a significant number of senior roles reaching retirement age.  Of particular note is the nearly 30K of both senior engineers and senior staff that are reaching retirement age.

- There are not nearly enough mentorship eligible employees to train this amount of open postions.  See the table below:

![](analysis\Mentorship_role_counts.png)

### Additional steps
-  It would help to look at how many employees not near retirement age in the roles listed above.  We could modify the query used to build the retiring role count by just saying not in that age range.

- From this list we could look at offereing a less intense mentorship role by looking at the most experienced employees not already eligible for the mentorship program.