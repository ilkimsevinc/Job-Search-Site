# Job Search Site
Steps:
a. Run the attached SQL scripts to import a correct implementation of the database.

b. Design a graphical user interface that will connect to the database remotely to provide the services to an end-user described in Project.Part#2, explained below. The quality of your design will also be evaluated.

c. Implement your design.

d. Write a brief report that explains the following:

a. How is the GUI used? Add some sample screenshots to the report.

b. Is the relational schema of your database in 2NF/3NF/BCNF?

c. How would you improve this database?



Services:

Basically, there are 3 actors: company, end-user, hrr (some hrr also end user).

• Develop registration page that allows any actor to register, to run corresponding insert queries

• Develop login page, no need to have separate login pages for each actor. For successful logins, redirect to actor’s home page.

Company page, after login:

• Display the first name and last name of the HRRs that posted a job listing for the company (Part#2.Q5)

• Display company’s job postings, along with the number of applicants

• Display applications to each posting (Part#2.Q6) if any,

• For either end-user applied to postings,

o Display unemployed end-users (Part#2.Q1, requires slight modification)

o Display the one that has been working at the same company for the longest period (Part#2.Q4, requires slight modification)

o Display the number of applications of each (Part#2.Q7, requires slight modification)

o Display the one with maximum experience (Part#2.Q8, requires slight modification)

• Display internship postings, if any.

• For each internship posting, display the applications, and their details

End-user page, after login:

• List all job postings, internship postings separately.

• List open job postings, open internship postings separately

• Display the company with highest paying job’s posting. (Part#2.Q3)

• Display some appropriate search environment to run queries 11, 12 and 13 of Part#2.

HRR Page, after login:

• Able to create job postings (insert job_posting query)

• Display his/her postings
