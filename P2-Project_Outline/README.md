# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/modules/assignments/project-outline)

## Submission Instructions

### Overview
The purpose of this project is to more easily view St. Louis City Police Department Crime Data.
The current system generates a PDF of the monthly report, organized by Official City Neighborhood, in Alphabetical order. 
The City wide totals are on the last page of the document (pg. 91) so you have to scroll 
or page down to the bottom to see the general information.

By using this app, the landing page (index), would display the City wide totals for latest
available month and year to date by default.
Additionally, there would be a dropdown to allow you to see results of a single neighborhood.

As conversations about local crime rates are ongoing, I envision many interested users
including local citizens and community leaders, perhaps even the City of St. Louis itself.

To meet Liftoff requirements, an optional sign up/registration page will be offered.
Users who choose to, will sign up with minimum requirements (name, email, password). They 
can eventually (not mvp) opt in to an email reminder when admin loads a new month of data.

### Features

Home Page: Default view would include navigation bar (Home, Signup page, Admin page);
           A View of latest months crime data displayed for (allCrime());
              This would require page to communicate with DB, retrieve  and display info (READ).  

Query Tool: A Drop down for altering the search to a single neighborhood (allCrimeByNeighborhood(neighborhoodId));
              This would require additional controller methods beyond allCrime().
           

Optional Registration: User who choose can register for an account, eventually to receive notifications.
           This would include a signup page and a registration successful page.
           This would include abilities to  signup (CREATE), remove user (DELETE), edit user (UPDATE) info to fulfill all other CRUD functions


This should be enough to roll out a MVP.

Future improvements:
Advancements in data display and Query selection (more selections, better granular insight into details), these would be 
iterative improvements and extensions of primary Feature (Data Query tool);

Future features would be graphical representation of data, and mapping of data points to a map image.

I hope to give Admins access to an eventual data import tool (files come as monthly csv). Import process should run as 
a method to check for new file, and import it automatically.

### Technologies

Java (Back End)
JavaScript/Java (Front End)
Springboot (Framework)
Hibernate (Object to DB Mapping)
MySQL/Postgres (DB)
Thymeleaf/AngularJS (Front End Display) (TBD)

### What I'll Have to Learn

REST API (How to) I want to implement REST API for better understanding separation of control, and demonstrating 
programming abilities.
Server Side Controllers (API Provider) For a better understanding of how to handle server side processing, cycle of operations.
Client Side Processing (API Consumer) For a better understanding of how to handle client side. Decoupling should give me chance to 
add/remove features on client side, without affecting the data or server side of operations. Ideally, coding front ends
in different languages, using same API endpoints should be another good demonstration of abilities.


### Project Tracker

[Trello Board for SLMPD data project](https://trello.com/b/RXWPkudo/slmpd-data-visualization-tool)
