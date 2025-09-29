# Django

## Django Tutorial

The best reference is the [Official Documentation](https://docs.djangoproject.com/en/).

First do the Poll App from the official documentation. Then do the IPL project.

Reference Videos (old but covers the basics well) - [https://www.youtube.com/watch?v=F5mRW0jo-U4](https://www.youtube.com/watch?v=F5mRW0jo-U4)

## Django IPL Project

Objective:

* Get familiar with Django MVC
* Get familiar with Django ORM - migrations, queries with joins and aggregations, using transactions

Step 1:

Take only the IPL dataset. Not the other ones.

* Make sure you have setup tables correctly having foreign key relationships.
* Create a custom Django command and import the dataset into tables. Use atomic transactions.

Questions:
* What is the use of a transaction?
* Why atomic transactions?

Step 2:

Create four routes in a views.py that calculate results using Django ORM queries and return JSON:

* Number of matches played per year for all the years in IPL.
* Number of matches won per team per year in IPL.
* Extra runs conceded per team in the year 2016
* Top 10 economical bowlers in the year 2015

Step 3:

Have another set of four routes for displaying the charts which hit the previous four routes and use HighCharts to render. You may have to figure out Django templates for this step.

### Django Review Points

1. Settings file
- What is secret key?
- What are the default Django apps inside it? Are there more?
- What is middleware? What are different kinds of middleware? Read up a little on each security issue.
- Read up on [Django Security](https://docs.djangoproject.com/en/4.0/topics/security/)
- CSRF
- XSS
- Click Jacking
- Any other middleware that is there
- What is (WSGI)[https://en.wikipedia.org/wiki/Web_Server_Gateway_Interface]?

2. Models file
- What is ondelete Cascade?
- A broad understanding of [Fields](https://docs.djangoproject.com/en/4.0/ref/models/fields/) and [Validators](https://docs.djangoproject.com/en/4.0/ref/validators/) available to you
- Understanding the difference between Python module and Python class?

3. Django ORM
- Using ORM queries in Django Shell
- Turning ORM to SQL in Django Shell
- What are Aggregations?
- What are Annotations?
- What is a migration file? Why is it needed?
- What are SQL transactions? (non ORM concept)
- What are atomic transactions?

## Individual Project

Check the document on Software Requirements. Create user personas, user stories and a tentative database diagram for your project.

Implement the stories 1 by 1.


## Django REST Framework

Introduction to [Django REST framework](http://www.django-rest-framework.org/). Complete the quickstart and tutorial.

#### Django version of the Data Project.

In this project, you will use the same datasets as the previous Data Projects. In this case, Django will be the focus of your work.

#### Scope out the project

In consultation with your mentor write out the user stories for this project.

#### Part 1: Data Loader, with Django custom command.
Write a [custom django-admin command](https://docs.djangoproject.com/en/3.1/howto/custom-management-commands/) to load all the data from the CSV source file.

** NOTE ** your Django project and app should already be created and models should be written.

#### Part 2: Django Admin

Configure Django Admin to Add/Modify/Delete data points and also related data like Umpires / Country Unions etc.

#### Part 3: Web API

In this case, the parameters of the plot can be selected by the user.

For example, if the plot is filtered by year, then provide a dropdown in which the user can select the year of the plot.

Another example if your plot shows the population for "SAARC" then provide a drop-down, with a few other country unions.
