
# Welcome to my portfolio!

I'm Maria Bezobiuk and I'm a junior QA/QC engineer, at the time - 
manual software tester. 

<img src="images/photo-bio.jpg" height="200"/>

I'm glad you are here. :smile: It means, you were interested in my CV or social page
 and were curious, what is the level of my skills.

These are examples of my work product.

The site was tested [newtea.ua](https://newtea.ua/)

Every test activity starts from analysis of project´s idea which realisation 
is started with definition of requirements.

-------

## Requirements
 
>The requirements should be documented, actionable, measurable, testable,
> traceable, related to identified business needs or opportunities, 
> and defined to a level of detail sufficient for system design.


 ------

## User stories

**User story** is a requirement written from a user position and can 
include any functional or non-functional user´s need, the reason behind it,
 and acceptance criteria.
 
There are some variants to write down user stories:  
- As a \<role\> I can \<capability\>, so that \<receive benefit\>
- In order to \<receive benefit\> as a \<role\>, I can \<goal\/desire\>
- As \<who\> \<when\> \<where\>, I want \<what\> because \<why\> 
 
[file with user stories](docfiles/requirements-to-functionality.pdf)

[file with user stories to UI](docfiles/requirements-UI.pdf)

------

## Use case diagram

The logic of some relationships between the use cases, actors, and systems 
can be visualised in **use case digram**. It´s usually simple and shows what 
behavior is expected in software underdeveloped. We can say, it is a primary 
form of system or software requirements and helps us design a system from 
the end user's perspective. 

> A use case is a scenario that describes the use of a system by an actor 
to accomplish a specific goal.

Use cases help us

- capture the system's functional requirements from the users' perspective
- actively involve users in the requirements-gathering process
- provide the basis for identifying major classes and their relationships
- serve as the foundation for developing system test cases

<img src="docfiles/use-case-diagram-newtea.png" width="700" alt="Use case diagram"/>

<p align="center"> Use case diagram </p>


------

## Use Case

A **use case** is a list of actions or event steps typically defining the 
interactions between a role (known in the Unified Modeling Language (UML)
 as an actor) and a system to achieve a goal. 

A usage scenario for a piece of software; often used in the plural to 
suggest situations where a piece of software may be useful.

Use cases organize requirements to form a narrative of how users relate 
to and use a system. Hence they focus on user goals and how interacting 
with a system satisfies the goals.
  
Use case flows describe sequences of interactions, and may be worded in 
terms of a formal model. A use case is intended to provide sufficient 
detail for it to be understood on its own.  

Template for use case:

- Title: "goal the use case is trying to satisfy"
- Main Success Scenario: numbered list of steps  
  - Step: "a simple statement of the interaction between the actor and a system"
- Extensions: separately numbered lists, one per Extension
  - Extension: "a condition that results in different interactions from .. 
the main success scenario". An extension from main step 3 is numbered 3a, etc.

Or

- Title (goal)
- Primary Actor
- Scope
- Level
- (Story): the body of the use case is simply a paragraph or two of text, 
informally describing what happens.

We can highlight such types of use cases:  

- System use cases specify the requirements of a system to be developed.  
- Business use cases focus on a business organisation instead of a software
 system. They are used to specify business models and business process 
 requirements in the context of business process reengineering initiatives.  
- Essential use cases, also called abstract use cases, describe the potential 
intents of the actors and how the system addresses these, without defining 
any sequence or describing a scenario. This practice was developed with 
the aim of supporting user-centric design and avoiding to induce bias about 
the user-interface in the early stage of the system specifications.  

------

## State-Transition Diagram

**State-transition diagram (STD)** is a visualisation of all the possible *states* 
of system, each variant of *event* from outside the system that cause changes 
in system, and *transition* to another state as a result of this event. 
Also on STD we can see the conditions that must be fulfilled before the 
transition will occure - *guards* and *actions* - activities undertaken 
during the life of an system.

Only valid state transitions may be utilized. 
 
It is used in the object-oriented modeling and developing as well as use case diagram.

For the tester there are three main questions to test these diagrams:

- Does the diagram follow the rules?
- Is the diagram correct?
- Does everything in this diagram trace back correctly and completely to 
its   predecessor?" and "Is everything in the predecessor reflected 
completely and   correctly in this diagram?"


<img src="docfiles/state-transition-diagram-registration.jpg" width="700" alt="State Transition Diagram"/>
<!--- State Transition Diagram for registration on newtea.ua.--->


------

## Decision Table

**Decision table** is a visual way to represent multiple conditions and 
actions for them or they combinations.  
Essentially it is a structured exercise to formulate requirements when 
dealing with complex business rules.

They provide a clear method to verify testing of all pertinent combinations
 to ensure that all possible conditions, relationships, and constraints 
 are handled by the software under test.

<p align="right">
<img src="docfiles/decision-table-registration.jpg" width="700" alt="Decision table"/>
Decision table for registration on newtea.ua.
</p>

------

## Checklist

**Checklist** is a simpliest form of test documentation, I think. 
It´s a list of test activities needed to be done with checkbox done or not. 
It can contains a columns ¨Pass/Fail¨ and ¨Coments¨ for tester´s comfort :\) 

File with [checklist](docfiles/checklist-main-newtea.pdf) for main page https://newtea.ua testing


------


 fgntynm





------


## Testcases

