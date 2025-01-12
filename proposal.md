
#  Occasion Gift Tracker Proposal 
Creators: TC, David, and Cecilia

Here are some useful links.
- [Check out our readme](https://github.com/cheddarmonk/super-duper-hepta-journey/blob/main/README.md) page
- [Check out our Wiki](https://github.com/cheddarmonk/super-duper-hepta-journey/wiki) page
- [Check out the Repo](https://github.com/cheddarmonk/super-duper-hepta-journey) page     
- [Check out the Projects](https://github.com/cheddarmonk/super-duper-hepta-journey/projects/1) section
- [Check out the Issues](https://github.com/cheddarmonk/super-duper-hepta-journey/issues) section.

## Table of contents
* [Main idea](#Main-idea)
* [Overview](#Overview)
* [Background](#Background)
* [Objectives](#Objectives)
* [Scope](#Scope)
* [Development](#Development)
   * [Architecture](#Architecture) 
   * [View](#View)
* [Development Schedule](#Development-Schedule)
* [Opportunities and challenges](#Opportunities-and-challenges)
* [Minimum Acceptance Criteria](#Minimum-Acceptance-Criteria)
* [Conclusions](#Conclusions)

---

## Main Idea:
Being organized and knowing who is doing what on what date is a normal part of our daily schedule.  Planning parties, giving, receiving, and tracking received or given gifts and by whom is a daunting task.  Coordinating and managing special occasion dates such as weddings, birthdays, or anniversary celebrations one must wear several hats.   By wearing these different hats things get lost, forgotten, or overlooked.

Wouldn't it be nice to be able to keep track of all these important dates, celebration categories, and the gifts received or given?  Having the ability to quickly pull up who you gave a gift to for a baby shower two years ago would be as easy as pushing a few buttons.  What about knowing that you only gave your sister a birthday card last year but, she gave you a box of your favorite cigars.

Having this ability would allow you to tailor your choice of gifts for any occasion.  Now, you do not look like a cheap scape or don't give a gift that is inappropriate for the occasion.  

To see the problem in action check out this [video](https://www.youtube.com/embed/FpGkLzGl1CI?start=20&end=50) of **Sheldon** from the Big Bang Theory with a similar problem.
<a href="#Table-of-contents"><p align="right">Return to the top</p></a>

## Overview:
We've all heard the story of the husband who forgot his wife's birthday or their anniversary. If only he had remembered then there wouldn't be any couch surfing for him. When that friend goes above and beyond to get you that nice single malt whiskey for your birthday and in return, you send him a 6-pack of bud-light. It just doesn't seem right. With the right tool, you can avoid these issues and experience the freedom that comes with knowing what the right gift is for the right person. 


<a href="#Table-of-contents"><p align="right">Return to the top</p></a>

## Background:
As a consumer, your choice is limited to three options to help plan for birthdays, anniversaries, holidays, and other special moments. You can use a calendar app like Google or Outlook to remind you of the date but then you are left to your own devices to prepare for the date. There are other apps like Gifster, Santa's Bag, and even Amazon to make lists and help order gifts for the occasion. The problem is if you can't remember when you are supposed to attend the event how can you order the gift on time. On top of that none of the previous competitors can remind you what you bought last time, nor are they able to track what others have gifted you! Regifting a gift or giving a gift that is too underpriced/inappropriate or overpriced for the occasion is awkward and tends to be very uncomfortable at best and offensive at worst. 

The only way at the moment to fulfill both of these is to manually create a list digitally or on paper, then you have to store it and before you go to buy a gift next time, you then have to find it and then you get to compare. In short... it's a major headache. 


<a href="#Table-of-contents"><p align="right">Return to the top</p></a>


## Objectives:
1. Developing a front-end web interface a user can interact.
1. Processing and persistently storing data to a backend database.
1. Retrieving and updating the persistent storage datasets as a user interacts with the web interface

<a href="#Table-of-contents"><p align="right">Return to the top</p></a>

## Scope:
This will be an operational prototype of an occasion gift tracker application.  The application will be an interactive web application that allows user input, storage, and data retrieval.  The application will interact with a Mongo DB.  The Mongo DB will be a persistent storage device for creation, retrieval,  updating, and deleting (CRUD) operations.  Other functional iterations of the application will be possible for future development.

<a href="#Table-of-contents"><p align="right">Return to the top</p></a>

## Development:

### Architecture
For this objective, the idea is to build a functional application that provides a web API with a persistent server-side database.  To accomplish this, the interface will be built with **`HTML`**, **`CSS`** and **`JavaScript`**, and **`NodeJs`**.  Using these technologies allows for rapid Agile development.  The interface will be simple and intuitive, so the user does not have to learn a complex process to use the application.  In addition, the application will use **`NodeJs`**, **`Express`** web framework, and **`AngularJS`** for data binding,  dependency injection, and elimination of code duplication.  All of this happens in the browser which makes **`AngularJs`** ideal for any dynamic webpage and server technology.  See more of what [**`AngularJs`**](https://angular.io/) and [**`NodeJS`**](https://nodejs.org/en/about/) can do 

For the backend persistent data storage MongoDB will be used for creation, reading/retrieval, updating, and deleting records.  MongoDB is ideal for this application because of the flexibility with document object modeling for development.  

To develop the project our team will do the following:
1.  Develop a plan of action that outlines the stages of development, (Product Proposal).
1.  Use SCRUM methodology which includes several SCRUM iterative sprints consisting of planning, building, testing, and product reviews.
1.  Deploy potentially shippable products at the end of each Scrum sprint.
1.  Repeat steps as necessary to complete the product.


 <h1 align="center"> 
  
  ![pic](https://user-images.githubusercontent.com/54637063/135461849-1f0ee9f2-40b9-4d55-a1d0-4e2372f50fa3.JPG) 

</h1>
  

![Blank diagram](https://user-images.githubusercontent.com/54637063/135622500-9728e6cb-5f7a-41fe-84a3-a4c998eaa924.jpeg)

<a href="#Table-of-contents"><p align="right">Return to the top</p></a>

## View:
To better understand the data, and how it will be processed we are providing a visual representation of the user interface of our project. 
            
![User_Interface](https://user-images.githubusercontent.com/54637063/135650567-9f4e2e9a-a940-44fa-988f-e0c5d37444a6.jpeg)
The purpose of this is to provide a visual representation of the layout and data flow.

<a href="#Table-of-contents"><p align="right">Return to the top</p></a>

## Development Schedule:
The following are tentative due dates for each stage of development:

Task             |       Due Date
------------     |     -------------
Team Product Repository        | 23 Sep 2021
Product Proposal               | 5 Oct 2021
Product Backlog                | 5 Oct 2021
Sprint 1 Backlog               | 5 Oct 2021
Development Product Ownership  | 8 Oct 2021
Sprint 1 Product               | 21 Oct 2021
Sprint 1 Reflection            | 21 Oct 2021
Sprint 2 Backlog               | 26 Oct 2021
Sprint 2 Product               | 11 Nov 2021
Sprint 2 Reflection            | 11 Nov 2021
Product Presentation           | 23 Nov 2021
Product Deployment             | 30 Nov 2021
Development Product Reflection | 4 Dec 2021

<a href="#Table-of-contents"><p align="right">Return to the top</p></a>

## Opportunities and challenges:
With our lifestyles becoming more hectic than ever, it’s increasingly difficult for most of us to juggle our professional and personal lives. One moment you’re trying to meet an impossible deadline at work, and the next, you’re running errands for your home.  In addition to the juggling of many tasks, all these tasks must be centrally located and accessible constantly while on the job, or while traveling with family and friends.  Having an app that handles time-consuming scheduling is another stressor you need not worry about.  Like any technology, some challenges must be considered.  Privacy is at the front of all of our minds.  The application's information is sensitive and must be stored safely and with personal privacy in mind.

## Minimum Acceptance Criteria
- [ ] User goes to website.
- [ ] User selects category to find a gift for.
- [ ] User selects date range to find people who have birthdays, weddings, etc. in the date range.
- [ ] User presses submit button to see all birthdays/special occasions for the date range and supplied gift and year given.

<a href="#Table-of-contents"><p align="right">Return to the top</p></a>

## Conclusions:
Relationships are without a doubt the most important part of our lives. From significant others and family to co-workers and bosses we all have relationships that we have to maintain and continue to work on. Remembering special occasions and dates about those relationships is a crucial part of keeping them healthy. Our app uses lightweight, simple-to-use open source web frameworks that enable you to be prepared to make the most of those special occasions. Forget no more and worry no more. With our gift tracking, put your stress to rest by making sure you have the right gift for the right person at the perfect moment. 

<a href="#Table-of-contents"><p align="right">Return to the top</p></a>
