#    T2A1 Workbook - RfQ Response
#    Luke Dawson 

### The ACME Corporation is interested in building a marketplace web application (app) using Rails for one of it’s product lines. To help it choose the vendor who will undertake the project they have released a RfQ. As an aspiring junior dev at an up and coming Sydney software startup (CAx-Dev) your manager has assigned you to assist with preparation of the RfQ response.

## Q1: Describe the architecture of a typical Rails application (200-300 words)


Ruby on Rails is a code library that expands the captabilities of Ruby from a high level programming language to a web development framework capable of full stack web application development specifically with a database backend. 

At the heart of Rail's design is Model-View-Controller (MVC) architecture. 

The Model governs the business logic of the application. Each table in your database is governed by it's own model and it is within the model that the developer establishes relationships between other tables and relevant validations within the tables. 

the View governs the display logic and is the front end of your web application. Views are HTML files that include embedded Ruby that can be used to render data in the browser. You can also attach CSS files to your application to style to your hearts content  

Controller governs application flow between the Model and View. Browser requests are intepreted in the controller which request model data and respond to the views to present the information. (actions as well)

The Ruby on Rails server creates a Web Server that listens to an IP and a port and you can interact with a web browser. On your local machine this defaults to port 3000 and you can access your webpage there.   

Routes convert URL paths into a form our application can intepret. These are configured in the routes file and include a controller and an action specified to complete a HTTP request. 

Assets are the files that supply our chosen visual content to our Views rendered in the browser. 

All of these components are clearly organised in a folder structure that allows us to easily navigate around our app. 


## Q2: Identify a database commonly used in web applications (including Rails) and discuss the pros and cons of this database (150 - 250 words )

 Mongo DB is an open source, dynamic, object oriented and scalable database. 
 
 It is NoSQL which means Data objects are stored as seperate objects as opposed to being stored in columns and rows as they would in a SQL database. These files are either represented as JSON or BSON documents. 
 
 Mongo DB excels in simplicity of instalation and implementation and providing high performance, high avaliability and horizontal scaling.  

Mongo DB is easy to install on Mac, PC and Linux systems and can be operated with Javascript notation as it can use JSON files to store data making it a popular choice for web developers. 

 Mongo DB is a high performance database because it can access it's indexed documents lightning fast. Relational databases have slower query times as they have to navigate nebulous fields and tables. 

 Mongo DB is horizontally scalable database. Through a process called Sharding, you can spread your database over multiple machines and combine their resources. This is much more flexible then competitors that are vertical scaling which means you must host your database om single machine. 

 These qualities make it very useful for Web Developers looking to build web applications quickly, with diverse data that need scale flexibly and efficiently. Examples of this includes Codecademy, Google Search and Ebay. 

 However, if you need table joins you are out of luck due to the NoSql nature of the database. Mongo DB is best when you have alot of a data but don't need it to be relational. It also may be unsuitable as you have to hire DB admins who fully understand NoSQL. It is extremely memory hungry due to it's reliance something called a memory mapped file. THis means your database is only as scalable as it's access to system memory. 



## Q3: Discuss the implementation of Agile project management methodology (200-300 words)

 
Agile software development encompasses a set of frameworks and practices that adhere to the Manifesto for Agile Software Development and it's twelve principles. 
 
in the 1990's the software industry was met with a developmental crisis. The problem was that the industry was just not fast enough to meet the demands of the customer. Traditionally, progress was made sequentially and the final product was revealed upon its completion. Companies were finding that by the time they were unveiling their products the customers expectations had shifted. 
 
in 2011, after years of experimentation and discussion a new method that addressed the concerns of the industry was formalised. This was the Agile Manifesto and it contained 4 core values and and 12 guiding principles.
 
But a philosophy is one thing. Agile needed some methodologies to help teams incorporate these values and principles into their projects. Popular examples of this are Scrum, Kanban and Extreme programming but all these methodology frameworks follow the same process. 
 
You must plan your project with a clear end goal and with Agile's values and principles in mind. Then you must break this process down into a roadmap that will represent all the features that will make up your final product. 
 
You will then break each feature into short development cycles called sprints. Before these sprints begin, the team must plan how much will be achieved, what will be achieved and by whom. This process should be visually documented and accessible by every member of the team. 
 
During the development process there should be daily meetings. In these meeting team members will briefly speak about what they accomplished the day before and what they plan to achieve today. It is important these meetings do not exceed 15 minutes so they don't impact on productivity. 
 
When a sprint is finished is finished there will be two meetings. One will be a presentation with the stakeholder to present your progress. The second meeting will be a breakdown of the previous sprint, a discussion on what can be improved and how team members handle work loads during the sprint. 
 
By following these steps and making them a routine for your team you will be on the path to utilizing Agile to its highest potential. 
 

## Q4: Provide an overview and description of a standard source control process (100-200 words)

## Q5: Provide an overview and description of a standard software testing process (100-200 words)

## Q6: Discuss and analyse requirements related to information system security (100-200 words)

## Q7: Discuss common methods of protecting information and data (100-200 words)

## Q8: Research what your legal obligations are in relation to handling user data (100-200 words)

## Q9: Describe the structural aspects of the relational database model. Your description should include information about the structure in which data is stored and how relations are represented in that structure. (100-200 words)

## Q10: Describe the integrity aspects of the relational database model. Your description should include information about the types of data integrity and how they can be enforced in a relational database. (100-200 words)

## Q11: Describe the manipulative aspects of the relational database model. Your description should include information about the ways in which data is manipulated (added, removed, changed, and retrieved) in a relational database. (100-200 words)

## Q12: Identify and explain the workings of TWO sorting algorithms and discuss and compare their performance/efficiency (i.e. Big O) (300-500 words)

## Q13: Identify and explain the workings of TWO search algorithms and discuss and compare their performance/efficiency (i.e. Big O) (300-500 words)

## Q14:  Conduct research into a marketplace website (app) and answer the following parts:  (50 - 100 words per)
 ### a. What software is used by the app?
 ### b. What hardware is used by the app?
 ### c. Describe the interaction of technologies within the app
 ### d. Describe the way data is structured within the app
 ### e. Identify entities which must be tracked by the app
 ### f. Identify the relationships and associations between the entities you have identified in part (e)
 ### g. Design a schema using an Entity Relationship Diagram (ERD) appropriate for the database of this website (assuming a relational database model)



 References: 
 Q1:
 https://www.techcareerbooster.com/blog/ruby-on-rails-architecture-overview-for-beginners
 https://adrianmejia.com/ruby-on-rails-architectural-design/
 https://rubyonrails.org/
 https://whatis.techtarget.com/definition/business-logic
 https://medium.com/@sagar.mane006/understanding-rest-representational-state-transfer-85256b9424aa

 Q2: 
 https://www.mongodb.com/what-is-mongodb
 https://www.guru99.com/what-is-mongodb.html
 https://data-flair.training/blogs/advantages-of-mongodb/
 http://makble.com/the-advantages-and-disadvantages-of-mongodb

 Q3: 
 https://zenkit.com/en/blog/agile-methodology-an-overview/
 https://www.agilealliance.org/agile101/
 https://www.workfront.com/blog/the-beginners-guide-to-agile-project-management-methodology
 https://plan.io/blog/ultimate-guide-to-implementing-agile-project-management-and-scrum/
