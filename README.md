#    T2A1 Workbook - RfQ Response
#    Luke Dawson 

### The ACME Corporation is interested in building a marketplace web application (app) using Rails for one of it’s product lines. To help it choose the vendor who will undertake the project they have released a RfQ. As an aspiring junior dev at an up and coming Sydney software startup (CAx-Dev) your manager has assigned you to assist with preparation of the RfQ response.

## Q1: Describe the architecture of a typical Rails application (200-300 words)

Ruby on Rails is a code library that expands the capabilities of the Ruby programming language. It is a web development framework capable of full stack web application development specifically with a database back-end. 
 
At the heart of Rail’s design is Model-View-Controller (MVC) architecture. 
 
The Model governs the business logic of the application. Each model in your application governs a different table in your database and it is within the model that the developer establishes relationships between tables and relevant data validations. 
 
The View governs the display logic and is the front end of your web application. Views use HTML to structure the web app page layouts but also include embedded Ruby to retrieve database records and render them to the browser. Assets are the files that supply our chosen visual content to our Views rendered in the browser. The developer can customise these with CSS and Bootstrap. 
 
The controller governs application flow between the Model and View. The Controller interprets browser requests and references Model data to respond to the views to present the information. 
 
Routes convert URL paths into a form our application can interpret.These are configured in the routes file and include a controller and an action specified to complete an HTTP request. 
 
The Ruby on Rails server creates a Web Server that listens to an IP and a port and is intractable with a web browser.On your local machine, this defaults to port 3000 and it is here that you can preview your web application.
 
The organisation of these components in a folder structure allows us easy navigation around our app. 

## Q2: Identify a database commonly used in web applications (including Rails) and discuss the pros and cons of this database (150 - 250 words )

 Mongo DB is an open source, dynamic, object oriented and scalable database. 
 
It is a NoSQL database which means it stores data as independent objects as opposed to being stored in columns and rows as they would in an SQL database. It represents these files as JSON or BSON documents. Developers can operate it with Javascript notation if the developer exports in JSON documents making it a popular choice for web developers. 
 
 MongoDB excels in simplicity of installation and implementation and providing high performance, high availability and horizontal scaling.  
 
MongoDB supports Mac, PC and Linux systems allowing you to stick to your preferred system. 
 
MongoDB is a high performance database because it can access its indexed documents lightning fast. Relational databases have slower query times as they have to navigate nebulous fields and tables. 
 
MongoDB is a horizontally scalable database. Through a process called Sharding, you can spread your database over multiple machines and combine their resources. This is much more flexible than competitors that are vertical scaling, which means you must host your database on a single machine. 
 
These qualities make it very useful for Web Developers looking to build web applications quickly, with diverse data that need scale flexibly and efficiently. Examples of this include Codecademy, Google Search and eBay. 
 
However, if you need table joins you are out of luck because of the NoSql nature of the database. MongoDB is best when you have vast amounts of data but don’t need it to be relational. It also may be unsuitable as you have to hire DB admins who fully understand NoSQL. It is extremely memory hungry because of its reliance a memory-mapped file. This means your database is only as scalable as its access to system memory.

## Q3: Discuss the implementation of Agile project management methodology (200-300 words)

Agile software development encompasses a set of frameworks and practices that adhere to the Manifesto for Agile Software Development and its twelve principles. 
 
In the 1990s the software industry  met with a developmental crisis. The problem was that the industry was just not fast enough to meet the demands of the customer. Traditionally, progress was made sequentially and they revealed the final product upon its completion. Companies found that by the time they were unveiling their products the customer's expectations had shifted.
 
In 2011, after years of experimentation and discussion, they formalised a new method that addressed the concerns of the industry. This was the Agile Manifesto, and it contained 4 core values and 12 guiding principles.
 
But a philosophy is one thing. Agile needed some methodologies to help teams incorporate these values and principles into their projects. Popular examples of this are Scrum, Kanban and Extreme programming but all these frameworks follow the same process. 
 
You must plan your project with a clear end goal and with Agile’s values and principles in mind. Then you must break this process down into a roadmap that will represent all the features that will make up your final product. 
 
You will then break each feature into short development cycles called sprints. Before these sprints begin, the team must plan how much will be achieved, what will be achieved and by whom. This process should be visually documented and accessible by every member of the team. 
 
During the development process there should be daily meetings. In these meeting team members will briefly speak about what they accomplished the day before and what they plan to achieve today. It is important these meetings do not exceed 15 minutes so they don’t impact on productivity. 
 
When a sprint is finished is finished there will be two meetings. One will be a presentation with the stakeholder to present your progress. The second meeting will be a breakdown of the previous sprint, a discussion on what can be improved and how team members handle work loads during the sprint. 
 
As teams incorporate these methodologies into their projects. They will enjoy the values and principles of Agile software development.

## Q4: Provide an overview and description of a standard source control process (100-200 words)

Source control is how developers maintain, share and archive their source code.  

A developer will have a working copy of a project on their local machine and a repository usually hosted in the cloud. Source control allows the developer to keep a record of changes made during the course of development. It allows many people to work on the same code without effecting each others changes and allows a developer to access their code from different computers. 

A developers working copy is a playground for them to experiment with code to their hearts content. When you want to share or document your code you commit your changes to a repository. Sometimes a repo can contain edits that we want to apply to our working copy, this process is called updating.  

There are two types of history on a repository. Linear history is a sequential list of changes but there is also sometimes a branching history. A branching history will contain split versions that will merge again at a later commit.

Good source control pratice is to commit code with a singular purpose and with a descriptive commit messages. It is also important to share your changes regularly and make sure you're updating to others changes as well.


## Q5: Provide an overview and description of a standard software testing process (100-200 words)

Software testing is utilizing software with the intention of discovering and documenting bugs. It is one of the ways we verify our code executes successfully and as intended. 

Software testing process is the a process that ensures that software is checked and bugs are eliminated in a timely and and efficient manner.

A project should begin with a Test strategy and a Test plan. This formal document contains the softwares systems, configurations, features and details how the tests will be carried out. Processes, approaches, schedule. 

Next you need to design the tests around what information you gathered druing the stratergy and testing phase. 

Next you need to execute the tests as designed as per your project management methodology 

Finally you need to consider exit criteria. All planned tests should be have been covered with a 90% success rate and all critical defects must be 100% fixed 


## Q6: Discuss and analyse requirements related to information system security (100-200 words)

A businesses security requirements range on a case by case business. Identifying what aspects your business needs to protect itself against is extremely important whether it be malware, system availability loss or data compromise. It is also important to adapt as threats grow more intelligent and aggressive every day. 
 
There are three obligations a business must consider when implementing these defences. First, protecting the business second, legal compliance and third, customer protection.

IT security should begin with a contigency plan for worst case scenario. 

Next they need to identify the threats and prioritise them by severity and likelyhood.

Next they need to raise awareness of bad practices within the business to ensure everyone is as protected as possible.

Next defenses need to be implemented and maintained 

next end users should be prioritied. The users must be aware of the risks and know what we're doing to maintain their privacy. Implemented practices should be user friendly and easy to maintain. 

Once everything is in place it is important that the IT security team is confident but they must stay viligant and up to date with evolving threats 

## Q7: Discuss common methods of protecting information and data (100-200 words)

 
In this modern age it is extremely important to ensure you are as protected as possible against cyber threats. 
 
As a user is it important we encrypt our data when possible. Mail programs on major operating systems now have encryption plugins that encrypt and decrypt messages to ensure they are not intercepted during sending. Another thing to ensure is that your OS of choice is automatically updating so you have the latest possible security features. 
 
We must also backup our data. This has never been easier as we can create backups on physical hard drives but we can also upload our files to the cloud. Most devices have some automatic way of storing user data in the cloud so you're safe knowing your backups are constantly updated. If you stop using a device you should wipe your hard disk to factory settings so you are protecting if it is stolen or becomes lost
 
We must also keep up to data with malware protection by installing the latest software and doing regular scans to prevent malware stealing our private information.
 
Never reuse password and make sure you use passphrases to protect yourself from dictionary attacks. Never store your password on any device in any form.  


## Q8: Research what your legal obligations are in relation to handling user data (100-200 words)

When you are in a business that deals with user data it is important that you know your legal obligations when handling that user information. 

In Australia you must conform to Australia's privacy principles if you: Provide a health service to a person or people. If you disclose personal information about an individual to anyone else. If you incentivise collecting information about an individual, is a contracted service provider under a Commonwealth agreement, if you are involved in credit reporting, have an annual turnover of $3 million or  if you are associated with a body corporate that is subject to anything above on this list.
  
If you are subject to these privacy principles you must take steps to ensure you meet the legal guidelines. 
 
First is it our job to identify what kind of  data we are handling. Is it personal, financial, or health related.
 
Once we know what information we are handling, our highest priority is to make our clients aware that we are collecting this information. We must then explain what we intend to do with this information and who it will be shared with. If the information is sensitive (racial, political, religious, professional, sexual or criminal) ensure that the individual has consented to the gathering of this information. The individual must be aware that they have the right and ability to access and change this information at their discretion. 
 
The collected information is also privy to disclosure restrictions that may vary depending on the country of area they are disclosed in. 
 
By following these guidelines an organisation can hope to both protect a users privacy and keep yourself out of legal implication.
 

## Q9: Describe the structural aspects of the relational database model. Your description should include information about the structure in which data is stored and how relations are represented in that structure. (100-200 words)


A relational database is a set of tables which is given a uniquely identifying name. Within each table are rows representing specific values that relate to each other in a meaningful way. These values are associated with attributes or columns in the table.
 
It is an effective design concept as it is simple and thus, is easy to pick up.
 
The theory of a relational database was built on the mathematical concept of a relation. Unlike alternatives like object databases, it's mathematical foundation lends itself to database algorithms.
 
When planning a relational database a developer creates a database schema. It it within the schema that the relations, attributes and domains of the tables and columns are determined. A database key or superkey is a way for user to uniquely identify a row of data within a table. 
 

## Q10: Describe the integrity aspects of the relational database model. Your description should include information about the types of data integrity and how they can be enforced in a relational database. (100-200 words)

We have four operations we can perform on a relational database. These are insert, delete, modify and select. 

Data intergrity is the way these operations are restricted within a relational database. This into three catergories: Domain, key and referential keys.


Domain contraits protect the way we accept data into the fields of our tables. In the schema we specifiy data types such as integer and strings and determine their intended lengths. If the data we input is not allowed by our contraits it will be rejected. .We also set whether we allow a field to be Null or not. The database will be default to Null but there are circumstances where this is not what we intend.

Key constraits allow unique values to have only one idenifying key.  

Referential data constraits only allow related fields in tables to interact. If you try and access a field that is not allowed by a foreign key you will be denied access to the field. 


## Q11: Describe the manipulative aspects of the relational database model. Your description should include information about the ways in which data is manipulated (added, removed, changed, and retrieved) in a relational database. (100-200 words)

Data manipulation languages or DML are a computer language that gives a user a commands to manipulate data in a database. 
 
DML is high level language as it was designed to be easily interpreted by a human and give them easy access to the database. through DML, the user can has access to the SELECT, UPDATE, INSERT INTO and DELETE FROM commands. These commands are subject to subject to the rules of the database. If you break these rules the data will not be manipulated and the database will rollback the command.
 
The SELECT command is used to request a specific rows from a table in your database. The syntax is simple as the language intends and you simply select a column name from a table name. 
 
The UPDATE command is used to alter data in rows of a table in your database. The query will act on a set of records, not just one record so it is important to specify which record you want to update by id. To update data the user selects a value in a column through a table and applies a condition to it. 
 
The INSERT INTO command is used to add new records into a table in your database. It is primarily used to add records to the end of a table with an auto incremented primary key. to Insert records into a table, the user simply inserts a value into a column in a table. 
 
The DELETE FROM command is used to remove records from a table. It can be complicated because a deleted record cannot be associated with any other table.  To delete the user specifies a table name and a condition.


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

 Q4: 
 https://homes.cs.washington.edu/~mernst/advice/version-control.html

 Q5: 
 https://www.testbytes.net/blog/software-testing-standards/ 
 https://www.softwaretestingstandard.org/part2.php
 https://www.tutorialspoint.com/software_testing/software_testing_iso_standards.htm
 https://reqtest.com/testing-blog/the-a-to-z-guide-to-the-software-testing-process/
 https://artoftesting.com/difference-between-test-plan-and-test-
 
 Q6: https://www.proserveit.com/blog/information-security-requirements

 Q7: https://digitalguardian.com/blog/101-data-protection-tips-how-keep-your-passwords-financial-personal-information-safe

 Q8: https://www.nfplaw.org.au/sites/default/files/media/Privacy_Guide_Cth.pdf

 Q9,Q11,Q12:
     https://www2.cs.sfu.ca/CourseCentral/354/zaiane/material/notes/Chapter3/node2.html
     https://dondi.lmu.build/share/db/relational1.pdf
     https://coderacademy.instructure.com/courses/240/pages/introduction-to-databases?module_item_id=9871
     https://www.guru99.com/relational-data-model-dbms.html
     https://opentextbc.ca/dbdesign01/chapter/chapter-7-the-relational-data-model/
     https://www.cs.uct.ac.za/mit_notes/database/htmls/chp02.html 
     https://www.techopedia.com/definition/1179/data-manipulation-language-dml
     https://www.simplilearn.com/data-manipulation-in-sql-tutorial