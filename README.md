# Learning Path - Python, Django

## Command Line Basics

**Session** on CLI.

[Command Line Crash Course](https://learnpythonthehardway.org/book/appendixa.html)

[Commonly Used Linux Commands](https://www.thegeekstuff.com/2010/11/50-linux-commands/)

## Version Control Systems

**Session** on Git and Github

[Version Control with Git - Udacity Video Course](https://in.udacity.com/course/version-control-with-git--ud123)

[GitHub & Collaboration - Udacity Video Course](https://in.udacity.com/course/github-collaboration--ud456)

[Learn enough Git to be dangerous](https://www.learnenough.com/git-tutorial)

[Practice Link](https://learngitbranching.js.org/) - Practice the **Learn Git branching** section

[Gamified Tutorial](https://www.katacoda.com/courses/git) - Learn the most common practices in the modern day Git Workflow.

## HTML and CSS

Start with [Learn to Code HTML and CSS by Shay Howe](https://learn.shayhowe.com/)

In particular read the following sections and complete the exercises.

HTMl & CSS

* Lesson 1: Building your first web page
* Lesson 2: Getting to know HTML
* Lesson 3: Getting to know CSS
* Lesson 4: Opening the Box Model
* Lesson 5: Positioning content

Advanced HTML & CSS

* Lesson 3: Complex Selectors
* Lesson 4: Responsive Web Design

Resources for Flex and Grid Layouts:

[CSS Flex Video](https://www.youtube.com/watch?v=JJSoEo8JSnc)

[CSS Grid Video](https://www.youtube.com/watch?v=jV8B24rSN5o)

Resources for Web Development for any Topic:

[Mozilla Web Docs](https://developer.mozilla.org/en-US/)

### Projects:

**Responsive Portfolio Website**

	Build your portfolio website using your knowledge of HTML and CSS. The display should work in all resolutions.

	Use your knowledge of responsive media queries, CSS flex and CSS grid for handling multi column layouts.

#### CSS Reference

[A Visual Reference to CSS](https://cssreference.io/)

**Themed Ecommerce Website**

	Recreate the following website: https://shop.polymer-project.org/

	Please make a Gitlab repository:

	The website should have 5 pages:

	1. Home Page
	2. Item listing page
	3. Single Item Page
	4. Cart Page
	5. Checkout Page

	Some pointers:

	* Please work *mobile-first*.
	* Add README.md and .gitignore files to your repository.
	* Make a styles.css. Include it in each html page. Put the style classes here. They can be gradually reused.
	* Work page by page, section by section, element by element. Break things down to the smallest step. Ask yourself what you don't know and figure it out.
	* Try to work with high energy and complete things.


## JavaScript and Ecosytem

### JavaScript Basics
[Introduction to JavaScript - Udacity](https://in.udacity.com/course/intro-to-javascript--ud803)

### ECMAScript 6 Basics
[Introduction to ES6 - Udacity](https://www.udacity.com/course/es6-javascript-improved--ud356)

### Recommended Projects:

**ToDo List in JavaScript**

	Implement a todo list with ordering


**Session**: Recap on Functions, Scope and Callbacks.

**Session** on JavaScript Environment Setup - JS, Node, NPM. Introduction to JavaScript.

### Developer Tools

[Getting Started with Developer Tools](https://developers.google.com/web/tools/chrome-devtools/)

## Python

**Session** on environment setup - virtualenv, pip and packaging.

[Introduction to Python - thenewboston](https://www.youtube.com/watch?v=HBxCHonP6Ro&list=PL6gx4Cwl9DGAcbMi1sH6oAMk4JHw91mC_)

[Official Python Tutorial](https://docs.python.org/3/tutorial/index.html)

Go through [PEP-8 Style Guide](https://www.python.org/dev/peps/pep-0008/)


### Unit Testing in Python

**Session** Unit testing

**Session** Code Retreat


## Data Project - Round 1

Get the [IPL Dataset](https://www.kaggle.com/manasgarg/ipl)

	In this data assignment you will transform raw data from IPL into graphs that will convey some meaning / analysis. For each part of this assignment you will have 2 parts -

	Download both csv files from https://www.kaggle.com/manasgarg/ipl

	Code python functions that will transform the raw csv data into a data structure in a format suitable for plotting with matplotlib.

	Generate the following plots ...

	1. Plot the number of matches played per year of all the years in IPL.
	2. Plot a stacked bar chart of matches won of all teams over all the years of IPL.
	3. For the year 2016 plot the extra runs conceded per team.
	4. For the year 2015 plot the top economical bowlers.
	5. Discuss a "Story" you want to tell with the given data. As with part 1, prepare the data structure and plot with matplotlib.

### Time and Space Complexity

[Time Complexity Summary](https://www.youtube.com/playlist?list=PL2_aWCzGMAwI9HK8YPVBjElbLbI3ufctn) (30 minutes) on mycodeschool - 4 videos

[Complexity for recursive programs](https://www.youtube.com/watch?v=ncpTxqK35PI) (8 minutes) on mycodeschool

(Optional) Additionally you can refer to the Algorithms and Data Structures course by Ravindrababu Ravula on youtube (First 6 videos cover ): [https://www.youtube.com/watch?v=aGjL7YXI31Q&list=PLEbnTDJUr_IeHYw_sfBOJ6gk5pie0yP-0](https://www.youtube.com/watch?v=aGjL7YXI31Q&list=PLEbnTDJUr_IeHYw_sfBOJ6gk5pie0yP-0)

Create an account on [Interviewbit](https://www.interviewbit.com) and solve the practice problems in the Time Complexity section.

### Python Decorators


[Decorators](https://www.youtube.com/watch?v=FsAPt_9Bf3U)


### SOLID Architecture

Watch videos.

[Overview of SOLID](https://www.youtube.com/watch?v=TMuno5RZNeE)

[SOLID principles](https://www.youtube.com/playlist?list=PL6n9fhu94yhXjG1w2blMXUzyDrZ_eyOme)

	Practice Data Munging problem (http://codekata.com/kata/kata04-data-munging).

	Create proper classes. Try to apply OOPs concepts and do it using minimum amount of code.

### SQL

Read up on RDBMS.

	Rewrite the data project.

	Write a script to import csv into table. Keep your TDD code same. But the source should be MySQL.

### MVC

Go through Model View Controller design pattern. Implement it in Core Python using [https://www.giacomodebidda.com/mvc-pattern-in-python-introduction-and-basicmodel/#conclusion](https://www.giacomodebidda.com/mvc-pattern-in-python-introduction-and-basicmodel/#conclusion)

## Flask, Celery, ElasticSearch, Deployment

	Implement your choice of project with Flask.

	First write user personas and user stories.

	Example:

	Blogging Engine with Authentication in Flask

	* As a reader I should be able to (henceforth ISBAT) see all blogs.
	* As a reader ISBAT register and register myself as a blogger. (Sign Up)
	* As a reader ISBAT login and become blogger. (Authentication)
	* As a blogger ISBAT create a blog post.
	* As a blogger ISBAT delete my own blog post.
	* As a blogger ISBAT update my blog post.

	Bonus:

	* As a reader ISBAT see an error page if I enter wrong URL. (Error Handling)
	* As a reader ISBAT search any text. (Full text Search)
	* As a reader ISBAT export blogpost as text file. (Use Celery for background jobs)

	Deployment:

	* Deploy your application using heroku.
	* Deploy your application on a Linux server (preferably create and EC2 machine using an AWS account)
	* Deploy your application using docker.

## Django

[Introduction to Django - thenewboston](https://www.youtube.com/playlist?list=PL6gx4Cwl9DGBlmzzFcLgDhKTTfNLfX1IK)

[Official Django Tutorial](https://docs.djangoproject.com/en/2.0/intro/tutorial01/)

	Django Poll App (Django Docs)

## Data Project - Round 2, Ansible

	Django Data Project
	* Use Django Custom Command to import data from csv into database
	* Use Django ORM for making queries
	* Use 5 routes for creating data, use Redis for caching
	* Use 5 routes for using Highcharts to plot data on the frontend
	* Use Ansible script to deploy on AWS


## Web Architecture Overview

**Session** on Web Architecture Overview


### REST

**Session** on APIs and REST.

1. Basics of [REST APIs](https://en.wikipedia.org/wiki/Representational_state_transfer)
2. [RESTful Design](https://blog.philipphauer.de/restful-api-design-best-practices/) - Best practices to use
3. [Building good APIs](http://conversation.bigbinary.com/) - Using appropriate HTTP Response codes

### Django REST Framework

Introduction to [Django REST framework](http://www.django-rest-framework.org/). Complete the quickstart and tutorial.

	Update Django Data Project with DRF

	- Create apis for matches
	- Use 4 separate branches and implement:
	  -- method based views
	  -- class based views
	  -- mixins based views
	  -- generics
	- Create apis for deliveries
	  -- implement hyperlinking with matches
	  -- implement pagination
	- Implement viewsets and routers


### Potential additions - Microservices, Messaging Queues, Load Balancers, Stress Testing

## Capstone Project

The final project of the bootcamp.

Deliverables:

1. User Personas - [How to define a User Persona](https://careerfoundry.com/en/blog/ux-design/how-to-define-a-user-persona/)
2. User Stories - [Writing User Stories](https://www.mountaingoatsoftware.com/agile/user-stories)
3. Wireframes - [Website Wireframes](https://en.wikipedia.org/wiki/Website_wireframe)
4. API Contracts
5. Trello Board for managing and prioritising user stories
6. Gitlab Repository for managing the code
7. Deployment link for the project

Thanks.
