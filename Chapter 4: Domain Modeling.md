# Chapter 4: Domain Modeling

## Overview:
This chapter focuses on another key concept that defines requirements: things in the problem domain of system users. 

## “Things” in the Problem Domain:
**Domain classes** are what end users deal with when they do their work—for example, products, sales, shippers, shipments, and customers.
**Problem domain** is the specific area of the user’s business that is included within the scope of the new system. The new system involves working with and **remembering these things.**

## There are many techniques for identifying the important things in the problem domain:
### 1. the brainstorming technique:
  In this technique, an analyst should ask the users to discuss the types of things they work with routinely and identify different types of things.
  #### types of things:
  1. Tangible things are often the most obvious.
  2. Role played by a person.
  3. Organizational units, such as a division, department, or workgroup.
  4. Site or location, such as a warehouse, a store, or a branch office.
  5. An incident or an interaction **"association"**.

#### the steps to follow when using the brainstorming technique:
1. Identify a user and a set of use cases or user stories.
2. Brainstorm with the user to identify things involved when carrying out the use case—that is, things about which information should be captured by the system.
3. categorization based on the types of things.
4. Continue to work with all types of users and stakeholders to expand the brainstorming list.
5. Merge the results, eliminate any duplicates, and compile an initial list.

**NOTE: Many things in the problem domain can fit into more than one type**
### 2. The Noun Technique:
a technique used to identify things in the problem domain by finding and classifying the **nouns** in a dialog or description.
#### the steps to follow when using the noun technique:
1. identify all nouns in a dialog or description.
2. Using other information from existing systems, current procedures, and current reports or forms.
3. you will need to refine list of nouns.
4. Create a master list of all nouns identified and then note whether each one should be included(in domain), excluded(out of domain), or researched(ask stakeholders about that).
5. Review the list with users, stakeholders, and team members and then refine the list of things in the problem domain.

### Attributes of Things:
The specific pieces of information are called **attributes**.
**Identifier or key** an attribute the value of which uniquely identifies an individual thing or object.
**compound attribute** an attribute that consists of **multiple** pieces of information but is best treated in the aggregate.

### Associations among Things:
After recording and refining the list of things and determining potential attributes, the analyst needs to set all  relationships among things.
**association** a term, in UML, that describes a naturally occurring relationship between specific things.

**multiplicity** in UML, a measure of the number of links in a particular association between a thing (object) and one or more other things (objects)
  1. one to one
  2. one to many
  3. many to one

It is important to describe not just the multiplicity but also the range of possible values of the multiplicity.
For example, a particular customer might not ever place an order. In this case, there are zero associations. Alternatively, the customer might place one order, meaning one association exists. Finally, the customer might place two, three, or even more orders. The relationship for a customer placing an order can have a
range of zero, one, or more, usually indicated as zero or more. The zero is the minimum multiplicity, and more is the maximum multiplicity. These terms are referred to as multiplicity constraints.

# STUDY UML DIAGRAM such as use cases, class diagram, sequence diagram, activity diagram, state machine diagram 
.






















