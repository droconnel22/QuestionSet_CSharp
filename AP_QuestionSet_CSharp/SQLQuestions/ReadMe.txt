Question 4:

(SQL)
You have a table of events for a given set of users. Create a report that gives all of the activity the user has done on one row instead of a single row and for each activity, display the time (in minutes) from that activity to the next. So given this table:


Thoughts: This was a difficult problem and one the motivating factors in seeking opportunity is how important perishable skills
such as SQL report generation can be. That being said I believe there is an error in the docs:

User Id:3 

Logged In: 2018-08-23 01:40

Clicked: Null

Logged Out: 2018-08-23 01:57

1:40 <-> 1:57 is 17 minutes not 30...

It might have been that the author thought:

User Id:3

Logged In: 2018-08-23 01:40

Logged Out:  2018-08-23 02:10 (Last Row, but is User 1)

1:40 to 2:10(x) = 30 mins (incorrect)


Question 5:

Given the above table of user activities, along with the below table, 
print out a report of the user's name and date when they were on our website. So given this table:

Thoughts: Straighforward inner join with group by implementation.

