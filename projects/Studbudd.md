---
layout: project
type: project
image: images/MS3-Thumb.png
title: StudBudd
permalink: projects/StudBudd
# All dates must be YYYY-MM-DD format!
date: 2018-12-09
labels:
  - User Interfaces
  - Semantic UI
  - Meteor/Mongo
summary: Worked in a team of 5 to develop a webapp that assists students at UH Manoa to find study groups.
---

<img class="ui large centered rounded image" src="../images/MS3-LP.png">

The StudBudd project was a project done in my ICS:314 Software Engineering class and served to be the culmination of all the topics and concepts that I have learned throughout the year. Studbudd is meant to be the bridge between students at UH Manoa to help find other students and classmates to effectively study with. Utilizing some social media aspects, the user can log into the webpage and view other students’ profiles and use the information there to set up study dates with each other. My four other group members and I set off to create our vision and with delicate balancing of school life, work life, and each other we have produced a functional product that we deem worthy to showcase what we have learned in this class.

<img class="ui large centered rounded image" src="../images/Studbudd3-Transperent.png">

## Milestone 1 ##

We split the work into 3 parts and each part had a goal in mind. The goal for our first Milestone was to create mockup pages on the site along with a sort-of functional landing page and some group bonding exercises. The group exercises were used to establish meeting times, discovering each other’s’ strengths and weaknesses when it comes to this class, and the foundation of what our project has become. We decided on a name, a color scheme, assigned each other issues, and created the github.io page to showcase our development. For this milestone, I oversaw the landing page middle menu creation along with setting up our CSS functions to use later in the site. The first Milestone was the easiest of the three as creating the landing page was just utilizing HTML and Semantic UI-React functions and the creation of the CSS page was just gathering the proper fonts, colors, and other miscellaneous functions we may use. The main part of the first Milestone was to be sure that everyone was on the same page and that we can move forward as one.

## Milestone 2

Milestone 2 was a jump in difficulty as we decided to implement our back-end collections. We each took a slice of the back-end collection pie and made sure that by the end of this milestone the mockup pages we created from the first milestone were going to have increased functionality. Basically, what that meant was make sure that the page can pull information from our default collections. The component I oversaw was the creation of the Calendar Component. The calendar component was to be used as a more intuitive way to view a student’s availability for an easier way to set up study dates. This component was designed to be a simple 7 column table each labeled as a respective day of the week and to be color coded to showcase more visibly if that student was available on a particular day. This proved to be difficult for the team as our knowledge on the back-end collections was very basic at the time however we all pulled through and finished our goal by the end of the milestone.

## Milestone 3

If Milestone 1 was the user interaction with the site itself and Milestone 2 was the back-end interaction with the information on the site this Milestone goal would be the user interaction to the back-end collections and be sure that the web-app didn’t break from this. For Milestone 3 I was again in charge of making sure the calendar component works for every user and along with general bug testing of the interaction between user and collection. The calendar component now showcases whether the user is available on a certain day and colors the cell to be either green or red based on if they are available or not. This calendar functionality was then given to all users that create a profile on the web-app and I added editing functionality to make sure the user can edit their availability if they need it. The bug testing, I mentioned previously was mainly making sure that the page redirects to a page where the user can edit only THIER own components making sure that a random user can’t edit anyone else’s profile page. The id function that we were using definitely caused the most of our issues within the site and thorough vigorous testing we found the issue lay with the fact that there is a latency issue between retrieving our site and retrieving our collection, this made it so that our web-app constantly broke if you reloaded the page without logging out and was definitely a feature that we did not want to keep. The fix I found was the be sure that all collections were “ready” to pull from before the web-app loaded to be sure that the id function was never undefined and break our site. At the end of our troubles we did some general touchups with CSS and made a functional web-app that we are all proud of.

## Conclusion

In conclusion, Studbudd became the web-app we wanted it to be. It showcased mine and my group members capabilities to create a working product within a time constraint and became a project that we can all say that we are proud of.


You can view the Source Code [here](https://github.com/studbudd/studbudd)
You can view the Github.io page [here](https://studbudd.github.io/)
