# Test Design Techniques

In this post, you will learn about five commonly-used test design techniques
that will help you ensure maximum test coverage and reduce time spent on 
testing activities.

## What is Test Design?

> **Test design** is the activity that derives and specifies test cases from test conditions. (ISTQB)

## When and Why do We Need Test Design?

Test design process helps QA engineers keep on track of the requirements coverage.

We need test design: 
- to develop tests that help to detect serious errors; 
- to take a thoughtful approach to testing and avoid wasting resources; 
- to minimize the number of tests required to validate the product.

## The Main Test Design Techniques

The benefits of using test design techniques is an opportunity to create 
fewer tests while ensuring broad requirements coverage. 

There are a dozen of test design techniques you can use, but let’s focus
 on the most popular ones:

- Black-box test design techniques
  + Equivalent Class Partitioning
  + Boundary Value Analysis
  + State Transition
+ Pairwise Testing
+ Error Guessing

### Equivalent Class Partitioning

> **Equivalent class partitioning** or **equivalence partitioning** or **partition testing** A black-box test technique in which test cases are designed to exercise
 equivalence partitions by using one representative member of each partition.
 (ISTQB)

The equivalent class partitioning implies splitting test data into classes, 
where all elements are similar in some way. This technique makes sense 
only if the components are similar and can fit in a common group. Choosing 
this technique means that we are going to test only a few values from every 
group. 

Remember that doesn’t guarantee that the rest of the values not 
covered by the tests will be bug-free. We only assume that using several 
elements from the group will be quite illustrative. 

The equivalent class partitioning is a good solution for cases when you 
deal with a large volume of incoming data or numerous identical input 
variations. Otherwise, it might make sense to cover a product with tests 
more closely.


### Boundary Value Analysis

> **Boundary value analysis** is a black-box test technique in which test cases are designed based on 
boundary values. (ISTQB) 

> **Boundary value** is a minimum or maximum value of an ordered equivalence partition. (ISTQB)

The boundary value analysis is similar to the previous technique. Some 
may even say it is based on the equivalent class partitioning. So what 
makes the boundary value analysis different? We still group data in 
equivalent classes but don’t test values from a particular class only. 
Instead, we check boundary values, those that are at the ‘borders’ of 
the classes. The same logic works perfectly for integration testing. 
We check smaller elements during unit testing, and on the next level, 
the errors are likely to pop up at the unit junctions.

### State Transition

> **State transition** is a black-box test technique in which test cases are designed to exercise
 elements of a state transition model. (ISTQB)

The state transition visualizes the states of a software system at 
different time frames and stages of usage. Visual information is simpler 
to perceive compared to verbal description. Therefore, the state 
transition allows you to come up with ultimate test coverage more 
quickly. This technique is effective for creating test suites for 
systems that have many state variations. It will be helpful if you test 
a sequence of events with a finite number of input options.

### Pairwise Testing

> **Pairwise testing** is a black-box test technique in which test cases are designed to exercise
pairs of parameter-value pairs. (ISTQB)

The pairwise testing is considered the most difficult and confusing of 
the five test design techniques. And there is a good reason for this. 
The pairwise testing is based on mathematical algorithms, namely 
combinatorics. It makes it possible to create unique pairs and test a 
huge amount of incoming data in different combinations, but the 
calculations might get complicated. To cover the maximum of features 
with test scripts that will require minimum time for testing, you need 
to match data correctly, combining pairs in a specific way based on the 
calculations.


### Error Guessing

> **Error guessing** is a test technique in which tests are derived on the basis of the tester's 
knowledge of past failures, or general knowledge of failure modes. (ISTQB)

Error guessing is the most experimental practice of all, usually applied 
along with another test design technique. In error guessing, a QA 
engineer predicts where errors are likely to appear, relying on previous 
experience, knowledge of the system, and product requirements. Thus, a 
QA specialist is to identify spots where defects tend to accumulate and 
pay increased attention to those areas.

**AN EXAMPLE OF ERROR GUESSING** 

As a rule, QA engineers start with testing for common mistakes, such as: 

- Entering blank spaces in text fields. 
- Pressing the Submit button without entering data. 
- Entering invalid parameters (email address instead of a phone number, etc.). 
- Uploading files that exceed the maximum limit. 
- … and so on. 

The more experience a QA specialist has, the more error guessing scenarios 
they can come up with quickly.

### TO SUM UP 

A correctly chosen test design technique helps to use QA 
resources smartly. Very often, QA engineers need to combine several test 
design techniques to ensure the most effective coverage. The correct 
combination always depends on a specific project. Some specialists 
choose a particular approach intuitively, without referencing the theory
 much. Well, with years, you start to do some things reflexively

### Sources: 

- 5 Test Design Techniques QA Engineers Should Know - QA Madness 
Software testing company
- ISTQB Glossary
