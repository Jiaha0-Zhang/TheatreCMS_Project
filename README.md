# TheatreCMS_Project

## Introduction

This is a 2-week Live project for a theatre company designed software to manage the content, I worked with my peers in a team developing a full scale MVC Web Application in C#. My main job was to complete some stories assigned by the director, including the redesign of the web pages, adding some functions and features of click events, creating entity models and modifying some controllers.

In this project, each of us played an important role and we were all assigned to both front-end and back-end tasks. Completing some relatively big changes would take up a lot of time, so I tried to complete most of the contents and requirements with what I had learned, and then spent extra time searching for similar solutions from various resources to solve the parts I didn't understand, including consulting the director and peers in my team. The number of stories I ended up completing far exceeded expectation and the requirements for pass.

## Back End Stories

### Create entity model for CalendarEvent and CRUD pages
***Create an entity model for the Calendar Event class so that productions can be saved to the database.***
* [Create entity model for CalendarEvent](https://github.com/Jiaha0-Zhang/TheatreCMS_Project/blob/main/Stories/CalendarEventProps.png)


### Seed EventPlanner
***Create a seed method for EventPlanner. Seeding the database entails creating an instance of EventPlanner and saving it to the database before the page is loaded so that we have access to the EventPlanner for testing purposes.***
* [Configuration code snippet](https://github.com/Jiaha0-Zhang/TheatreCMS_Project/blob/main/Stories/Configuration.png)
* [EventPlanner code snippet](https://github.com/Jiaha0-Zhang/TheatreCMS_Project/blob/main/Stories/Eventplanner.png)

### Restrict CRUD Operations
***Prevent any user that is not an EventPlanner from accessing the Create, Edit, and Delete pages.Create a new View in the EventPlanner View folder called AccessDenied. Redirect the user to this AccessDenied page when they try to access one of these restricted pages.***
* [CanlenderEventsController code snippet](https://github.com/Jiaha0-Zhang/TheatreCMS_Project/blob/main/Stories/CanlendarEventsController.png)
* [EventAuthorize](https://github.com/Jiaha0-Zhang/TheatreCMS_Project/blob/main/Stories/EventAuthorize.png)


## Front End Stories

### Create and Style About Page
***Create a new view of About page, And match the style to the theme of the theater.***
* [Create and Style About Page code snippet](https://github.com/Jiaha0-Zhang/TheatreCMS_Project/blob/main/Stories/About_cshtml.png)
* [Create and Style About Page webpage screenshot](https://github.com/Jiaha0-Zhang/TheatreCMS_Project/blob/main/Stories/AboutPage.png)

### Index Page for Calendar Event
***Create an index page for calender event to meet specific requirements and add some features.***
* [Index Page for Calendar Event code snippet](https://github.com/Jiaha0-Zhang/TheatreCMS_Project/blob/main/Stories/index.png)
* [Index Page for Calendar Event webpage screenshot](https://github.com/Jiaha0-Zhang/TheatreCMS_Project/blob/main/Stories/IndexPage.png)

### Style the Create and Edit Pages for Calendar Event model
***Re-style Create page and Edit page to meet specific requirements and add some features.***
* [Style the Create Pages for Calendar Event model code snippet](https://github.com/Jiaha0-Zhang/TheatreCMS_Project/blob/main/Stories/Create.png)
* [Style the Create Pages for Calendar Event model webpage screenshot](https://github.com/Jiaha0-Zhang/TheatreCMS_Project/blob/main/Stories/CreatePage.png)
* [Style the Edit Pages for Calendar Event model code snippet](https://github.com/Jiaha0-Zhang/TheatreCMS_Project/blob/main/Stories/Edit.png)

### Related CSS
***This contains all the CSS code used in the above webpages design.***
* [Related CSS code snippet](https://github.com/Jiaha0-Zhang/TheatreCMS_Project/blob/main/Stories/ProdCss.png)
* [Related CSS code snippet2](https://github.com/Jiaha0-Zhang/TheatreCMS_Project/blob/main/Stories/SiteCss.png)

### Restrict CRUD Operations
***The webpage when user is redirected to.***
* [AccessDenied page](https://github.com/Jiaha0-Zhang/TheatreCMS_Project/blob/main/Stories/AccessDenied.png)

## Summary and Experience

This is a team project. Although there was no overlap between the Stories made by my peers and me, there were many similar contents and requirements in our Stories instead. Therefore, I realized something very important: there is no shame in asking someone for help when you are helpless, because productivity is often a big thing. Of course learning on the job is necessary, but it should not waste too much time.

The biggest challenge of this Live Project was that I often felt overwhelmed at the beginning of a Story and not knowing where to take the first step, but once I had a complete plan in my mind, the rest fell into place easily. 


*Jump to: [Back End Stories](#back-end-stories), [Front End Stories](#front-end-stories), [Summary and Experience](#other-skills-learned), [Page Top](#live-project)*


