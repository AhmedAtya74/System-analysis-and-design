## Chapter 3: Identifying User Stories and Use Cases 
### Intoduction
In this chapter we discus about how to define the system’s functional and nonfunctional requirements and techniques for documenting the functional requirements 
by creating a variety of models.

### User Stories and Use Cases:
Identifying user stories and use cases is a key task
when defining functional requirements because these form the basis for the list
of functions the system needs to carry out.

**User story**: what a user does as part of his or her work and **describes user goals** when using the system.

***The standard template for a user story looks like this:*** “As a [**role played**], I want to [**goal or desire**] so that [**reason or benefit**].” (ex... “As a *teller*, I want to make a *deposit* to quickly *serve more customers*.”)

A final part of a user story is the **acceptance criteria:** These indicate **the features** that must be present for the user to be
satisfied with the resulting implementation. **They focus on functionality, *not* on features or user-interface design**. 

 **Use case:** is an activity the system performs in response to a request by a user.
 
 ### Use Cases and the User Goal Technique:
 
The most **common** technique for identifying use cases.

User stories will help analysts identify and define use cases.
One approach to identifying use cases, called the **user goal technique:** is to ask users to describe their goals for using the new or updated system.

**The user goal technique for identifying use cases includes these steps:**
1. Identify all the potential users for the new system.
2. Classify the potential users in terms of their functional role (e.g., shipping,marketing, sales).
3. Further classify potential users by organizational level (e.g., operational,management, executive).
4. Interview each type of user to determine the specific goals they will have when using the new system.
5. Create a list of preliminary use cases organized by type of user.
6. Look for duplicates with similar use case names and resolve inconsistencies.
7. Identify where different types of users need the same use cases.
8. Review the completed list with each type of user and then with interested stakeholders.


### Use Cases and Event Decomposition Technique:
The most **comprehensive** technique for identifying use cases.

**The event decomposition technique:** begins by identifying all the business events the information system responds to, with each event leading to a use case, (ex. customer wants to update some info).

**Elementary business processes (EBPs)**: the most fundamental task in a business process, which leaves the system and data in a quiescent state; usually performed by one person in response to a business event, (ex. Search for item).

 **Event:** occurs at a specific time and place, can be described, and should be remembered by the system.
 
***Event Decomposition Technique:***
When defining the requirements for a system, it is useful to begin by asking, “What business events occur that will require the system to respond?”, (ex. A customer triggers two events:
customer pays a bill, Send late notices)


### Types of Events:
#### 1. External Events: is an event that occurs outside the system—usually initiated by an external agent or actor.

**actor:** is a person or organizational unit that **supplies or receives** data from the system.
 
To identify the key external events, the analyst first tries to identify all the external agents that might want something from the system.
When describing external events, it is important to **name the event** so the external agent is clearly defined. The description should also include the **action** that the external agent wants to pursue.

**Important external events** can also result from the wants and needs of ** people or organizational units inside the company**

#### 2.Temporal Events: an event that occurs as a result of reaching a point in time(ex. at point in time system will send notify to user about specfic somthing).

These events are different from external events in that the system should **automatically** produce the required output without being told to do so.In other words, **no external agent** or actor is making demands, but the system is supposed to generate information or other outputs when they are needed.

The analyst begins identifying temporal events by asking about **specific deadlines** that the system must accommodate. **What outputs are produced at that deadline? What other processing might be required at that deadline?**

Temporal events **do not have to occur on a fixed date.** They can occur **after a defined period of time has elapsed. For example, a bill might be given to a customer when a sale has occurred. If the bill has not been paid within 15 days, the system might send a late notice.

#### 3. State Events: an event that occurs when something happens inside the system that triggers some process.
**State events are also called "internal" events.**
Events are similar to temporal events, except the point in time cannot be defined.

### Identifying Events:
Defining the events that affect a system is **not always easy**, but some guidelines can help an analyst think through the process.
#### Events Versus Prior Conditions and Responses:
It is sometimes difficult to distinguish between an event and part of a sequence of prior conditions that leads up to the event.
Events are effect on the system follow these and identify the event
Customer thinks about getting a new shirt then Customer drives to the mall then Customer tries on a shirt at Sears then Customer goes to
Walmart then **Customer buys(this event will effect on the system) a shirt.**

#### The Sequence of Events: Tracing a Transaction’s Life Cycle:
A useful method for identifying events is to trace the sequence of events that might occur for a specific external agent or actor.

#### Technology-Dependent Events and System Controls:
the analyst is concerned about events that are important to the system, but do not directly concern users or transactions.
Such events typically involve design choices or system controls. During analysis, the analyst should temporarily ignore these events. However, they are important later for design.
Most of these physical system events involve **system controls**, which are checks or safety procedures put in place to protect the integrity of the system.

**The perfect technology assumption:** states that events should be included during analysis only if the system would be required to respond under perfect conditions.

### Steps in the Event Decomposition Technique:
1. Consider the external events in the system environment that require a response from the system.
2. For each external event, identify and name the use case that the system requires.
3. Consider the temporal events that require a response from the system.
4. For each temporal event, identify and name the use case that the system requires and then establish the point of time that will trigger the use case.
5. Consider the state events that the system might respond to.
6. For each state event, identify and name the use case that the system requires and then define the state change.
7. When events and use cases are defined, check to see if they are required as part of analysis by using the perfect technology assumption. Do not include
events that involve such system controls as login, logout, change password, and backup or restore the database, as these are put in as system controls.


