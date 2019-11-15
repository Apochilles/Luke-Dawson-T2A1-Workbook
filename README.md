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

 Mongo DB is a dynamic, object oriented and scalable database. 
 
 It is NoSQL which means Data objects are stored as seperate objects as opposed to being stored in columns and rows as they would in a SQL database. These files are either represented as JSON or BSON documents. 
 
 Mongo DB aspires to be simple to install and implement and provides high performance, high avaliability and automatic scaling.  
 High performance 



## Q3: Discuss the implementation of Agile project management methodology (200-300 words)

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