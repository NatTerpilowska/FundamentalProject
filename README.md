* [Introduction](https://github.com/NatTerpilowska/WIP-FundamentalProject#introduction)
* [Proposal](https://github.com/NatTerpilowska/WIP-FundamentalProject#proposal)
* [Requirements](https://github.com/NatTerpilowska/WIP-FundamentalProject#requirements)
* [My tech stack](https://github.com/NatTerpilowska/WIP-FundamentalProject#my-tech-stack-will-be-as-follows)
* [CRUD](https://github.com/NatTerpilowska/WIP-FundamentalProject#my-crud-is-as-follows)
* [Risk Assessment](https://github.com/NatTerpilowska/WIP-FundamentalProject#my-risk-assessment)
* [Trello Board](https://github.com/NatTerpilowska/WIP-FundamentalProject#link-to-my-trello-board)
* [ER Diagram](https://github.com/NatTerpilowska/WIP-FundamentalProject#er)
* [ER Implementation](https://github.com/NatTerpilowska/WIP-FundamentalProject#here-is-what-and-how-i-actually-implemented-it-into-my-code)
* [Testing](https://github.com/NatTerpilowska/WIP-FundamentalProject#testing)
* [Frond End and Functions](https://github.com/NatTerpilowska/WIP-FundamentalProject#functions-and-front-end)
* [Future Improvements](https://github.com/NatTerpilowska/WIP-FundamentalProject#future-improvements)
* [Acknowledgements](https://github.com/NatTerpilowska/WIP-FundamentalProject/blob/main/README.md#acknowledgements)
# **Introduction**


Objective
My overall objective with this project is the following:

>"To create a CRUD application with utilisation of supporting tools,
methodologies and technologies that encapsulate all core modules
covered during training." - QA Community

#### Proposal:

For this project I have decided to develop an app for D&D story prompts based on; tarot cards, their symbols and meaning and inspiration from illustrations.

#### Requirements:
* A Trello board (or equivalent Kanban board tech) with full expansion
on user stories, use cases and tasks needed to complete the project.
It could also provide a record of any issues or risks that you faced
creating your project.

* A relational database used to store data persistently for the
project, this database needs to have at least 2 tables in it, to
demonstrate your understanding, you are also required to model a
relationship.

* Clear Documentation from a design phase describing the architecture
you will use for you project as well as a detailed Risk Assessment.
A functional CRUD application created in Python, following best
practices and design principles, that meets the requirements set on
your Kanban Board

* Fully designed test suites for the application you are creating, as
well as automated tests for validation of the application. You must
provide high test coverage in your backend and provide consistent
reports and evidence to support a TDD approach.

* A functioning front-end website and integrated API's, using Flask.
Code fully integrated into a Version Control System using the
Feature-Branch model which will subsequently be built through a CI
server and deployed to a cloud-based virtual machine.


#### My tech stack will be as follows:

* Kanban Board: Trello 
* Database: GCP SQL Server
* Programming language: Python
* Unit Testing with Python (Pytest)
* Front-end: Flask (HTML)
* Version Control: Git
* CI Server: Jenkins
* Cloud server: GCP Compute Engine
![](https://i.imgur.com/x7f5JnJ.png)  




#### My CRUD is as follows:

* User can create all the stories and corresponding cards.
* User can read all the stories and see the relevant cards.
* User can update all the stories.
* User can delete all the stories.

#### **My Risk Assessment**
I have revisited this with solutions I actually applied with scenarios that did happen and updated it under "Implemented".

![](https://i.imgur.com/HRoeBy9.png)

#### Link to my Trello Board:
https://trello.com/b/GemvxO82
It changed a lot since I first started it because I moved things into "completed".

#### ER

My planned ER looked as follows, hovewer - half way through making it I realised that the login functionality is not something I want to implement into my project, so I removed it and made a new one.
![](https://i.imgur.com/0UVNVFe.png)

Below is my finished ER diagram and how I would like my database to look like. It's simplified and I find that it suits the purpose more.
![](https://i.imgur.com/9LSgsnz.png)
#### Here is what and how I actually implemented it into my code
As you can see, it changed a lot.
![](https://i.imgur.com/qxomCQS.png)

#### Testing
I used Jenkins to perform my Pytest testing. Below is a screenshot of the detailed results of my coverage.

![image](https://user-images.githubusercontent.com/86067593/126895038-0038e237-32fb-4db2-a042-bf01099743ad.png)


#### Functions and Front End

* This is the top of my page - I used a quick, premade CSS Bootstrap link in my templates to make it look nicer.
![image](https://i.imgur.com/PWjxixl.png)

* Here is the navigation.
![image](https://i.imgur.com/khGgsI8.png)

* Here is creation of a Card.
![image](https://i.imgur.com/NlHjLnn.png)

![image](https://i.imgur.com/Werw7Sm.png)

* Here's creation of a Story prompt.
![image](https://i.imgur.com/GatMp9x.png)

* Here's how it will display and editing options.
![image](https://i.imgur.com/vlrLXZy.png)


#### Future Improvements
* I would really like the user to be able to display a card to clearly see where the story inspiration came from.
* I would like to add more functionality to edit the cards and their illustrations.
* I would like the user to be able to generate a random story.

#### Author
Natalie Terpilowska

#### Acknowledgements
* Oliver Nichols
* Ryan Wright
* Victoria Sacre
