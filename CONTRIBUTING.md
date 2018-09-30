---
layout: page
title: Contributing to the UO Data Science Club

---

Welcome to the Contributing guideline for the UO Data Science Club. Thanks for taking the time to contribute! 

The following is a set of guidelines for contributing, whether it be by teaching a lesson, fixing the website, helping to plan and organize our various events, or taking on a leadership role.

### Table of Contents

1. [About the UO Data Science Club](#about-the-uo-data-science-club)
    - [Code of Conduct](#code-of-conduct)

2. [How You Can Contribute](#how-you-can-contribute)
    - [Leading a Lesson](#leading-a-lesson)
    - [Creating the Content](#creating-the-content)
    - [Fixing and Updating the Website](#fixing-and-updating-the-website)
    - [Other Ways to Get Involved](#other-ways-to-get-involved)

-----
# About the UO Data Science Club

Welcome! We are a student-led group formed to provide a supportive space for collaboration on code-based projects. At Data Science Club, graduate students present informal lessons, bring analysis or code issues to workshop as a group, and work together on projects related to coding or data science. More information can be found on our [website](https://uodatascience.github.io/club/), and in our [archived lessons](https://blogs.uoregon.edu/rclub/2013/10/03/welcome/).

## Code of Conduct

We adhere to a [Code of Conduct](https://github.com/uodatascience/club/blob/gh-pages/codeOfConduct.md)
and by participating, you agree to also uphold this code. Please report any unacceptable behaviour to any of the club facilitators. 

-----
# How You Can Contribute

## Leading a Lesson

The Mozilla Study Group
handbook [**here**](https://mozillascience.github.io/studyGroupHandbook/lessons.html#reuse)
and [**here**](https://mozillascience.github.io/studyGroupHandbook/event-types.html#workalong)
has several very good points about making a lesson. This section summarizes bits
of the handbook, but also includes additions. Check out the
[lesson bank too](https://github.com/mozillascience/studyGroupLessons/issues).

### Creating the Content

+ **Minimal use of slides**: The most effective sessions are ones that are very
hands-on. We strongly encourage *live-coding*](#more-on-live-coding) as a 
teaching method; it's best to keep slides to a minimum or avoid them completely.
+ **Keep in mind beginners**: Make few assumptions about the knowledge of the audience,
unless specified that this is an intermediate level lesson, requiring prior knowledge.
Keep it simple. Don't attempt to cover too much material in a single session.
+ **Use Built-in Datasets**: Use built-in sample datasets instead of requiring
attendees to download files. 

#### More on Live-Coding

Live-coding is a hands-on method of teaching coding to a group in which the instructor 
shares their screen with the group and types all commands on their computer while the 
group follows along. Live-coding is a very effective teaching technique: it forces the 
instructor to go slowly and ensures that participants get to try out every command 
being used. It allows learners to experience common errors themselves and debug them 
in a supportive environment, to explore variations on material as they go, and to 
immediately check their understanding by trying things hands-on. 

Live-coding is a technique used by [Software Carpentry](https://software-carpentry.org/about/). 
Software Carpentry has lots of great resources explaining the why and how of live-coding:
+ [10 tips and tricks for instructing and teaching by means of live coding](https://software-carpentry.org/blog/2016/04/tips-tricks-live-coding.html)
+ The Software Carpentry [instructor training manual](http://carpentries.github.io/instructor-training/) 
includes many resources about programming education.


### Tips for Leading a Lesson

+ **Arrive early**: Come 5 minutes before the lesson starts to set up.
+ **Introduce yourself**: Start by introducing yourself and perhaps why you're teaching this lesson.
+ **Stay on time**
+ **Start from the very beginning**: Briefly explain all aspects of the what you are doing when live-coding including:
    - show how to open the program or IDE (e.g. RStudio/Jupyter Notebook/Shell or Terminal/etc)
    - how to run code (e.g. press `Shift+Enter` in the Jupyter Notebook)
    - if this is an intro lesson, explain the concept of an IDE or shell
    - importing modules and packages such as  `import numpy as np` or `library(dplyr)`

+ **Live-coding**: Use of slides is minimal, majority of lesson involves writing the code WITH the audience during the lesson
+ **Stay on topic**: There is only one hour, if a question arises that is off-topic, you can always suggest discussing afterwards.
+ **Check in with participants**

-----

## Fixing and updating the website

There are two ways of fixing or adding to the website, either by:

- Creating an [Issue](https://github.com/uodatascience/club/issues/new)
describing the problem or enhancement. This is technically not doing anything
yourself, just recommending something to be done.
- Submitting a Pull Request from a clone of this repo. This way takes a bit more work and requires knowledge of Git and likely HTML. But we
 would appreciate any help! No harm in giving it a try! That's a beauty of using Git, it's hard to mess up and break something.

If you want to view the website before submitting a Pull Request to make sure
your changes are as you expect, you'll need to:

- Install Jekyll by following these [instructions](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/).
- To build the site locally, run `jekyll serve`.
- The built site can also be viewed at your forked version
(`https:://yourusername.github.io/club`).

----

## Other Ways to Get Involved

### Taking On A Leadership Role

The planning and organization of the Data Science Club is done by our graduate student facilitators. This is done on a volunteer basis, and we are always looking for people of all skill levels to help create content and organize meetings.
