# University of Oregon Data Science Club

Welcome to the University of Oregon Data Science Club! 

### Table of Contents

1. [About the UO Data Science Club](#who-we-are)
    - [Code of Conduct](#code-of-conduct)
2. [How You Can Contribute](#how-you-can-contribute)
    - [Leading a Lesson](#leading-a-lesson)
    - [Creating the Content](#creating-the-content)
    - [Fixing and Updating the Website](#fixing-and-updating-the-website)

### Who We Are
 
 We are a student-led group formed to provide a supportive space for collaboration on code-based projects. At Data Science Club, graduate students present informal lessons, bring analysis or code issues to workshop as a group, and work together on projects related to coding or data science. More information can be found on our [website](https://uodatascience.github.io/club/), and in our [archived lessons](https://blogs.uoregon.edu/rclub/2013/10/03/welcome/).

### Code of Conduct

We adhere to a [Code of Conduct](https://github.com/uodatascience/club/blob/gh-pages/codeOfConduct.md)
and by participating, you agree to also uphold this code. Please report any unacceptable behaviour to any of the club facilitators. 

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

### Misc
* **Join our Gitter Chat:** There are Study Groups all around the world. We use an online [Gitter Chat](https://gitter.im/mozillascience/studyGroup) to connect and share resources and ideas (you can sign in with GitHub, or using a Twitter ID if you're not set up on GitHub just yet). If you'd like to say hello, please introduce yourself in the chat, tell us where you are, and what you're thinking about or planning for your new Study Group. We're looking forward to meeting you.
* **Read the code of conduct:** this Study Group Program is for everyone - we abide by a [set of rules](https://www.mozillascience.org/code-of-conduct/) that require everyone be treated with respect. Help us make a space where everyone feels welcome, and we'll all have a better time!
* **Watch this repo:** up in the top right, there's a button that says 'Watch'; click it, and set yourself to 'Watching'. This will send you email notifications of new discussions; if you don't want email, but would like an alert just on GitHub, change the setting in Settings -> Notification Center (Settings is the little cog in the top right).
 
If you are new to GitHub, don't worry, [there's an introduction to it here](https://mozillascience.github.io/study-group-orientation/3.1-collab-vers-github.html). 
