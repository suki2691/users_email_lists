# users_email_lists
An analysis of user email logs

Please refer to the file named - 'user_email_analysis.ipynb' for the code


##Overview

We have an email metrics system that has been gathering data since early summer. This tracks email sends, opens and clicks on a per-user basis. It also tracks some supplemental information about each user:

	1.	Whether or not they have created a Babylist registry (registry_created_at) 
	2.	The arrival/birthdate for their baby (original_arrival_date) 
	3.	The attribution (source) for how we acquired that user and the referrer 
	4.	Is the user still active (is_active) 

There are 4 types of emails represented in this data set:

	1.	Weekly Pregnancy Emails - email is sent once per week to user. Contains information about the current stage of their pregnancy as well as tips/suggestions for making a birth plan, putting together a baby registry, organizing a shower, etc. 

	2.	Baby Registry 101 - emails that are sent to new users or leads (people we hope to convert to new users). These contain useful information about how to use Babylist, products that you should register for, and some sponsored content later in the series 

	3.	Newsletter - a weekly newsletter sent to users containing a round-up of articles, deals, ads, and other timely information relevant to parents/parents-to-be 

	4.	Sponsored - Emails that we are paid to send by partners. These usually include a specific deal/offer from our partner. 


Project Criteria

Can you describe how our email list(s) are growing?

Can you describe how our email list(s) are churning?

What is the average lifetime of an email user (how long do they receive at least one of our email series)? Does that vary by referrer?

What factors correlate the most to churn? 
* Due date?
* Source?
* Anything else?

How would you describe our worst cohort?

How would you describe our best cohort?

Are there any recommendations you would make based on this data? What are things we could try to provide a better user experience?

Presentation Requirements
You may use any tools, programming languages, etc that you would like to answer these questions. You will be presenting your findings to a panel of 4-5 people. You should be prepared to explain your findings and back them up with visualizations, charts, tables, etc.

Please save all of your work in either a git repo, a jupyter notebook, or in some format that will allow it to be reviewed by the hiring committee.

Additional Information
1. A large user backfill from a separate email system was done in the summer of 2017. The large spike of users added on a specific day in June represents that backfill.
2. We have been tracking opens/clicks/delivers since February 8th, 2017. In order to make accurate assessments about user activity it may make sense to only look at users created after this date.

