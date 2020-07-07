# T2A1
---
# T2A1
---
Q1: Describe the architecture of a typical Rails application. 200-300

Ans: 
  
  Ruby on Rails is an open-source web frame-work with inbuilt Ruby Programming language. It is capable of building a powerful Rails app quickly. Life as a Developer becomes easier with the inbuilt feature of rails that includes creating a summed up package of the required file. That means a developer get to write less code while getting more accomplishment of the work done.
  
  Rails was created by  David Heinemeier Hansson in 2003 as a byproduct while working on his project management tool BASECAMP. It was officially released as an open-source code in 2004. In 2005 Version 0.1 was released. It was 2006 when Rails got maximum recognition after Apple Builder added Rails in their OSX leopard.

Rails got three principles: 
1. MVC
2. Convention over configuration
3. DRY

M is for Model. Model is the Object of Object-oriented programing system of rails. The Model holds the data.
V is for View. View handles the presentation of the web page by holding necessary HTML, CSS and JS file in it.
C is for Controller. The controller holds the responsibility of processing and responding at events like user actions. It makes connection in between Model and View. In this way, the controller controls what happens. 

To elaborate on this concept a diagram will be helpful.

    add diagram here

The browser communicates to the controller that holds all the required actions based on browser requirements, then the controller talks to the model to bring the piece of information from the database. Model, which is the only connection to the database then finds the piece of information and takes it back to the controller. At this stage, the controller can connect to the model and the model can connect to the database as many times it requires to get the correct information. Finally, when the controller gets a satisfactory result for the browser, it sends it to the view. The view then uses the suitable HTML, CSS, JS files to present the result back to the browser.
 Rails has a specific name for these three: ActionController is the controller, ActionView is the View and ActiveRecord is the model. ActionController and ActionView together are called the Action pack.


Convention over configuration 

Rails convention is to encourage devs to use the set of assumptions/ default to make it easier and less coding for maximizing the outcome.

DRY 
DO NOT REPEAT YOURSELF principle keeps the code maintainable and less buggy.

  
---


Q2: Identify a database commonly used in web applications (including Rails) and discuss the pros and cons of this database 150-250

---

Ans: 
  In the world of web development, one crucial part is Database. As an example, any organization needs to store information about their employees, their contact details, and other important information.  Here comes the use of the database. A systemic collection of data is simply called the database. database stored information in an organized, reliable, and searchable way and it also has a security feature to keep the information safe with a controlled password-protected way. There are different kinds of databases for different purposes. The main types are text databases, desktop database programs, relational database management systems (RDMS), and NoSQL and object-oriented databases.
 I have found the relational database most common in many places like from the order management system (banking) to the content management system (mobile app). One most commonly used relational database management system is Postgresql which is also hugely used in building the Rails app.


Q3: Discuss the implementation of Agile project management methodology 200-300

---


Q4: Provide an overview and description of a standard source control workflow 100-200

---


Q5: Provide an overview and description of a standard software testing process (e.g. manual testing) 100-200

---


Q6: Discuss and analyse requirements related to information system security and how they relate to the project 100-200

---


Q7: Discuss common methods of protecting information and data and how you would apply them to the project 100-200

---


Q8: Research what your legal obligations are in relation to handling user data and how they can be met for the project 100-200

---


Q9: Describe the structural aspects of the relational database model. Your description should include information about the structure in which data is stored and how relations are represented in that structure. 100-200

---


Q10: Describe the integrity aspects of the relational database model. Your description should include information about the types of data integrity and how they can be enforced in a relational database. 100-200

---


Q11: Describe the manipulative aspects of the relational database model. Your description should include information about the ways in which data is manipulated (added, removed, changed, and retrieved) in a relational database. 100-200

---


Q12: Identify and explain the workings of TWO sorting algorithms and discuss and compare their performance/efficiency (i.e. Big O) 100-200

---


Q13: Identify and explain the workings of TWO search algorithms and discuss and compare their performance/efficiency (i.e. Big O) 100-200

---


Q14: Conduct research into a marketplace website (app) and answer the following parts: 50-100 per part
  a. List and describe the software used by the app.
  b. Describe the hardware used to host the app.
  c. Describe the interaction of technologies within the app
  d. Describe the way data is structured within the app
  e. Identify entities which must be tracked by the app
  f. Identify the relationships and associations between the entities you have identified in part (e)
  g. Design a schema using an Entity Relationship Diagram (ERD) appropriate for the database of this website (assuming a relational database model)




---


Q2: Identify a database commonly used in web applications (including Rails) and discuss the pros and cons of this database

---


Q3: Discuss the implementation of Agile project management methodology

---


Q4: Provide an overview and description of a standard source control workflow

---


Q5: Provide an overview and description of a standard software testing process (e.g. manual testing)

---


Q6: Discuss and analyse requirements related to information system security and how they relate to the project

---


Q7: Discuss common methods of protecting information and data and how you would apply them to the project

---


Q8: Research what your legal obligations are in relation to handling user data and how they can be met for the project

---


Q9: Describe the structural aspects of the relational database model. Your description should include information about the structure in which data is stored and how relations are represented in that structure.

---


Q10: Describe the integrity aspects of the relational database model. Your description should include information about the types of data integrity and how they can be enforced in a relational database.

---


Q11: Describe the manipulative aspects of the relational database model. Your description should include information about the ways in which data is manipulated (added, removed, changed, and retrieved) in a relational database.

---


Q12: Identify and explain the workings of TWO sorting algorithms and discuss and compare their performance/efficiency (i.e. Big O)

---


Q13: Identify and explain the workings of TWO search algorithms and discuss and compare their performance/efficiency (i.e. Big O)

---


Q14: Conduct research into a marketplace website (app) and answer the following parts:  a. List and describe the software used by the app.
  b. Describe the hardware used to host the app.
  c. Describe the interaction of technologies within the app
  d. Describe the way data is structured within the app
  e. Identify entities which must be tracked by the app
  f. Identify the relationships and associations between the entities you have identified in part (e)
  g. Design a schema using an Entity Relationship Diagram (ERD) appropriate for the database of this website (assuming a relational database model)