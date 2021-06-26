# Pewlett-Hackard-Analysis

### Overview of the analysis:
The purpose of the analysis is to determine the number of retiring employees from Pewlwtt_Hackard per title, and be able to identify employees who will be eligible to participate in a mentorship program. We created a Retirement table that held all the titles of current employees who were born between January 1, 1952 and December 31, 1955. We then created a query that retrieved the emp_no, first_name, last_name columns from the employees table and then retrieved the title, from_date and to_date columns of the titles table. 

### Results:

- The retirement_titles table allows us to see the employee number, first name, last name, title, from date and to date; this allowed us to gather every eligible retirement employee and how long they have worked at each position over the course of their career.

<img width="834" alt="retirement_titles csv" src="https://user-images.githubusercontent.com/83566868/123525580-66eac600-d697-11eb-8c11-f83e7e9dfdb9.png">

- The retiring_titles table shows us majority of the employees of retirement age of which 64% have senior titles (total 90,398 of which 57,668 have a senior title = 64%).

<img width="338" alt="retiring_titles csv" src="https://user-images.githubusercontent.com/83566868/123525698-42dbb480-d698-11eb-8ffd-9d6a644b5300.png">

- The mentorship_eligibility table shows us the employee number, first name, last name, birth date, from date, to dateshow , and title. This table also shows us who were born between January 1, 1965 and December 31, 1965, this allows us to see tthat most of the eligible employees have senior titles.

<img width="892" alt="mentorship_eligibilty csv" src="https://user-images.githubusercontent.com/83566868/123525786-e9c05080-d698-11eb-9c81-d39f9acac802.png">

- The unique_titles table also shows us the employee number, first name, last name, and title. This table that we created is showing the most recent title for employees of retirment age.

<img width="641" alt="unique_titles csv" src="https://user-images.githubusercontent.com/83566868/123525835-4c195100-d699-11eb-844c-7ffc2661c0e9.png">

### Summary:

-- 90,398 roles will need to be filled before the "silver tsunami" begins to make an impact. 
-- Only 1,940 employees are qualified, therefore there are not enough qualified retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees. 

<img width="371" alt="retiring_titles2" src="https://user-images.githubusercontent.com/83566868/123527134-b71b5580-d6a2-11eb-86f0-dae7e2faaad0.png">

The mentorship_eligibility table below shows us that 1,549 mentorship roles available.

<img width="309" alt="Screen Shot 2021-06-26 at 5 17 08 PM" src="https://user-images.githubusercontent.com/83566868/123527228-4c1e4e80-d6a3-11eb-9bf8-84d9a7603918.png">

Over the next couple of years years the company will have to fill many roles and positions due to more than 50% of employees are at retiring age and or are mentorship eligible. 
