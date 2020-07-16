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



Ans: 
  In the world of web development, one crucial part is Database. As an example, any organization needs to store information about their employees, their contact details, and other important information.  Here comes the use of the database. A systemic collection of data is simply called the database. database stored information in an organized, reliable, and searchable way and it also has a security feature to keep the information safe with a controlled password-protected way. There are different kinds of databases for different purposes. The main types are text databases, desktop database programs, relational database management systems (RDMS), and NoSQL and object-oriented databases.
 I have found the relational database most common in many places like from the order management system (banking) to the content management system (mobile app). One most commonly used relational database management system is Postgresql which is also hugely used in building the Rails app.


The pros of the Postgres database( relational DB) :
 
Postgresql is one most popular, flexible, and scalable relational database management systems. It requires a Postgresql server to manage the connection of data and a management application to work with and to view the data it contains. 
It is good for highs scaled, large project that requires relational queries.
Structure:
* Recorded are organized as a table that holds rows and columns. Columns correspond to the type and rows corresponds to the individual entities of the table 
* It must have a Primary key that corresponds to a unique identifier that identifies a specific row.
* It has attributes that hold general data about a record.
* It also can hold a column named foreign key that can link to other tables. The foreign key column, each row holds a value that corresponds to the Primary keys of another table.
* It holds multiple tables linked by the joined operation. 


The cons of the Postgres database( relational DB) :

 * No document implementation or no graph database association
* Cannot be used in defined access patterned situation.
* The storage pattern here is concentrated. That means the entire copy of data is contained in one place which is typically not partitioned from one another unless some advanced strategy is been used.
*  Low performance. For better performance, building a better machine is the requirement. 
* Not good for High scaled, a large project that needs high performance.

---

Q3: Discuss the implementation of Agile project management methodology 200-300

Ans: Before developing a web application some prior works are done virtually for assuming the outcome of the whole work at the end. This called the development methodology. There are different kinds of methodologies. Waterfall methodologies, Agile methodologies sets.  
Waterfall model applications are normally very big applications. It holds different sectors all together like the front end, back-end, DNS, etc that are measured altogether as a single application. The interesting aspect of the waterfall methodology as if the smallest part of the application fails somehow, the entire application would stop working. It also took a long time to push the change to production in this way which is not acceptable for most of the modern web applications like-  Netflix, uber, etc..  For fulfilling this shortage, the agile methodology was brainstormed but the developers. For finding the better approach to build an application in a first-place without affecting the existing software. 


Agile meaning: The word Agile means - the chain of rapid development and deployment. That means, breaking the whole application plan into a small piece of code and work on the small services one by one by not affecting the main application in general. Planning, designing, developing, testing, deploying, reviewing is done on those small chunks one by one except the launching. This ensures secure constant feedback by deploying it in a dev environment no matter how big or small changes have been done in any part of code.  This is way batter than waiting months long for getting feedback on a simple change on a code to decide whether the change is acceptable or not.
This aspect is good for developer because they can focus on a specific set of task that has specific requirements and priorities, rather than being worried of 10 different microservice at a same time.


Agile methodology got few values: 
* People over process and tools: Agile methodology gives a development-centric and client-centric environment that means exploring the other possibilities rather than holding on something old when a new solution is on hand available. 
* Working software over comprehensive documentation: Development of the functional application get priority over documentation.

* Customer collaboration over a rigid contract and responding to change rather than following a plan: It is feedback dependent. Because agile allows doing the task in small pieces, any part of code can be modified at any time according to the need following feedback also keeping the main plan intact.

Implementation:

Some examples of Agile frameworks/ philosophies: Scrum, eXtrema Programming, LEAN, KANBAN, CRYSTAL.
The most popular is SCRUM. 
Scrum is basically an iterative philosophy. It allows iteration over changes one at a time. Scrum iterates over the plan, build, test, review constantly.

SCRUM structure:
ROLES:
1. Product owner ( Manager)
- In scrum, the product owner is the"Guy with the Idea" so all accountability lies on him. The product owner might not be a technical person, he or she might be a person from management.

2. SCRUM Master ( Team leader)
- SCRUM master handles the day to day operation which includes setting up meetings, planning tasks for everyone.

3. Tam ( Developers, Tester)
- The peoples who actually got to do different parts of the whole work that to be done.


Parts of Development:

Parts of Development:

*Product Backlog: This is made by combination of the small tasks of the whole project and each task will iterate over - plan, build, test and review. Each of the tasks supposed to be done within a specific time limit. The product owner and SCRUM master makes the Product backlog. They prioritize the user stories while making the small parts and depending on that the next part is built which is called the "Sprint backlog"

* Sprint backlog: This is where the team starts to work on. It includes the small tasks prioritizing the user stories. These are the logical reasonable tasks that need to be executed one at a time.

* Sprint planning(Meeting): In this meeting, the Product owner explains how he wants the app to look like.

* Daily scrum: This is the meeting among the member of the team that includes DEVS, testers, and other people according to the situation to discuss what to do.

*Sprint review: This review session occurs at the end of each user story. The time range could be 2week to 4weeks. This session includes: demonstration of the chunk of code or the verification of completion and to move on to the next task. 

This development process is done several times and at the end of each 2 weeks, there is a shippable part of the app that is ready.





---


Q4: Provide an overview and description of a standard source control workflow 100-200

Ans:
Version-control is a system that helps to maintain change in files of the collaborative workflow in a controlled way without having the worry of losing anything. There are two types of Version control. Centralized and Distributed. I choose to explain GIT (Distributed version control) as a standard source/version control system. 

1. It backups every single change made in files so understanding part of code or if anything needs to stay in a previous way is done easily by following the backup history.
2. It keeps the history so it is easier to compare the current version of work to the version we are working on now.
3. The entire project with all of the history is mirrored to all the contributor's computers.
4. It gives the scope to experiment on a part of the project and let ti merge to the main project if it is ok or let it stay as like it was before by letting go of the experimental part.
5. It allows us to see the contributor's name in the collaborative work field. That means, one contributor, can see which part of code is written or changed by whom.

6. As Git stores all operations in the local machine it is so fast.
7.  Because it is distributed, all the contributors have the full part of the project and can save the changes locally.
8. Git is an open-source project
9. The vulnerability of any organization depends on the software development process. So having the contents secured is a necessity. Git protects all the contents of a git repository with Secure Hash Algorithm 1 or SHA1.

NEW GIT repository -> create a standard file directory locally -> the repository is started by the command `git init` on the terminal -> after adding few files in the repository a snapshot is taken by running the command 'git commit' -> after this further changes can be done to that file and run 'git commit' again -> like the same any file can be deleted or added via the commits 

Git has three parts: working tree(add, remove, edit files in the working tree), staging area(edited file adds to staging the and only staging area files are put into the next commit), history
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

Ans:
  The relational database has three types of integrity.
 * Entity integrety in RDBMS: Prevent duplicacy, ensures that data has been saves is uniq. DB table must have a primery key and they should be uniq in each row for holding the data in the columns.
 * Referential integrety in RDBMS: Prevention of adding any inconsistant data to exsisting data system is the referential integrety. This states that a table holding foreign key can only hold the values of the table holding the primery key.
 * domain integrety in RDBMS: A same type of data should be stored under a specific domain name in the table column. That means, every column of a table need to have a domain name.

---


Q11: Describe the manipulative aspects of the relational database model. Your description should include information about the ways in which data is manipulated (added, removed, changed, and retrieved) in a relational database. 100-200

Ans:
 Data Manipulation in RDBMS:
  The database is manipulated by Data manipulating language, eg SQL. 
  * To add a single row in the existing table of the database, the command is below:
    SQL INSERT statement- 
    `INSERT INTO table(columnA, columnB,...)`
`VALUES (valueA, valueB,...);`
  * The syntax to remove one or more rows in a table of database permanently:
   SQL DELETE statement
  
  `DELETE FROM table`
   `WHERE`
      ` condition;`
     
  * To change the existing data in one or more rows in a table the syntax is below:
   SQL UPDATE syntax
    ```
    UPDATE table
    SET 
      column1 = new_value1,
      column2 = new_value2,
    WHERE
      condition;
  * To retrive any data SQL SELECT statement is used:
     ```
     SELECT column1,column2...
     FROM table2,table2...
     WHERE filter_condition
     GROUP BY column1
     HAVING group_condition
     ORDER BY column1,column2 ASC | DESC 
---


Q12: Identify and explain the workings of TWO sorting algorithms and discuss and compare their performance/efficiency (i.e. Big O) 100-200
Ans: 
Sorting algorythms:

Bubble sorting: If an array needs to be sorted by asending order, it is scaned from left to right multiple times comparing the particular element of current position to the adjacent element of next position. If the current one is greater than the next one, we need to swap the element position otherwise move to the next position and repeating the comparision until the end of that array. 
  The whole process need to repeat (n-1) times where n = the number of elements of that array. After that the whole array will be sorted in asecnding order. In this process the array divides into two bubbles, one part holding the sorted elements and rest holding the unsorted part. With each round finishing, the sorted part gets bigger.
  For the n number element of an array, the time complexity of bubbble sorting is worst case and average complexity of О(n2).
  
  Merge sorting: In merge sort we take an array and divide it in two halves in two squares. Then keep dividing each of the half again and again until only one stays in one square, then take one pair of square and find the smallest one to sort the two in asending order and store them togather keeping smallest one on the top. 
Merge sorting is less complex then bubble sorting.


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