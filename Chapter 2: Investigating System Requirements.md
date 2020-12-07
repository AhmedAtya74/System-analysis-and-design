# Chapter Two: Investigating System Requirements

This blog concentrates on systems analysis activities (Core Process 3) and cover a wider range of concepts, tools, and techniques.

### Six core processes for system development life cycle (SDLC):

 1. Identify the problem and obtain approval.

 2. Plan and monitor the project.

 3. Discover and understand the details of the problem.

 4. Design the system components that satisfy the need.

 5. Build, test, and integrate system components.

 6. Complete system tests and then deploy the solution.
	

**Technology architecture:** the set of computing hardware, network hardware and topology, and system software—such as operating and database management systems employed by an organization
		 
**Application architecture:** the set of information systems (the software applications) the organization needs to support its strategic plan.


> ### Systems Analysis Activities:

the activities of the third core process, which is to discover and understand the details, The activities are as follows:

 #### 1. Gather detailed information:
 
 Systems analysts obtain information from people who will be using the system and 
 read nearly everything available about the existing system and obtain additional information by reviewing planning documents
 and policy statements and study existing systems, including their documentation and 
 looking at what other companies (particularly vendors) have done when faced with a similar business need.
 The analyst must become an expert in the business area the system will support.
 For example, if you are implementing an order-entry system, you need to become an expert on the way orders are processed
 
 #### 2. Define requirements:

 The analyst uses information gathered from users and documents to define
 requirements for the new system. System requirements include the functions the
 system must perform.
 Defining requirements is not just a matter of writing down facts and figures.
 Instead, the analyst creates models to record requirements, reviews the models with users and others, and refines and expands the models to reflect new
 or updated information
 
 #### 3. Prioritize requirements:
 
 Once the system requirements are well understood, it is important to establish
 which requirements are most crucial for the system. Sometimes, users request
 additional system functions that are desirable but not essential. However, users
 and analysts need to ask themselves which functions are truly important and
 which are fairly important but not absolutely required.

 Why prioritize the functions requested by the users?
 Resources are always limited and also help to determine the number, composition, and ordering of project iterations. High-priority requirements are often incorporated into       early project iterations

 If system requirements tend to expand as users make more suggestions called SCOPE CREEP

 #### 4. Develop user-interface dialogs:
 
 Users tend to be uncertain of many aspects of system requirements. Such requirements
 models as use cases, activity diagrams, and interaction diagrams can be developed based on user input, but it is often difficult for users to interpret and validate such         abstract models.

 requirements models as use cases, activity diagrams, and interaction diagrams

 In comparison, user validation of a user interface is much simpler and more
 reliable because the user can see and feel the system. To most users, the user
 interface is all that matters. Thus, developing user-interface dialogs is a powerful
 method of eliciting and documenting requirements.

 #### 5. Evaluate requirements with users:
 
 The processes of eliciting requirements, building models and prototypes, and evaluating them with users may repeat many times until requirements models and prototypes are         complete and accurate.
 
### System Requirements and FURPS:
 
 System requirements are all the activities the new system must perform or support and the constraints that the new system must meet.

 System requirements are divided into two categories:

 #### 1. functional requirements

 Functional requirements are the activities that the system must perform (i.e., the business uses to which the system will be applied).

 Identifying and describing all these business uses require a substantial amount of time and effort because the list of functions and their dependencies can be very complex.

 The functional requirements were defined by the list of use cases in general, but functional requirements are also based on the procedures and rules that an organization uses     to run its business.

 Discovering such rules is critical to the final design of the system. If this rule were not discovered, customers who had reliedon it in the past might become angry. Modifying   the system after customers start complaining is much more difficult and expensive than building in the rule from the start.


 #### 2. nonfunctional requirements

 Nonfunctional requirements are characteristics of the system other than those activities it must perform or support.

 It is not always easy to distinguish functional from nonfunctional requirements  One way to do so is to use a framework for identifying and classifying requirements.

 FURPS is an acronym that stands for functional, usability, reliability, performance, and security. The F in FURPS is equivalent to the functional requirements defined             previously.

##### The remaining categories (URPS) describe nonfunctional requirements as follows:

#### 2.1. usability requirements: 
describe operational characteristics related to users, such as the user interface, related work procedures, online help, and documentation.

#### 2.2. Reliability requirements:
describe the dependability of a system—how often a system exhibits such behaviors as service outages and incorrect processing and how it detects and recovers from those problems.

#### 2.3. Performance requirements:
describe operational characteristics related to measures of workload, such as throughput and response time.

#### 5.4. Security requirements:
describe how access to the application will be controlled and how data will be protected during storage and transmission. 

### Additional Requirements Categories:

 **FURPS+:** is an extension of FURPS that adds additional categories, including design constraints as well as implementation, system interface, physical, and supportability           requirements.

#### Requirements Categories:

1. Design constraints: describe restrictions to which the hardware and software must adhere.

2. Implementation requirements: describe constraints such as required programming languages and tools.

3. Interface requirements: describe interactions among systems.

4. Physical requirements: describe such characteristics of hardware as size, weight, power consumption, and operating conditions.

5. Supportability requirements: describe how a system is installed, configured, monitored, and updated.


### Stakeholders:

Stakeholders are your primary source of information for system requirements, who have an interest in the successful implementation of the system. Depending on the nature and scope of the system.

Each stakeholder group interacts with the system in different ways, and each has a unique perspective on system requirements. Before

gathering detailed information, the analyst identifies every type of stakeholder who has an interest in the new system.

#### Stakeholder category:
 1. internal stakeholders:
   persons within the organization who interact with the system or have a significant interest in its operation or success.

2.  External stakeholders are those outside the organization’s control and influence.

3. operational stakeholders persons who regularly interact with a system in the course of their jobs or lives.

4. executive stakeholders persons who don’t interact directly with the system but who either use information produced by the system or have a significant financial or other interest in its operation and success.

### clients: 
a person or group that provides the funding for the system development project.

The project team includes the client in its list of important stakeholders because the team must provide periodic status reviews to the client throughout development. 

#### Information-Gathering Techniques:

#### 1. Interviewing users and other stakeholders:

Interviewing is an effective way to understand business functions and business rules.

Systems analysts do:

#### 1.1. Prepare detailed questions.

#### 1.2. Meet with individuals or groups of users.

#### 1.3. Obtain and discuss answers to the questions.

#### 1.4. Document the answers.

#### 1.5. Follow up as needed in future meetings or interviews.

This process may take some time, so it usually requires multiple sessions with each of the users.

#### 1. Question Themes:

Three major themes that guide the analysts when they are asking questions to define system requirements:

#### 1.1 What Are the Business Processes?

The analyst must obtain a comprehensive list of all the business processes and carefully discern which of those functions are fundamental and which may possibly 		 
be eliminated.

#### 1.2 How Are the Business Processes Performed?

Determining how business processes are performed.

The goal is to define how the new system should support the function rather than how it supports it now.

The analyst must be able to help the user visualize new and more efficient approaches to performing the business processes.

#### 1.3. What Information Is Required?

  Some information inputs are formal; others are informal.

  the analyst should specifically ask about exceptions or unusual situations in order to identify additiona.

  An analyst must understand the nitty-gritty detail to develop a correct solution. 	 

   ### 2. Question Types:

#### 2.1. open-ended questions: 
encourage discussion and explanation —such as “How do you do this function?”.

#### 2.2. closed-ended questions: 
are used to get specific facts —such as “How many forms a day do you process?”.

#### 2.3. Focus of Questions—Current System or New?

 A significant question that faces all analysts is how much effort to expend studying and documenting the existing system.

 if a new system inherits many or all of the requirements of an existing system, then an analyst risks missing important requirements through insufficient study of the 

existing system. To minimize both risks, analysts must balance the review of current business functions with discovery of new system requirements.

###  4. Interview Preparation, Conduct, and Follow-Up: is a sample checklist that summarizes the major points to be covered

#### 4.1. Preparing for the Interview:
The first and most important step in preparing for an interview is to determine what you want to accomplish with this interview. Write down the objective and  		
determine which stakeholders should be interviewed.

 #### 4.2. Conducting the Interview:
 Limit the time of the interview for the benefit of the analyst(s) and stakeholder(s); stakeholders have other responsibilities, and the analysts can absorb onlyso
 much information at one time. It is better to have several shorter interviews than one long interview and data analyst must Look for exception and error                          conditions. Look for opportunities to ask “what if” questions

#### 4.3. Following up the Interview:
Follow-up is an important part of each interview. The first task is to absorb, understand, and document the information that was obtained. Generally, analysts document             the details of the interview by constructing models of the business processes and writing textual descriptions of nonfunctional requirements.


#### 2. Distribute and Collect Questionnaires: 
Questionnaires enable analysts to collect information from a large number of stakeholders.

Questionnaires are often used to obtain preliminary insight into stakeholder information needs, which helps to determine areas that need further research using other 		 methods.

 three types of questions:
 The first part has closed-ended questions to determine quantitative information. The second part consists of opinion questions in which respondents are asked whether 		they agree or disagree with the statement. Both types of questions are useful for tabulating and determining quantitative averages. The third part requests an 			explanation of a procedure or problem.

#### 3. Review Inputs, Outputs, and Procedures:

There are two sources of information about inputs, outputs, and procedures. One source is external to the organization—industry-wide professional organizations and other 	  
companies. It may not be easy to obtain information from other companies.

 Reviewing internal documents and procedures serves two purposes. First, it is a good way to get a preliminary understanding of the processes. existing inputs, outputs, 	  
 and documents can serve as visual aids for the interview.

#### 4. Observe and Document Business Processes:

 observing a business process in action will help you understand the business functions. However, while observing existing processes, you must also be able to visualize 	  
 the new system’s associated business processes.

### Models and Modeling:

Modeling is an important part of systems analysis and design and  Analysts build models to describe system requirements and use those models to communicate with

users and designers to ensure an understanding of the user’s requirements.

#### model: 
representation or abstraction of some aspect of a system.

Analysis and design models can be grouped into three generic types:

#### 1. textual models: text-based system models such as memos, reports, narratives, and lists to describe requirements that are detailed.

#### 2. graphical models: system models that use pictures and other graphical elements to create a diagram it's easier to user.

#### 3. mathematical models system models that describes requirements numerically or as mathematical expressions

Many graphical models used in system development are drawn according to the notation specified by the Unified Modeling Language (UML).

#### Unified Modeling Language (UML):
a standard set of information system model constructs and notations defined by the Object Management Group.

### Documenting Workflows with Activity Diagrams: 

As you gather information about business processes, you will need to document your results as a workflow. A workflow is the sequence of work steps that complete one business     
transaction or customer request.

One effective way to capture this information is with a UML activity diagram. 

An activity diagram describes the various user (or system) activities, the person or component that completes each activity, and the sequential flow of these activities.

#### Synchronization bar: an activity diagram component that either splits a control path into multiple concurrent paths or recombines concurrent paths.

Swimlane an activity diagram component that divides the workflow activities into groups showing which agent performs which activity.



