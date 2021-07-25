# **Introduction**


Objective
My overall objective with this project is the following:

>"To create a CRUD application with utilisation of supporting tools,
methodologies and technologies that encapsulate all core modules
covered during training." - QA Community

#### Proposal:

For this project I have decided to develop an app that generates D&D story prompts based on; tarot cards, their symbols and meaning and inspiration from illustrations where the user is able to generate a random card and story and add their own personal ideas.
I have been thinking about making it a full tarot deck, but have decided to find about 5 most interesting cards and only use those as a minimum.

#### Requirements:
-A Trello board (or equivalent Kanban board tech) with full expansion
on user stories, use cases and tasks needed to complete the project.
It could also provide a record of any issues or risks that you faced
creating your project.

-A relational database used to store data persistently for the
project, this database needs to have at least 2 tables in it, to
demonstrate your understanding, you are also required to model a
relationship.

-Clear Documentation from a design phase describing the architecture
you will use for you project as well as a detailed Risk Assessment.
A functional CRUD application created in Python, following best
practices and design principles, that meets the requirements set on
your Kanban Board

-Fully designed test suites for the application you are creating, as
well as automated tests for validation of the application. You must
provide high test coverage in your backend and provide consistent
reports and evidence to support a TDD approach.

-A functioning front-end website and integrated API's, using Flask.
Code fully integrated into a Version Control System using the
Feature-Branch model which will subsequently be built through a CI
server and deployed to a cloud-based virtual machine.


#### My tech stack will be as follows:

Kanban Board: Trello 
Database: GCP SQL Server
Programming language: Python
Unit Testing with Python (Pytest)
Integration Testing with Python (Selenium)
Front-end: Flask (HTML)
Version Control: Git
CI Server: Jenkins
Cloud server: GCP Compute Engine





#### My planned CRUD is as follows:

Read/view

Generate new

Add

Refresh





<p align="center">
  
#### **My Risk Assessment**
  </p>
  
![](https://i.imgur.com/HRoeBy9.png)

#### Link to my Trello Board:
https://trello.com/b/GemvxO82
It changed a lot since I first started it!
#### ER

My planned ER looked as follows, hovewer - half way through making it I realised that the login functionality is not something I want to implement into my project, so I removed it and made a new one.
![](https://i.imgur.com/0UVNVFe.png)

Below is my finished ER diagram and how I would like my database to look like. It's simplified and I find that it suits the purpose more.
![](https://i.imgur.com/9ka4DvQ.png)
#### Here is what and how I actually implemented it into my code
![](https://i.imgur.com/qxomCQS.png)

#### Testing
I used Jenkins to perform my Pytest testing. Below is a screenshot of the results which got 100% coverage.

![image](https://user-images.githubusercontent.com/86067593/126895038-0038e237-32fb-4db2-a042-bf01099743ad.png)
