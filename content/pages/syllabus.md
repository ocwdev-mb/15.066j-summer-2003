---
content_type: page
description: ''
learning_resource_types: []
ocw_type: CourseSection
title: Syllabus
uid: b91650b6-c23e-65c3-d3d2-1d080801c811
---

A complete syllabus is presented below in text format. Syllabi for the portions of the course taught by Prof. Stephen Graves or Prof. Jérémie Gallien are available separately in PDF format:

*   General Information about 15.066J and calendar for first portion of class, taught by Prof. Stephen Graves ({{% resource_link a1542b42-275b-90fa-c37c-6d21f874e0bc "PDF" %}})
*   Information and calendar for second portion of class (sessions 19-29), taught by Prof. Jérémie Gallien ({{% resource_link 26754964-974b-f39e-fb00-6465b7c38162 "PDF" %}})

General Information
-------------------

This part of the syllabus applies to the entire course, especially those portions taught by Prof. Stephen Graves.

### Objectives

The first objective is to introduce modeling, optimization and simulation, as it applies to the study and analysis of manufacturing systems for decision support. The introduction of optimization models and algorithms provide a framework to think about a wide range of issues that arise in manufacturing systems. Probabilistic simulation methods are also a powerful tool for the study, analysis and design of manufacturing systems. The second objective is to expose students to a wide range of applications for these methods and models, and to integrate this material with their introduction to operations management. The third objective is to 'refresh' the student's analytic thinking and background in anticipation of the rest of the Leaders for Manufacturing (LFM) curriculum.

### Topics

The topics to be covered include a subset of the following: linear programming, sensitivity analysis for linear programs, network flow problems, introduction to integer and non-linear programming, Lagrange multipliers, simulation, and computer applications. Examples are drawn from manufacturing processes and manufacturing systems.

### Text

Baker, Kenneth R. _Optimization: A Spreadsheet-Based Approach._ Duxbury Press, 2003.

The textbook is not yet published but the author and publisher have granted us permission to use the manuscript, based on our commitment to provide some feedback. As the name suggests, the textbook will cover optimization topics. For the simulation component of the class, we will distribute readings and notes.

We also mention some other very useful books that we have used in prior years:

*   _Introduction to Mathematical Programming_, by W. L. Winston, PWS Kent, 1995, which does a great job on algorithms and model formulations;
*   _Practical Management Science_, by W. L. Winston and S. C. Albright, Duxbury, second edition, 2001, which is excellent in describing a wide range of applications as well as illustrating spreadsheet modeling;
*   _The Science of Decision Making_, by E. V. Denardo, Wiley 2002, which was used last year and provides a problem-based approach both to optimization as well as probability applications;
*   and _Data, Models, and Decisions: The Fundamentals of Management Science_, by D. Bertsimas and R. Freund, South-Western College Publishing, 2000, which was written for the Sloan MBA core class in Data, Models and Decisions. Indeed, we will use some of the cases and other material from this book.

### Course Requirements

Grading will be based on performance on assignments, exams, and class participation.

Individual:  
Midterm (25%)  
Book Report (10%)

Group:  
Problem Sets (25%)  
Group Project (30%)

Individual/Group:  
Case Preparations, Class Participation, and Feedback on Text (10%)

15.066J Systems Optimization and Analysis: Simulation Module Outline and Logistics, Cases and Examples

The following is the syllabus for that portion of 15.066J taught by Prof. Jérémie Gallien, Sessions 19-29.

### Outline and Logistics

Digital simulation deals with the design and analysis of computer models in order to gain knowledge about, and optimize real systems. In particular, digital simulation enables numerical experiments that do hold some actual predictive value, but would be too costly, time consuming, risky or just plain impossible to directly conduct on a real system. Simulation can be an extremely powerful tool and is becoming quite widespread (LFM second year internships seem to increasingly involve simulation models!), yet few in industry seem well trained in the design, implementation and interpretation of a useful simulation experiment. The simulation module in 15.066J is an application-oriented introduction to static and dynamic discrete-event simulation for executive decision-making. This module has two primary goals:

1.  Develop the practical skills necessary to design, implement and analyze discrete-event simulation systems;
2.  Cover the basic theory underlying discrete-event simulation methodologies, in order to enable a critical understanding of simulation output in managerial environments and build the foundations necessary to quickly adapt to future advances in simulation technology.

Because of its first objective, this module involves a sustained workload and many opportunities for hands-on practice. This year we will use two software packages for in-class examples, tutorials and homework assignments throughout the course: Crystal Ball® (CB) for static (Monte-Carlo) simulations, and SIMUL8® (S8) for dynamic discrete-event simulations (the exact meaning of these terms will be explained in the first lecture). While I have primarily selected these software packages among dozens of others because they are both relatively easy to learn, they also happen to be quite widespread and powerful. For support regarding the actual use and learning of these software packages, you should normally consult the following sources (in this order):

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
ORDER
{{< thclose >}}
{{< thopen >}}
CRYSTAL BALL®
{{< thclose >}}
{{< thopen >}}
SIMUL8®
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
1
{{< tdclose >}}
{{< tdopen >}}
Help File (Software Help Menu)
{{< tdclose >}}
{{< tdopen >}}
Help File (Software Help Menu)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
2
{{< tdclose >}}
{{< tdopen >}}
User Manual
{{< tdclose >}}
{{< tdopen >}}
User Manual
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
3
{{< tdclose >}}
{{< tdopen >}}
Online FAQ available at  
[Decisioneering Online Knowledgebase](http://www.decisioneering.com/)
{{< tdclose >}}
{{< tdopen >}}
Online Q&A Forum available at  
[SIMUL8® Cafe](http://www.simul8.com/)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
4
{{< tdclose >}}
{{< tdopen >}}
Teaching Assistant
{{< tdclose >}}
{{< tdopen >}}
Teaching Assistant
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
5
{{< tdclose >}}
{{< tdopen >}}
Professor Gallien
{{< tdclose >}}
{{< tdopen >}}
Professor Gallien
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

However, if for some reason you find yourself stuck or struggling for more than 30 minutes and sources 1-3 do not yield any quick answer/fix, please do escalate to sources 4 and 5 at that point (again, the goal is to learn about simulation, not software interface). In addition, the module will contain in-class introduction/demos to both CB and S8, and I have assigned as a required reading for Class 4 the tutorial "Introduction to SIMUL8®" which I have adapted from some of SIMUL8 Corporation's training material.

This module consists of 7 lectures and 3 tutorials. The {{% resource_link f8c0d4e0-c157-0358-2762-3e7b50631c7f "schedule" %}}, {{% resource_link f8c0d4e0-c157-0358-2762-3e7b50631c7f "list of topics covered" %}}, {{% resource_link a475a835-2b88-c8a9-eb80-ed3d5213bdd4 "reading" %}} and {{% resource_link 0245c9eb-9868-8276-516b-fdf64623a690 "homework assignments" %}} are listed elsewhere on this web site.

All assignments may be prepared as part of your regular study group/team (and not beyond!), but you should individually be able to answer questions in class about every part of the work that has been done by your team. The three homework assignments, Introduction to SIMUL8® document, Ontario Gateway and Human Genome cases will be posted on the class server, and the readings/assignment ClearPictures, Inc. refers to a mini case described later in the present document. The two Probability / Statistics Review Checklists consist of making sure on your own (or as part of your study group) that you are comfortable with a number of concepts covered earlier this summer in 15.064 Engineering Probability and Statistics before walking into class that day. More specifically before the corresponding classes you should have a good understanding of the following concepts:

Probability / Statistics Review 1 Checklist:

*   definition of continuous and discrete random variables;
*   pdf, cdf;
*   law of large numbers; and
*   statistical estimators of mean and variance;

Probability / Statistics Review 2 Checklist:

*   central limit theorem;
*   fractile of a distribution; and
*   construction of confidence intervals for the mean.

Don't skip this! Besides helping you and the class as a whole to make the most out of the simulation lecture that day, it is also a great opportunity to ensure that you have internalized these important concepts covered in 15.064, which should prove useful to you time and time again at MIT and beyond.

An important milestone in the module is the software implementation of the ClearPictures model on Class 4: this assignment represent the first time in the module that you will have the opportunity to implement a somewhat realistic discrete-event simulation model. It has been partly designed to help you become familiar with S8 before you will need to use this software package even more extensively (when preparing Homework 2 and the Human Genome Project case in particular), so I strongly urge you to prepare it thoroughly - even if you don't get the ClearPictures model 100% right for Class 4, it is very important that you try!

Finally, an anonymous feedback survey will be posted on the class server at the end of the module for you to complete - this is a key point in helping me to continuously improve the quality of this module (and thus the learning experience of future LFM students), so I ask that you please fill it completely and honestly.