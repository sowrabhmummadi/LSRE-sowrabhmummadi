***Seminar  0***

**What is large scale requirement engineering?**

 Requirement engineering process for large scale complex products is called large scale requirements engineering.  This plays a vital role in the development of complex software-intensive systems and in market-driven development.
 
**What are the challenges in large-scale requirements engineering?**

As large-scale requirements engineering involves dealing with a huge number of requirements it involves various challenges, unlike normal requirements engineering process. Some of the challenges are taken  from ((Requirements Engineering in the Development of Large-Scale Systems)) follows:

 -  A Large number of requirements- difficult to specify analyses and prioritization.
 - 	Complex customer meetings- getting feedback in case of ambiguity is a time-consuming process.
 - 	Reaching expectations – due to the complexity of product ensuring the early prototypes does meet customer expectations.
 - Technology advancement – complex products take a long time to develop by when there is a possibility that a new advanced technology is introduced to the market.
 - Scope creep and changes – Research have proven that scope of the project changes frequently  during its development in such case customer requirements and milestones  should be taken care of
 - Traceability – Considering the number of requirements traceability becomes a complex task.


**What is the order of magnitude of the number of requirements we are discussing?** 

Order of magnitude of requirements in a large-scale requirement engineering process is approximately between 1000 - 10000 requirements.

**Papers**

The Art and Science of Software Release Planning
------------------------------------------------
Release planning needs computational intelligence combined with knowledge and experience of experts. In this paper, Authors describe the release planning process in association with incremental development. Incremental development helps the customer to have early access to the product which results in early feedback from the customers. Release planning contains the plan of different system releases each contains a certain set of features based on customer value. Also each further release help in fixing defects from previous releases. Release planning is mainly about selecting features and assigning them to the different releases. This assignment should consider technical, budget, risk constraints.

***Challenges faced during release planning:***

 - 	Planning is computationally complex after identifying the formal definition of the problem. Identifying the problem in the first place is a more complex task due to cognitive complexity.
 - 	A Proper understanding of planning objectives, constraints, important stakeholders and their feature preferences is necessary.
 - Release planning in most of the industries is done in ad-hoc because	
	 - Optimally selecting features is a very complex task considering the no of features.
	 - 	Planning involves the use of resources and also time-consuming.
	 - 	Scope planning is limited to next release only.
	 - 	Even the standards which mention the necessity of the plan lacks the procedures to follow implement planning successfully.

In this paper, the author provides two approaches to release planning. The Art of release planning and the Science of release planning. Agile development methodology which is famous for the well-known small, iterative software release providing early feedback from the customer avoids big bang syndrome does not have a specific procedure to select the features and priorities. Most of the industries even dealing with a large number of requirements lack the tool support for release planning, they use spreadsheets for this process. Authors try to formalize the release planning problem, in the process they have identified similar studies
 - Anthony Bagnall and his colleagues assign weight to the customers based on their importance to the company and then used to plan the feature by satisfying the subset of customer who are more valuable considering the allowed budget.
 - Ho-Won Jung’s approach involves selecting features that provide maximum value to the minimum cost and according to budget features are allocated.
These approaches does not involve customers in decision making process.

***Authors proposed process***
Identify the set of features and assign them to the set of releases.
 

 - identify the dependencies among the features. Proposed two types of dependencies Coupling (dependent should be released in the same release) and precedence (dependents should be released in certain order).
 -  Resources constraints should be considered, these relate to budget and effort estimates.
 - Stakeholders are assigned certain level of importance (ordinal nine-point scale for each customer)
 - Feature Prioritization is done based on the urgency and value. Each feature is assigned a level of urgency (Ordinal nine-point scale given by each stakeholder) based on its impact on the product’s overall value.
 - objective function is formed and then hybrid approach based on integer linear programming is followed.


This process is implemented and verified.


Introducing Support for Release Planning of Quality Requirements – An Industrial Evaluation of the QUPER Model
------------------------------------------------------------------------

In this paper authors introduces a new dimension named quality to the release planning process along with cost and value dimensions. Authors Evaluates this process 	in an industrial environment. From the research the authors have done they found that very little research have been done in prioritization of quality requirements. Therefore, authors have developed a model named Quality Performance (QUPER model) which supports releases planning and road mapping of quality requirements. Quality requirements include performance, usability, reliability etc. When dealing with such requirements aspects such as release targets, end-user experience, business opportunities should be taken into consideration. In this paper, this QUPER model is tailored to the specification of Sony Ericsson and the model is evaluated.

**About QUPER**
QUPER is build following different steps, First step is to understand the requirements decision process and the need for quality aspects in the cost-benefit model is identified. In the second step based on the input of step one QUPER model which comprises of three views is defined, these views are a benefits view, cost view, roadmap view. The concepts such as breakpoints, cost barriers, benefits are also defined in this step. This QUPER model is validated in six cases of selected subdomains by conducting interviews.
QUPER model includes the third dimension along with cost and value that is used for prioritization of functional requirements. This model aims at supporting quality requirements in early stages of release planning process thereby helping in making high-level scoping decisions and creating roadmaps.
	
	
**VIEWS of QUPER**

*Benefit View:* Based the principle changes in the benefit level Benefit view consists of three breakpoints. These breakpoints are based on the level of market value and user experience.
Utility breakpoint: breakpoint between useless (low quality product is not accepted) quality and useful quality.
Differentiation breakpoint: breakpoint between useful quality and competitive quality (helps in competitive market position)
Saturation breakpoint: breakpoint between competitive quality and excessive quality (no impact on benefit by increasing the quality levels). 
*Cost View*: includes cost barriers that show the relation between cost and quality. It contains two different steepness changes, cost barriers which denote the result in quality increase in not feasible without doing huge modifications to the product architecture, whereas cost plateau denotes comparatively less inexpensive software modification results in huge gains.
*Roadmap view:* combines cost and benefit views by placing breakpoints and barriers together on the same scale. Helps in identify the quality of current product and qualities of competing products.


 **Tailoring of QUPER**
 
This is necessary because QUPER model describes above is more generic. As per the company only benefit view is tailored as it is considered more important in QUPER by authors. This process is done by defining the quality aspects used in the company. Estimate the quality of current product with respect to given release, competitor’s product quality is also considered which is already present. For each quality aspects breakpoints are estimated. Based on the estimates target requirements are selected for next releases.
	

***SEMINAR  1***

 **GAP / CVA / IVA Analysis** 
 
 *GAP*: It is a technique that is used by product level management to identify the gap between current state and desired state and determine the steps to reach this state. It consists of 

 - Identifying and listing the factors such as performance of the product, competencies of the present situation (WHAT IS) 
 - Determining steps needed to achieve future desired state ("what should be") which helps in highlighting the gaps that are to be filled.
Gap analysis helps the company to understand who it is and also gives clarity about the way it wants to be in future.


*CVI:* It is a technique that assesses the place of the organization with respect to similar organizations in the marketplace. It involves:

 - 	Define customer value and Identity how that value influences potential customers.
 - Quantify the value as per the developed product or service.
 - Compare your value with competitor’s customer value either better or worse on each aspect the customer value.
 - Then use this observation to predict the future.


*IVA:*   Internal Value Analysis helps in evaluating the product with respective to the company strategies.

**What tools are available for Continuous Integration?** 

It is the part of agile software development. Continuous integration (CI) is support by many tools some of those tools are:

| OPEN SOURCE:                     | COMMERCIAL TOOLS:                      |
|----------------------------------|----------------------------------------|
| Jenkins                          | ThoughtWorks’ Go                       |
| Buildbot                         | Urbancode’s Anthill Pro                |
| Travis CI                        | Jetbrains’ Team City                   |
| Strider                          | Microsoft’s Team Foundation Server     |
| CruiseControl                    |                                        |
| Integrity                        |                                        |

**What is technical product management?** 

 Technical product management involves the tasks like, defining market requirements and allotting them to different product releases. Management tasks are more “How to develop” driven rather than “what to develop”.
 
**What is road mapping? How can you do it large scale?**

 Roadmapping is a technique followed for planning and describing the use technological and scientific resources, elements and their relationships over a certain period of time. Roadmapping helps in improving development process by providing early information by long term decision making. Which in 


***SEMINAR 2***

**Read up on the Boston Matrix**

Boston Matrix is the tool used for product portfolio analysis and management. It is an in formal tool which is developed by the Boston Consulting Group in the early 1970. This tool uses the degree of market share and market growth to identify the necessity of resources to maximize the product management oriented profit.
 Market share (X-Axis): it is the percentage of the total market that the organization attained. Market share is measured in terms of revenue i.e. higher market share means higher financial benefits. 
Market growth (Y-Axis): It is the count of total potential customers using the product. 

| Problem Children 	| Starts    	|
|------------------	|-----------	|
| Dogs             	| Cash Cows 	|

Impact of Market share and Market growth on product portfolio is done using four categories. 
Dogs, cash cows, question marks (or problem children) and stars.
*Dogs* suffer from low market share and low market growth problems. Investment dominates the profit (breakeven will be reached). Usually dogs are sold or closed.

*Cash cows* have high market share and low market growth. These products results in high profits and there is no scope of improvement or no excess opportunities are available. As the name specifies cash cows should be “milked” as long as possible. 

*Problem children* have low market share and high market growth. These products require huge amount of resources by profit obtained is very low. They can grow their market share and thus increases profits, which turns them into stars or cash cows. There is also possibility for them to degrade into dogs which will reduce the profits. These types so products are also called question marks as they are to be analyzed carefully or the investment would be wasted.

*Starts* have ideal combination with high market share and more market growth. These products result in both profits and further opportunities.

**How do you connect your requirements to your architecture?** 

Requirements specify what product is to be build. Architecture depicts how system is organized and how it behaves given a situation. As requirements specify the problem and architecture gives a high level solution to that problem, therefore we can say that Architecture depends on the requirements.

**Can you connect all requirements directly? What do you do if you cannot?**
	All requirements cannot be directly connected to architecture. This might be because some of the requirements are not mature enough to connected to architecture. Maturity depends on the level of detail of the requirement and level of its understanding by the architect. In this case those requirements should be revisited and steps to understand it more should be taken. These steps include conducting meetings with the requirements or owner, conduct interviews  as the requirement ‘s target personal etc.

**SEMINAR 4**

**What tools are available for requirements management?** 

There are many tools available for requirement management. Tools vary based on the type of tools that will be used online or standalone, functionality that the tool provides (e.g. Collaboration, comments for requirements, History tracking, ranking, status reporting, Traceability etc.)
Some of the most popular tools available are:

[Case Spec](http://www.casespec.net/)

[Trace cloud](https://www.tracecloud.com/)

 [Spira test](https://www.inflectra.com/SpiraTest/) 

[Process street](https://www.process.st/)

[Gather space](http://www.Gatherspace.com)

**Any particular tools for agile requirements management?**

Some of the tool particular to agile requirements management are:

[Case Spec](http://www.casespec.net/)

[Process street](https://www.process.st/)

[Innoslate](https://www.innoslate.com/)

[Requirement one](http://www.requirementone.com/)


