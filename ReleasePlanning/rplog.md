RELEASE PLANNING
----------------



----------


Release planning log:
---------------------

**Week 47:**

 Started working on Assignment in GitHub worked with issues, trying to understand the issues and discussing the requirement with issue owner based on better understanding the requirements. This discussion is done in person rather in Github.
**Week 48**
 
Haven’t worked more notable progress is understanding the latest requirements.
**WEEK 50**
 
Added new issues (requirements) which includes 
*86: “as a student I should be able to upload my personal files such as running log, other materials related to my work which is to be private to myself.”*

*87: “mail alert should be given to students regarding high preference notifications related the courses they have registered”*

*90: “As a user, data about extra-curricular activities that are happening in and around the campus should be provided.”*

*91: “All the data such as course slides, course videos should be backed up”*

 *93: “How long will the user be able to recover his/her account with this email . ”*
 
 *108: “Along with the assignment record tab should allow students to have discussion about the assignment with the teacher”*
 
These issues are created in order to complete the necessary set of requirements. Also participated in the discussions about the issues created.

**WEEK 51** 

Created the labels to the issues which specify the type of requirements and started identifying the dependencies among the requirements. These dependencies are then plotted in GitHub.
  Also, a discussion about the prioritization techniques for requirements is started in the discussion forum.

**Week 53**
 
Assigned the issues among ourselves in order to own the requirements and participated in prioritization and release planning. Discussion about the prioritization techniques are finalized and release planning is done according to the techniques chosen this process is clearly described in the section below. Release planning is done bases on the prioritization after grouping the requirements based on the domain.


----------


***Release planning meeting and work done.***
MoSCoW technique has been followed to prioritize the requirement. This prioritization of the requirements is done in following steps.

***Step 1:*** Requirements are first divided into a number of groups based on the description given in GitHub. Groups include login, course start page, course, security, view, extra, Roles etc. this division is done manually. At the end of step one, all available requirements are divided into above-mentioned groups.
*Note:* Names of the groups are based on the theme of the group and also abstract.

***Step 2:*** Based on the labels given in the GitHub, dependencies are identified and marked in the workspace. Precedence dependency is mostly considered. This process is done by discussing the requirements and in the case of ambiguity help from the respective owner for the requirement is taken. Dependencies mentioned in GitHub are further refined during this step. At the end of the step, 2 dependencies of the requirements and groups are identified. 

***Step 3:*** Then the requirements that are grouped and dependencies identified are now assigned to priority groups based on the MoSCoW technique. The decision process for allocating requirements into groups is done by discussion.

***Step 4:*** Based on the requirements priority groups they are assigned to different releases.

> Released plan and work can be seen at
> https://drive.google.com/open?id=0Bz_7Gx1hn6L9blVlRDlhR3ZzWDA
> Workspace can be seen at:
> https://drive.google.com/file/d/0B2j1u9JQf0oVaW5ZWVQybWZBOGs/view?usp=sharing
> Numbers denote the issue numbers from GitHub.





***Selection of prioritization techniques.***
	 After having a discussion in its learning and in the meeting, different prioritization techniques are proposed and discussed. Initially, everyone has suggested planning poker as we have previous experience using it. As the discussion happened we realized the challenges of using planning poker as the prioritization technique we also cannot much literature supporting our decision of using planning poker. After some literature review we identified some techniques, these techniques include 

 - 	*AHP (analytical hierarchy process)*
This process involves comparing the requirements in pairs (unique pairs requirements). In order to determine the priority of the compared requirements i.e. which among two requirements is of high priority and which is of low priority comparatively and to what extent. 
Pros: due to redundancy in comparisons this process is not prone to judgmental errors.
Cons: This method is demanding as no of requirements increases. For a project which has n requirements total of n(n-1)/2 comparisons are required.

 - *100 dollar test*
It is a game based method where all the participants of the prioritization process are provided with a constant amount (in this case 100$) each and are asked to buy the requirements with giving amount worth. Requirements are ranked based on the amount of dollars that the participants willing to pay .Participants include various stakeholders and from this method their preference of the requirements can be known.
*Pros*: Easy to use and does not require any previous expertise. 
*Cons*: Bias

 - 	*Top ten estimation* 
Each participant is asked to select his/her top ten requirements from given set of requirements based on this list, level (priority) of stakeholder requirements are prioritized.

 - *Ranking*
Stakeholders are given the list of requirements and are asked to rank them as per their preference. Ranks from different stakeholders are collected and the mean of the rank is considered as the rank of the requirement.
*Pros:* Easy to implement 
*Cons:* difficult when a number of requirements are high.

 - 	*Grouping:*
All available requirements are divided into different priority groups. MoSCoW technique is one of the grouping methods. 

After the discussion and considering pros and cons of each method, the group agreed to use MoSCoW  technique.

MoSCoW
It is a grouping technique where requirements are grouped into different prioritized groups. MoSCoW contains different priorities.

> M – MUST have this requirement. 

> S – SHOULD have this requirement if at all possible. 

> C – COULD have this requirement if it does not affect anything else.

>  W – WON’T implement this time requirement but WOULD  like to implement sin the future.


***MUST*** 
Requirements which are labeled as MUST have to be included in the current release. Of the available Must requirements if any requirement is not implemented the release may result in failure of the release.

***Should*** 
			SHOULD requirements are also crucial in the success of the project, but not including them in current release will not result in failure of the release. Usually, SHOULD requirements are not as time-critical as MUST requirements and have different ways of implementing it to satisfy the requirement.
			
***Could*** 
Requirements which are labeled as COULD are considered less critical and are often seen added features (good to have). These requirements help in increasing customer satisfaction thereby help in a competitive market.

***Won’t (but Would like)***
 These requirements are not critical, doesn’t have any influence on the product in the market, not appropriate at current time requirements. These types of requirements are dropped of considered when the time is appropriate.
 
***PROS:*** 

•	easy to implement, no infrastructure is necessary. This could be done without the support of big software tools.

•	Participation of the entire team (participants in requirements prioritization process) helps in understating the requirements better.

•	A Clear description of the MoSCoW selection process helps in assisting the team.

***CONS:***

•	Stakeholder thing every thing is important and all requirements are labeled as MUST (understanding of the product is very important)

•	Selection criteria play a vital role

 
*note:* requirements can be downgraded, upgraded by agreement with all relevant stakeholders.
	


