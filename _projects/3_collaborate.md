---
layout: page
title: Collaborate
description: collaboration template 
img: assets/img/consulting.png
importance: 3
category: work
---



### Motivating Example

To illustrate a model for collaboration, let’s consider a problem in an
enterprise setting. The problem pertains to data from an IT help desk. I
picked this dataset because it is real world data and has a very
representative set of issues that need to be addressed before developing
a data science solution. I have used [this
dataset](https://archive.ics.uci.edu/dataset/498/incident+management+process+enriched+event+log)
in a [machine learning
setting](https://www.sciencedirect.com/science/article/pii/S2666827021001195),
but let’s consider an analytics setting for this discussion. You or the
business entity you represent have problems with your help desk. You
have decided to take a data driven approach to understanding the
underlying problems with the help desk. In IT speak, you have identified
an *organizational key result*: **Improve Help Desk Efficiency**. You
propose doing this with the following strategic tasks:

-   Baseline performance of the help desk teams

-   Understand the ticket load for each team

-   Undestand normal and abnormal ticket resolution paths for each group

Ok, the planning is done, now you want to get this done. You don’t have
a data scientist at hand for doing this, you decide to [get in touch
with me](https://calendly.com/rajiv-sambasivan/30min?month=2023-08) and
describe your problem. I suggest that I need to look at the data and
possibly ask your data team and tech team a couple of questions to
understand the data. You take a representative segment of data, for
example the second quarter of ticket resolution activity and deanonymize
it. You ask your data team for any supporting documentation they have on
the data and you put this on cloud storage, say an S3 bucket or box and
send me a link.

### Data Analysis

I spend some time looking at the data and come up with some approaches
to get to the information you need to do the analysis that is of
relevance to you. In particular, I determine the time it takes to
resolve the ticket from the ticket resolution database. I then spend
some time picking the appropriate statistical visualizations for the
information that you need from this analysis. I discuss the approach
with you and your tech team. In the process of coming up with this
approach, I have questions about the data and your goals. We have a few
discussions to get this worked out. We agree on what is to be built.

### The Implementation

I create a [git repository](https://github.com/rajivsam/example_ITSM) for the project and start implementing the
project. For this project, we decide on the following visualizations:

1.  A ticket resolution time distribution plot by group. You pick a team
    in the help desk organization and then generate a distribution plot
    for the resolution times for that team.

2.  An empirical cumulative distribution of the ticket resolution time
    for that group. This plot can be used to determine the ticket
    resolution with a degree of confidence. For example, you could say
    that this group will resolve tickets with 100 hours with 95 percent
    confidence.

### Iterative Solution Refinement

We schedule a demonstration and work through the deliveries. We agree
on a time to review and revisit with questions if needed - as many as
you need. Once we agree on an initial baseline, you can either fork the
repository or I can transfer it over to your organization.

### The Vital Ingredients

For me, a successful iteration needs a couple of key ingredients. To
begin with, a clear discussion of the business (or engineering) problem
you want to solve with data science. It is ok if you don’t have a
concise summary, but at the very least, I would expect to understand the
most important outcome you want to achieve. The next key ingredient is
the data. A representative sample of the the data for your problem is
essential for me to start crafting a solution. Your data and technical
team’s support in answering questions is also needed. This can of course
be worked asynchronously via email or chat. If you prefer, we can work
updates and questions on a schedule.

### The Cost

To begin exploring the fit for your project, you can set up an
appointment to chat. The first hour of discussion - either one full
session or two 30 minute sessions is free. This conversation and the
above sample hopefully gives you enough information to make a decision to
start your project. Depending on the scope of work for your project, we
can then either work on a deliverable basis or a time and materials
basis. This really depends on how well defined your project requirements
are.

### The Prologue

So the analytics reports developed in this example can help summarize
the ticket resolution activity for each help desk team. Looking at the
results, it looks like many groups that get a lot of tickets have
clustering tendencies in ticket resolution times. There is a cluster
(usually bigger than the others) of tickets that are resolved quickly
and smaller clusters of tickets that are more difficult to resolve.
Armed with this tool you can look at the groups that have challenges or
complaints. Help desk managers also get a probablistic calibration of
ticket resolution times for each group. This can help them get at making
reliable estimates for their customers.

Once the challenges and issues have been identified, your team can then
implement strategies to address these issues. The next quarter comes around.
You now use the tool to assess the effectiveness of the changes you have
implemented. Much of machine learning and analytic solutions have this
repetitive nature. In fact, I am working on a solution to leverage and
optimize solutions such as this to leverage this fact. So hopefully,
that can make using such tools easier.

I hope this page has piqued your curiosity enough to have a chat and
explore using my services for your project. Thank you for your time.


