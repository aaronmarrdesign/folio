---
published: true
layout: article
title: Managing Web Projects
abstract: This post aims to illustrate the basics of managing a Web project. While there may be different approaches, depending on the size of the team or company culture, this post will aim to set out the basic principles of runnning a successful Web project.  
articleimage: sketchpad.jpeg
author_twitter: aaronmarruk
author: Aaron Marr
categories:
- articles
---

#### Project Constraints

The "Silly Quality Triangle" illustrates the fundemental aspects of a project and their relationship to one another. Time represents the available time in which to deliver the project, cost represents the amount of money or resources available, and scope represents the feature set that the project must deliver in order to be viable. In the middle is quality, which is affected by all the other aspects, and represents the overall quality and  viablity of the project. [1]http://www.projectsmart.co.uk/project-management-scope-triangle.html

![Alt The quality triangle](/blog/img/quality-triangle.jpg)

The constraints illustrated by the triangle are often competing: increased scope usually increases the timescale and cost, less time available could mean increase in cost or reduced scope, and less money and resources available would usually mean an increased time scale or reduced scope. [2]http://www.sqa.org.uk/e-learning/ProjMan03CD/page_13.htm [WAS Book]

* Reducing the time available always affects the quality or scope. 
* Less money and resources available usually equates to reduced scope, rather than less time spent. 
* Increasing the overall quality should equate to an increase in timescale and resources, rather than a reduced scope.[WAS Book]

#### Minimum Viable Product and Phase Development

To keep on top of project deadlines the concept of "minimum viable product" becomes important. Minimum viable product, in essence, is the deliverable that achives all the requirements set out in the scope, without including any non-essential features. 

Phase development is the process of delivering the minimum viable product in the first instance, with any non-essential features left until a later stage of development, sometimes until after release.

#### Iterative Development

Iterative development is the process of developing features in an iterative process over time. This means that you don't have to get everything perfect right away. Features may be developed and fine tuned over time. 

However, it is difficult to iterate the foundations of a project so carefull planning and research must be done at the beginning of a project to ensure the foundations are correct. Changing the foundations of a project is more costly the closer to production that a project is. This can be illustrated by the "cost of change curve" illustrated below:

![Alt Cost of change](/blog/img/costofchange.jpg)

* Scoping errors found during the scope phase are inexpensive to fix. You merely change a portion of your scope. 

* Scoping errors found during devlopment are more expensive to fix, you need to update your scope, design, and potentially scrap portions of your work done in development. 

* Errors found during the traditional testing stage at the end of production are very expensive to fix; you need to update your scoping documentation and scrap large portions of work done in development. 

* Finally, errors that get through to production are very expensive to fix. You'll need to send out updates, fix databases, restore old data, and rewrite or reprint manuals.

An Iterative process relies on our ability to successfully focus on something for a short period of time, and takes into account our inability to accurately predict how theory becomes reality. By taking short, iterative steps, we can focus on creating brilliance one move at a time, and can evlove our app as we get a better feel for the features that succeed and those that don't turn out as we hoped.

The iterative process happens on two levels. At the higher level, new app features are developed incrementally. For each release the approximate stages of this book are followed: some research, then interface design, coding, a working release and marketing. Check the customer reactions, learn and repeat.

![Alt Cost of change](/blog/img/iterativedevelopment.jpg)

On the lower level, each of the stages is a mini set of iterations in itself, punctuated by testing that informs us whether or not further cycles are required. This holds especially true at the interface and development stages, where a skeleton design or chunk of code can gradually be refined with more detail as it undergoes testing.

If your project has a deadline each high-level iteration should be allotted a specific number of days, so that you can be sure to fit in a number of full iterations, and the learning that comes from them, over the lifetime of the project.
Each iteration should last for a fixed length of time, so that your team can develop a rhythm; you will quickly adapt to the recurring deadlines and become adept at estimating how much functionality can be produced in each.
The exact length of an iteration can range from a week to a month. Your team will need to decide on the best length for them based on a number of factors:

* **The complexity of the app**
An iteration needs to be long enough for a team to sometimes produce fairly advanced features. Even if these are only developed to a minimum quality or prototype level, they may take weeks. Similarly, an iteration should not be so short that the majority of it is spent on planning, testing and deployment, with little time for the actual development.

* **Customer expectations**
If you’re developing an app for a client, they may influence
how often they expect to see movement and change. This is not necessarily a negative factor if the customer can participate more easily in shaping the development of the application to meet their expectations.

* **Team pressure and rhythm**
A deadline needs to positively pressure the team into productivity without being unrealistic and causing the team to opt-out of
the process.

#### Risk Driven Development

To decide on the deliverables for an iteration, a risk-driven approach is superior to choosing the low-hanging, easy features first. When taking this approach, you should first develop the high-priority/high-risk features followed by high-priority/low-risk and, finally, low-priority/low-risk. Low-priority/high-risk features should be avoided altogether until the app is a proven success.

High risk features can be identified by:
* A new or unkown technology
* Ambigous requirements
* A complex graphical interface
* Tasks that cannot be assigned accurate estimates in a development timescale.