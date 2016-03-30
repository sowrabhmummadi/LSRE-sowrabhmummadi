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

Seminar 3
--  v.d. Weerd & Brinkkemper “Towards a reference framework for software product management”
Software product management is different from traditional (non-software) product management in different ways. Software products has various advantages such as there are no additional costs required for the extra copies and any unnecessary functionality of this products can be rectified easily by releasing patches. Due to this ease of development, changes occur more frequently which will increase the responsibility of product manager. 
In this paper authors formulated a reference framework for the software product management. This framework assists product managers in accomplishing their responsibilities such as managing requirements, defining products and releases in the context of both external and internal stakeholders. This framework provides the complete understanding of the whole product management domain.
Software product management is divided into four process areas based on the hierarchy levels. 
	-Software portfolio management (deals with the products with similar base structure produced by the organization) identifying new market trends and introducing new products to match them. Also determining the product life cycle, product line (identifying the products with similar set of features), establishing contracts, etc. 
	-Product road mapping (long term (min 2 years) planning the business, technological resources for a certain product throughout its lifecycle) input from portfolio management is taken into considerations to identify themes necessary resources for the project. 
	-Requirements management (Gathering /identifying, revising, organizing requirements) it include analyzing the requirements, translating them into product requirements (requirements implemented in product).
	-Release planning (determining the set of requirements that are to be implemented for releases) it involves prioritization, selection of requirements.
	
	13 Market-Driven Requirements Engineering for Software Products

Market-Driven Software Products are the software that is aimed at the open market rather than a specific customer(bespoke product).Development costs of Market Driven products are divided among many buyers in an open market. This paper focuses on the product requirement engineering process of Market-Driven products. This paper also provides implementation way to progress tracking and data management.  Requirement Engineering process of the Market-Driven products is identical to the bespoke product but with some additional challenges and change in context. The process of requirement engineering in Market-Driven environment is called Market-Driven Requirements Engineering(MDRE). Developing organization should consider the following things in order to stay alive in competitive Market-Driven market.

 - Efficient MDRE process dealing with bespoke requirement engineering activities such as elicitation, specification, and validation in the Market-Driven context.
 - Management of MDRE Repository.MDRE repository includes the data about produced requirements along with past requirements data with varying level of abstraction. MDRE repository includes current customer profiles, latest status about candidate requirements and requirements under development etc.
 - Profitable Release planning which considers strategic assets of development, the competence of its engineers,software architecture investment combined with overall business strategy.
 
Requirements Elicitation is the primary step in requirements engineering process.This steps in MDRE process includes the market analysis and new ideas based on the technology.Requirement specification step in MDRE process becomes more complex as there is possible of a huge number of requirements and level of detail of the requirement cannot be expected.Therefore, a well-defined repository should be in place to deal with these requirements. Prioritization is a key aspect of MDRE process which helps in decision making and supporting. 
MDRE along with traditional requirement engineering activities will also include release management and market analysis. MDRE is conducted mainly because of competition from co-developing organizations as product evolve.Software products can be classified using a degree of customization and the hardware/software content.Market-Driven products include generic(developed for open market)/customized and pure software(contains only software)/embedded systems.Customized products are also part of Market-driven products because a product which is customized first can later be introduced in the open market  which can improve revenue.The main characteristic of Market-Driven product is to release right product at the right time while bespoke deals with agreement fulfillment and customer satisfaction.
***Some of the Challenges faced in MDRE***
 - 	Balancing market pull and technology push(balance between needs and technology)
 - 	Chasm between marketing and development
 - 	Organizational instability and market turbulence. (caused due to  undefined specific process for development/no documentation or standardized procedure followed)
 - Requirement dependencies
 - Release planning and cost value estimation (caused due to immature estimations )
 - Overloaded requirement management (caused due to flooding of requirements repository).
 
MDRE process implementation to be concrete  some factors should be implemented such factors include type of development process, price, distribution policy, type of market, product complexity, product flexibility ,user interface complexity, prediction of sales, sale channels. Process quality of MDRE process is explained using *alfa-beta model* where alfa requirements are must implement requirements as they add quality to the product, beta requirements should not be implemented as they are lower the quality of the product. Using this model product quality and decision quality can be known. Main challenge lies in selecting alfa requirements while rejecting beta requirements. Elicitation process had a great impact on the process quality. Golden-grain ratio (ratio of number of selected alfa requirements to total number of issued requirements) is used to identify the outcome of elicitation process.
***MDRE Data Management***	
	Data management In MDRE can be done using requirements state model (RSM) (used for the tracking the progress of the requirement refinement), requirements repository where there details about the requirements are stored. RSM uses requirements salmon ladder with following states candidate (each received requirements gets this status), Approved (Reviewed and accepted requirements gets this status), specified (detailed specification added), Discarded (Reviewed and rejected requirements gets this status), Planned (resources allocated), Developed, Verified, and Released. 

**My view:**Having requirements repository will assist requirements analysts in identifying the dependencies, identifying similar requirements,grouping the requirements etc.  MDRE process tends to be more complex process as we consider each and every possible scenarios such as number of requirements,  continuous requirements inflow, requirements changes, competitors, changes in technology, target market etc. An effective process plan considering all above mentioned challenges should be made in order to be effective in the market.

	

-An Industrial Survey of Requirements Interdependencies in Software Product Release Planning
Requirement dependencies play an important role in requirement selection and releasing planning process as there are independent with each other. Traditional bespoke project has more functional dependencies and Market driven development project has value related dependencies. Different possible interdependencies are identified in order to improve releasing planning process. Authors also applied a simple visualization technique to display the interdependencies of the requirements and also find this technique useful in identifying important characteristics of the requirements. Authors identified some preliminary interdependencies by conducting a survey which includes AND, REQUIRES, TEMPORAL, CVALUE, ICOST, OR etc. A set of requirements can have as many interdependencies as possible. After this identified interdependencies are applied to the requirements  authors visualized  these interdependencies.
VISUALIZATION process
1)	Requirements that are singular are spotted in the graph which is an easy task they don’t contain interdependencies. These can be scheduled to any increment. 
2)	Pairwise assessments for the requirements for identification of similarities ,
3)	Identifying highly dependent requirements.
4)	Plot the graph as requirements as nodes and different kind of dependencies as different type of edges.  

-Are you biting off more than you can chew? A case study on causes and effects of overscoping in large-scale software engineering
	In market driven development when there are less requirements that are priori they there is a change of overscoping. This paper discusses this overscoping shortcomings, impact of agile requirement practices on overscoping. In Market Driven Requirement Engineering (MDRE) product mangers task of scoping requirements for the release planning is very hectic. Due to change in market technology, market priorities with large number of requirement change requests, new requirements that may include new functionality come continuously. Usually agile development methodology claim to address this issue by having balanced view of scoping and available resources due to comparatively less requirements per sprint. Authors provides factors responsible for overscoping thereby eliminating the risk by avoid the overscoping.
-Identifying the Main causes of requirement overscoping.
1)	Continue requirement flow –different requirement flows which are caused by different variants in product line, late new market requirements, communication gap between different units (e.g.  requirement unit, development unit, design unit etc.)lead to overscoping.
2)	No overview of software process-lack of overview of available development resources associated with communication gaps result in overscoping   
3)	Low Development Team (DT) involvement in the early phases-development team busy with development and maintenance of the previous projects.
4)	Requirement not agreed with DTs-due to the low involvement of development team in the decision making process of the requirement engineering.
5)	Detailed requirement specification produced upfront.
6)	Unclear vision of overall goal.-lack of clear business strategy.
-Effects of overscoping
1)	Frequent of change of requirement- descoping the requirement that has already started is waste of the resources
2)	Quality issues-due to high workload caused by overscoping, continues changing of requirements.
3)	Delays
4)	Customer expectations not always meet
5)	Communication gaps
6)	Challenge the keep SRS updated 
IMPACT of agile practices:
   Even though overscoping can be seen it is more manageable and less challenging. With the introduction of following agile practices.
1)	One continuous scope and releasing planning flow
2)	Cross functional development teams
3)	Gradual and iterative detailing of requirements.
-Factors Affecting Decision Outcome and Lead-time in Large-Scale Requirements Engineering
	Requirements Engineering process is a critical stage in software development where the decisions about developing the right product as customer expects are taken. Requirements selection is a complex decision problem, this paper author aim to identify the change requests that may influence decision lead-time and decision outcome.
Decision lead-time: time taken to analyse the impact of the decision.
Decision outcome: Specific outcome of decision process (acceptance or rejection).

Seminar 4
-- Wnuk et al. “What Happened to Our Features? Visualization and Understanding of Scope Change Dynamics in a Large-Scale Industrial Setting”

In this paper, authors developed a Visual representation chart called Feature Survival chart (FSC) which is useful in understanding the scope changes and help investigators in taking scoping decisions. Along with the chart some scoping measurements are also proposed which are also in evaluated.

FSC is constructed as follows, it is a two dimensional representation with scope changes over time on X-axis and feature list in Y-axis. Different colour schemes are followed to represent the feature for scope for example shades of green is used to display acceptance level of the feature whereas red specifies that this feature is de-scoped.

FSC is developed by conducting a case study in large company which uses a product line approach for developing embedded systems. FSC is applied for three different projects, and scopes changes are observed.
--Company follows a state gate model (project id divide into smaller pieces with stages where project activities are conducted and gates where business evaluations and go/Kill decisions are made) with many iterations. Company has four mile stones and according to company guidelines most of the scoping should be done before milestone two but if we observe the FSC charts of the products we can understand this is not the case as most of the scope changes are done after the milestone three.
--According to the company the secondary flow (requirements that deal with platform adaptation which does not include core functionality) of requirements are identified after the milestone 2 which is not the case. Secondary requirements are identified after milestone 4 which can be understood by FSC chart
From the above examples it can be understood that FSC chart helps in keep track the scoping process of requirements which helps design a better product in this changing markets with evolving technologies.

A total of five measurements are also identified to measure this scope process of which four can be calculated from the scope attribute value from feature list document (document that contain the description of each feature along with scope attributes) and fifth measurement require more qualitative approach.
-Measurement 1: Number of positive and negative scope changes per time stamp/baseline (M1).
	Positive scope change inclusion and negative scope change exclusion of the feature.
-Measurement 2: Time to feature removal (M2)
	Time between introduction of a feature and its removal completely.
-Measurement 3: Number of state changes per feature (M3)
-Measurement 4: Time to birth (M4)
	Delay in introduction of the feature.
-Measurement 5: Reason for scoping decision	
	Non numerical value specifying the reason of the scoping decision.

--  Wnuk & Gorschek “Obsolete Software Requirements”
This paper describes obsolete requirements phenomena in the software industry. As changing requirements become more obvious nowadays in order to stay competitive in software business where the requirements become obsolescence before completion of project, required amount of consideration should be given to requirement obsolescence. These obsolete requirements could drastically prolong project timelines resulting in increase of total cost of the product.
Even though there is research about the identifying such requirements (Volatile requirements (requirement that tend to change so often), scope creep (initially unidentified requirements that are identified later in the project which are every large in number), etc.). However identification of these requirements is not just sufficient this phenomenon of obsolete requirements should be addressed.This process is called requirement selection 


SEMINAR 4
---------

Assessing challenges of continuous integration in the context of software requirements breakdown a case study
------------------------------------------------------------------------

This paper discusses the challenges faced during continuous integration in agile practices. This is done by conducting a case study. This paper also considers software requirements breakdown and its influence on continuous integration. Continuous Integration is the concept of integration of small requirements or parts of a requirement several times in a day.Due to increase in a number of requirements and considering the frequency of the requirements changes, agile practices are considered most promising development methodology.This development methodology can be further improved by using continuous integration.Continuous integration in order to be effective it should have the support of  software requirements breakdown.Requirements should be small enough to facilitate continuous integration.This helps developers to test them independently before integration.Breakdown of a user story into smaller, clearer requirements with visual business and customer value is considered difficult task and many examples that verify this statement are provided by authors.During literature review, authors found that there are many problems that can occur by continuous integration.

> During this thesis, author focused on 
> 
>  - challenges of implements continuous integration in practice
>   
>  - challenges of software requirements breakdown in practice
>   
>  - influence of software requirements breakdown on continuous integration.

A case study is conducted by authors’ at **Ericsson**.

 Continuous integration is adapted by many teams at Ericsson and the process followed in the company is as follows.The company has different branches for development(Work Branch),testing(local latest version,pre-test Build),quality assurance.Any new feature or bug fix that is being developed,changes made are pushed into Work Branch.once the whole feature is developed changes are pushed to Local Latest Version branch here the new functionality is tested after the tests are passed these changes are pushed to pre-test Build branch here the regression testing is done.After these tests are completed then the changes are pushed to latest stable version.Quality assurance is done at each branch.
 
***Challenges identified during continuous integration:***
-Mindset:developers mindset which is influenced by scepticism,change of old habits(Continuous integration challenges old habits), early exposing work(less time to polish the code before integration) .
-Tools and infrastructure
-Testing challenges, Domain Adaptability, Understanding of Continuous Integration, Code Dependencies, Software Requirments breakdown challenges.


**Software Requirments breakdown** 
	Ericsson introduced cross-functional teams as a part of the agile transformation.These cross-functional teams contain operational product owners who decide the order of implementation of requirements and it's up to the teams breakdown the requirements.
***Challenges faced:***
-Requirements Abstraction, Alignment of requirements and test, customer value, Guiding principle.
Influence of software requirements breakdown on continuous Integration.
Authors received difference opinion about the necessity of Software breakdown in continuous integration.The necessity depends on the work that is being carried out.Breaking down the requirements to support continuous integration will come with certain implications .

**My View**: Continuous integration will support the development of the product.But in order to implement this process one should have a clear picture of what is being developed.Better planning is required to realize the advantages of the process.As the requirements gathered are from different levels of abstraction and has different customer value and business value breaking them will help in continuous integration.Another challenge is maintaining the quality of the product effective quality assurance measures should be in place to preserve the quality of the product.Another challenge is less feedback time this should be considered while planning the project.










