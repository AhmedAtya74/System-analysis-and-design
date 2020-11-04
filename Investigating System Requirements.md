Chapter Two: Investigating System Requirements

Six core processes for system development life cycle (SDLC):

 1. Identify the problem and obtain approval.

 2. Plan and monitor the project.

 3. Discover and understand the details of the problem.

 4. Design the system components that satisfy the need.

 5. Build, test, and integrate system components.

 6 Complete system tests and then deploy the solution.
	

This blog concentrates on systems analysis activities (Core Process 3) and cover a wider range of concepts, tools, and techniques.

Technology architecture:

the set of computing hardware, network hardware and topology, and system software—such as operating and database management systems employed by an organization
		 

Application architecture:

the set of information systems (the software applications) the organization needs to support its strategic plan.


Systems Analysis Activities:

the activities of the third core process, which is to discover and understand the details, The activities are as follows:

 1. Gather detailed information:
 
Systems analysts obtain information from people who will be using the system and 
read nearly everything available about the existing system and obtain additional information by reviewing planning documents
and policy statements and study existing systems, including their documentation and 
looking at what other companies (particularly vendors) have done when faced with a similar business need.
The analyst must become an expert in the business area the system will support.
For example, if you are implementing an order-entry system, you need to become an expert on the way orders are processed
 
 2. Define requirements:

The analyst uses information gathered from users and documents to define
requirements for the new system. System requirements include the functions the
system must perform.
Defining requirements is not just a matter of writing down facts and figures.
Instead, the analyst creates models to record requirements, reviews the models with users and others, and refines and expands the models to reflect new
or updated information
 
 3. Prioritize requirements:
 
Once the system requirements are well understood, it is important to establish
which requirements are most crucial for the system. Sometimes, users request
additional system functions that are desirable but not essential. However, users
and analysts need to ask themselves which functions are truly important and
which are fairly important but not absolutely required.

Why prioritize the functions requested by the users?
Resources are always limited and also help to determine the number, composition, and ordering of project iterations. High-priority requirements are often incorporated into early project iterations

If system requirements tend to expand as users make more suggestions called SCOPE CREEP

 4. Develop user-interface dialogs:
 
Users tend to be uncertain of many aspects of system requirements. Such requirements
models as use cases, activity diagrams, and interaction diagrams can be developed based on user input, but it is often difficult for users to interpret and validate such abstract models.

requirements models as use cases, activity diagrams, and interaction diagrams

In comparison, user validation of a user interface is much simpler and more
reliable because the user can see and feel the system. To most users, the user
interface is all that matters. Thus, developing user-interface dialogs is a powerful
method of eliciting and documenting requirements.

 5. Evaluate requirements with users:
 
The processes of eliciting requirements, building models and prototypes, and evaluating them with users may repeat many times until requirements models and prototypes are complete and accurate.
 
System Requirements and FURPS:
 
System requirements are all the activities the new system must perform or support and the constraints that the new system must meet.

System requirements are divided into two categories:

 1. functional requirements

Functional requirements are the activities that the system must perform (i.e., the business uses to which the system will be applied).

Identifying and describing all these business uses require a substantial amount of time and effort because the list of functions and their dependencies can be very complex.

The functional requirements were defined by the list of use cases in general, but functional requirements are also based on the procedures and rules that an organization uses to run its business.

Discovering such rules is critical to the final design of the system. If this rule were not discovered, customers who had reliedon it in the past might become angry. Modifying the system after customers start complaining is much more difficult and expensive than building in the rule from the start.


 2. nonfunctional requirements

Nonfunctional requirements are characteristics of the system other than those activities it must perform or support.

It is not always easy to distinguish functional from nonfunctional requirements  One way to do so is to use a framework for identifying and classifying requirements.

FURPS is an acronym that stands for functional, usability, reliability, performance, and security. The F in FURPS is equivalent to the functional requirements defined previously.

The remaining categories (URPS) describe nonfunctional requirements as follows:

1. usability requirements: describe operational characteristics related to users, such as the user interface, related work procedures, online help, and documentation.

2. Reliability requirements describe the dependability of a system—how often a system exhibits such behaviors as service outages and incorrect processing and how it detects and recovers from those problems.

3. Performance requirements describe operational characteristics related to measures of workload, such as throughput and response time.

4. Security requirements describe how access to the application will be controlled and how data will be protected during storage and transmission. 

Additional Requirements Categories:

FURPS+: is an extension of FURPS that adds additional categories, including design constraints as well as implementation, system interface, physical, and supportability requirements.

Requirements Categories:

1. Design constraints describe restrictions to which the hardware and software must adhere.

2. Implementation requirements describe constraints such as required programming languages and tools.

3. Interface requirements describe interactions among systems.

4. Physical requirements describe such characteristics of hardware as size, weight, power consumption, and operating conditions.

5. Supportability requirements describe how a system is installed, configured, monitored, and updated.



