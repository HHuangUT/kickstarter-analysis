# kickstarter-analysis
Challenge 1: Perform analysis on Kickstarter data to uncover trends

#Overview of Project

>"Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals."

Using the kickstarter data set, I analyzed the success/fail rates of a various kickstarters that fit the same criteria as Louise's. I've compared sucess rates based on two main metrics:

**Month of Release** (Month of Kickstarter Announcment)

**Funding Goal** (Kickstarter Funding Goal Amount)

By optimizing the best windows for success on both these metrics, we can help Louise decide on the best way build the funding campaign.

#Analysis and Challenges

**Month of Release**
Success Rates of Kickstarter Plays vs Month

<img width="397" alt="Theater_Outcomes_vs_Launch" src="https://user-images.githubusercontent.com/80546200/111099554-c6bbc780-8513-11eb-8079-167195bebfa7.png">

As shown above, the highest rate of sucesss is found in the month of May.
Summer months on average yield the highest success rates.
This can possibly be attributed to potential funders being more free/open to attend plays in the summer, as apposed to the winter (where the success rate drops).

However, the total number of plays announced in the summer months greatly outnumber those of the winter months. Louise could see this as a sign of less competition, but the success rate of those projects still diminish during the winter months.

**Funding Goal**
Success Rates of Kickstarter Plays vs Funding Goal

<img width="397" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/80546200/111099938-94f73080-8514-11eb-9f59-cadcf682ce68.png">

As shown above, there are two main peaks of successful kickstarter projects:

$9999 and Below

$35000 to $44999

The first peak zone, $9999 and Below, can be attributed to a "low-risk" proposition for the funders, and are most likely to hit their goals because they are either very obtainable and/or could have stretched the goal further.

The second peak zone, $35000 to $44999, can be attributed to a committment from the funders that was enough to get the play "over the hump". In context, just short of this peak is the lowest success rate- the funding that could not get over said hump.

**Challenges**

It is very difficult to create a metric that can resemble the projects performance to what was proposed, and the kickstarter's committment to the funder's feedback. For example, a kickstarter with a great concept might get a great initial burst of funding, but as the project's progress does not meet the funders' intent/direction, the funding can fall short quickly.
Conversely, if a project gets off to a rough start, by listening to the funders' feedback, the project can have its funding likleyhood increase over time.

#Results

**Conclusions Based on Theatre Outcomes by Launch Date**

-  Previous kickstarter plays announced in May (and summer months) yield the highest rates of success (conversely, those released in the Winter months show low success rates)
-  More kickstarter plays are announced the most in Summer months (conversely, Winter months yield less kicktarter play announcements)

**Conclusions Based on Theatre Outcomes based on Goals**


There are two main peaks of successful kickstarter projects:

-$9999 and Below
-$35000 to $44999


**Summary of Limitations and Reference**

-Limitation: This dataset has no lense on how well the Kickstarter project met the funder's expecations (regardless of funding goal).

-Another table/graph that would be useful would be a timeline of funding/support vs time since project announcment until project outcome. This would help Louise gauge and maximize how long/short the project development timeline for success
