# Day 3 lab
## Purpose
Practice using aggregate functions (Unit 2.6) in single-table SELECT statements.

## What to do

### Poverty
* Answer the following 4 questions using the 'poverty' database. This data comes from the US Census Bureau. 
* Create a .txt file to hold the SQL answers to the following questions:
1. Write a SQL query to find the percentage of Alamance County (NC) citizens who are living in poverty. Just show the percentage and the County Name. *Does this query need an aggregate?*

2. Write a SQL query to find the percentage of NC residents who are living in poverty. Just show the state code and the percentage. *Look at the data carefully - does this query need an aggregate?*

3. Write a SQL query to list the county names and poverty rates for NC counties whose ```pov_pct``` rate is higher than the NC rate. Put them in order from highest down to lowest. (You may 'hard code' in the NC rate in your ```WHERE``` clause today - in other words, just type in the percentage number in the ```WHERE``` clause. In future classes we will learn how to look up the NC rate automatically, but we haven't learned how to do that yet.) The answer will be a longer version of the following:

![question 3](https://github.com/megansquire/CSC301Fall2018/blob/master/images/day3Lab.1.png)

4. Write a SQL query to list the top 10 counties (also list the state and poverty percentage) in the United States with the highest poverty rates. Just in case there are ties, sort them numerically and then alphabetically to break the tie.

### World
* Answer the next 5 questions using the 'world' database. 
* Put these answers in your same file.

5. Write a query to find the City name and population for the city that has the highest population. Hint: you might need a LIMIT here.

6. List every head of state from the countries table and how many countries they are in charge of. List them in order of most to least countries.

7. Write the SQL to list each HeadOfState, add up how many countries that person is in charge of, sort them from most to least, but only show the HeadsOfState that are in charge of more than 1 country.

8. Write the SQL to list each HeadOfState and add up how many people that person is in charge of, sort them from most people to least, but ONLY include the HeadsOfState that are in charge of countries on the North American continent.

9. Write the SQL to count major cities by country code, but only list the countries that begin with the letter A and have 2 or fewer major cities.


## What to turn in
* Paste your answers to those queries or upload a text file into the Day3 assignment box on Moodle. 
* Don't forget to take your Quiz #1 before you leave.
