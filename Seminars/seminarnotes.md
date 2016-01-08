– “The art and science of release planning”, plus some more recent works on the EVOLVE methods
Summary
According to Ruhe and Sailu incremental development helps in understanding the stakeholder’s preferences by facilitating the possibility of early feedback and also add early value to the product which help the organizations to build user expected products. This process can be enhanced by effective release planning. Release planning involves identifying and selecting features necessary for successive releases satisfying budget, resources, and risk constraints. It also involves human hunch,
Most of the research planning techniques used in industries are informal and ad-hoc which make this process not so promising this can be because of organization lack of attention towards the process or lack of maturity about the process.
Even though planning is mentioned in Standards like CMM,ISO they don’t explain how exactly to achieve better results
Research planning can be better implemented in agile development as planning has physical involvement of important stakeholders for respective set of features and these set being small. Even in agile development there are no predefined set of methods followed in planning that yield better results.
Plan driven development also suffers these disadvantages.
The process of releasing planning manually becomes exponentially complex as number of requirements increases.
Formalize the problem to get better meaningful results.
Anthony Bagnall and his colleagues-Assigning weights to the customers	
Ho-Won Jung’s approach-Maximum value for minimum cost	 
Drawback: Don’t not involve stakeholders in research planning decisions
Mark Denne and Jane Cleland-Huang’s-incremental funding method	Focus on revenue projection	
Penny’s maintenance planning.	Release monitoring (available effort, required effort)	 
RP constraints are not considered
Factors to be considered for release planning :  Decision variables, Feature dependencies (Coupling and precedence dependencies), Resource constraints (Identify the resources available), Stakeholders, Feature prioritization, objective function (urgency, risk, satisfaction or dissatisfaction, and return on investment)
Release planning can be more effectively implemented by actually identifying the need for strong methodology, formulating objectives which involve impacting criteria rather than only considering the importance of features. Better data collection techniques to get more accurate and limited data to evaluate. 



– A Case Study Evaluation of the Guideline-Supported QUPER Model for Elicitation of Quality Requirements Richard Berntsson Svensson and Bjorn Regnell

Release planning plays a major role in market driven development where the organizations compete in open market. To survive competition organization should be able to bring new, innovative, necessary features as early as possible to market which requires better more formal release planning. Along with value of the features considering quality requirements acts as added advantage. This article provides practitioners’ view of Quality Performance (QUPER) model by providing results of case study conducted in a company on mobile handset domain which has 24 professionals.
	Methods that consider strategic quality requirements for release planning are very less, one such method is QUPER.it addresses quality and cost constraints for a requirement.
EVOLVE II is the method used for released planning and which considers quality aspects of the requirements. It usually assigns cost between functionality and quality requirements.
Ex: 90% for functionality and 10% for quality
Drawback: level of quality necessary is not identified.
QUPER and EVOLVE II can be used combined to achieve better results.
WHEN IS THE QUALITY LEVEL GOOD ENOUGH..?      It is the tough question when it comes to identifying the quality.
Introducing Support for Release Planning of Quality Requirements


– An Industrial Evaluation of the QUPER Model

In this paper authors tries to answer questions relating to performance, value, cost, benefit that can occur during release planning.
E.g. would slightly better performance significantly more valuable form market perspective?
Main purpose of this paper is to figure out the implementation of QUPER in Industry. This is done by conducting a case study at sony errison a mobile handset company. QUPER model doesn’t evaluate quality based on either its good or bad instead it evaluates quality as the different levels of scales of goodness. Quality is non-linear continuous graph when evaluated with cost, benefit. Further generic QUPER model is tailored as per the company and a case study is conducted. Based on the evaluation results it can be understood that applying QUPER during release planning will have added advantage understanding, evaluating quality which leads to the better performance of the product in the market.


-A Market-Driven Requirements Engineering Process: Results from an Industrial Process Improvement Programme

This papers describes continuous elicitation, prioritization of requirements during release planning process in a market driven environment with expert cost estimation techniques. Unlike releasing planning for bespoke software where customer is well defined and requirements specification are more clear in market driven development this releasing planning should be able to identify new requirements to ensure the competitiveness in the market. In this paper authors describes an industrial requirements engineering process for a packed software called REPEAT (Requirements Engineering ProcEss At Telelogic).REPEAT involves elicitation, selecting, managing requirements for release planning process.
REPEAT actors
Requirements Management Group (RQMG) - requirement management and decision making.
Issues: any one that issues a requirement.
Customers and users: Stakeholders who uses the software and provide feedback.
Requirements team: analysing and specifying the set of requirements.
REPEAT Requirements states
New: initial state, initial priority 
Assigned: Assigned for expert for analysis
Classified: rough estimate and implementation ideas.
Rejected: end state representing that requirement is rejected.
Selected: requirement is selected with detailed estimates  
Applied: implemented and verified

REPEAT provided promising results by releasing the producing as expected than traditional ad-hoc process of release planning.

SEMINAR 2:

-A Cost–Value Approach for Prioritizing Requirements
Authors develop an approach for the prioritization of requirements, this approach is called cost-value approach. This approach is applied in two commercial projects which have showed promising results.
According to authors’ pair wise evaluation of requirements yield better estimates than evaluating them individually. This approach utilizes Analytical Hierarchy Process (AHP) for pair wise comparisons of the requirements. AHP is used because it favors redundancy thereby eliminating human error.
Approach includes five steps:
1. Requirements engineers review the requirements to ensure they are unambiguous
2. External Stakeholders apply AHP on requirements to determine the value
3. Experienced software engineers apply AHP on requirements to determine the implementation cost.
4. Software Engineer determines the value and implementation costs of candidate requirements and plot them in cost-value graph.
5. Stakeholders uses this graph as a map for analyzing the requirements


-A Method for Early Requirements Triage and Selection (MERTS) Utilizing Product Strategies
According to authors, rejecting the unnecessary requirements in the starting phases of requirements engineering process would help in saving resources without spending more resources on the those unnecessary requirements. This paper presents a method for requirements triage and selection by aligning the technical and strategic goals. This method is built on performing literature review for identifying product strategies and also validated with the industry.
PROCESS
1)	Specify- Answer questions such as i) where do we want to go? ii) How to get there? iii) what will be done? For each product which will result in explicit understanding of goals and objectives of the product.
2)	Assign Weights- A total weight of 300 is given to all three question 100 for each question. Distribute this weight for the answers according to their priority. Later these weights are normalized.
3)	Compare requirements – Compare the requirements along with answers and their sub classifications, assign weights to then and the normalize them.
SELECTION PROCESS
1)	Specify product technology roadmap-
2)	Estimate resources

-Requirements engineering: In search of the dependent variables
In this paper authors describe the framework for accessing the quality of requirements engineering process. This framework includes identifying the dependent variables that necessary for accessing the quality. This framework include different levels of qualities. The quality of Software Requirement Specification (SRS) itself is a first level, other levels includes successfulness of project ,product at next level, impact of company on society as a whole is included in the higher-level. According to authors most of the companies perform their improvements for the requirements engineering process assuming the success of the project which can be for example reducing the overall project cost, finishing early, optimistic resources etc. Which does not promise the better product. Identifying the dependent variable for making changes for the independent variable is a difficult task as there are very large set of dependent variable available. Here independent variable is requirement engineering process and dependent variable can be time taken for whole project etc. Identifying the better set of dependent variables for the changing the independent variables yields better results. Authors identified dependent variable from different stages of the project development and organized them into levels. First level includes requirements phase and the variables identified are requirements cost and time, requirements quality which include total cost of the project, average cost per requirement, and quality of SRS. Next level include variables that are necessary for project success which are project cost and time, project estimates, degree of requirements change. Next level is product level to determine the success of the product which includes requirements selection, degree of impact, Next level is company level it determines the company’s successes which include portfolio management, strategic management, degree of impact. Next level and last level is Society, this determines the impact of product on the society which includes positive and negative externalities. Finally this paper provides different aspects that the change of requirements engineering process effect.

Requirements Abstraction model
	 Authors designed a model supporting requirement engineering process which help in making the requirements comparable to one other thereby helping the prioritization process. This model is developed keeping mind the market driven development (MDD) where the requirements are more product oriented. Market driven development usually follow incremental model whose primary goal is to select optimal set of requirements for different releases (increments).Things like what requirements that a release should contain, what is the cost (resources) needed for the implementing these requirements, decision of what features should to available depending on different customers, point at which quality should be taken into consideration determine the success of the product. Unlike in classic bespoke project development project initiation is done by requirement engineering process rather than an idea or order. According to authors this there are many sources from which an requirement can come from, from internal stakeholders, external stakeholders etc.at different time and with different level of abstraction in MDD .In order to provide the product managers a tool for requirement engineering process Requirement Abstraction model was developed. Benefits of the model are 
-Analyzing the requirements to meet product goals and dismissing them if they don’t match them. Helps to concentrate on the requirements that are only required.
-All requirements are broken down to abstraction level to ensure that requirements are able to initiated the development process
-For effective prioritization and release panning requirements which are at abstraction level are compared to each other.
-requirements can have different levels of requirements providing the better understanding of the requirement thereby supporting decision making process. 
RAM PROCESS
1.	Specify (elicit) - this step involves getting an overview of the raw requirement, so that it can be understood by product manager. This step discusses about the specification of the requirement according to RAM model requirements should have title, description, benefits from specifiers perspective, Restrictions and risks etc.
2.	Place(Ascertain the abstraction level of requirement)-RAM contains four abstraction levels i)Product Level –most abstract level can be compared to product strategies cannot be compared to organizational strategies , ii) Feature Level, iii)Functional level, iv)component level.
3.	Abstraction (Work up) - breaking down the requirement based on the level they are placed previously. This step may result in creating new requirements called workup requirements. This break down is done because the requirements should be compared and we can only compare the requirements at same level.
4.	Requirements workup discussion
Authors have validated RAM using static and dynamic validations.
