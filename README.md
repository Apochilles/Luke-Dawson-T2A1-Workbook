#    T2A1 Workbook - RfQ Response
#    Luke Dawson 

### The ACME Corporation is interested in building a marketplace web application (app) using Rails for one of it’s product lines. To help it choose the vendor who will undertake the project they have released a RfQ. As an aspiring junior dev at an up and coming Sydney software startup (CAx-Dev) your manager has assigned you to assist with preparation of the RfQ response.

## Q1: Describe the architecture of a typical Rails application (200-300 words)

Ruby on Rails is a code library that expands the capabilities of the Ruby programming language. It is a web development framework capable of full-stack web application development specifically with a database back-end. 
 
At the heart of Rail’s design is Model-View-Controller (MVC) architecture. 
 
The Models govern the business logic of the application. Each model in an application controls a different table in the database, and it is within the model that the developer establishes relationships between tables and relevant data validations. 
 
The View governs the display logic and is the front-end of your web application. View files use HTML to structure the web page layouts but can also use embedded Ruby to retrieve database records and render them to the browser.

Assets are the files that supply our chosen visual content. We link these files into the View files for rendering in the browser. The developer can customise the views with CSS and Bootstrap. 
 
The Controller governs application flow between the Model and View. The Controller interprets browser requests and references Model data to respond to the Views to present the information. As Rails is designed using Ruby, each controller represents a class and you assign these classes methods through actions. 
 
Routes convert URL paths into a form our application can interpret. These are configured in the routes file and include a controller and an action specified to complete an HTTP request. 
 
The Ruby on Rails server creates a Web Server that listens to an IP and a port and is intractable with a web browser. On your local machine, this defaults to port 3000 and it is here that the developer can preview their web application.
 
The organisation of these aspects within the Rails folder structure allows developers easy navigation around the app, optimising speedy and intuitive development. 

## Q2: Identify a database commonly used in web applications (including Rails) and discuss the pros and cons of this database (150 - 250 words )

MongoDB is an open-source, dynamic, object-oriented and scalable database.
 
It is a NoSQL database which means it stores data as independent objects as opposed to data being stored in columns and rows as the standard in an SQL database. MongoDB represents these files as JSON or BSON documents. Developers can operate it with Javascript notation, making it a popular choice for web developers.
 
MongoDB excels in the simplicity of installation and implementation and provides high performance, high availability, and horizontal scaling.  
 
MongoDB supports Mac, PC, and Linux systems allowing different developers to work on their preferred systems.
 
MongoDB is a high-performance database because it accesses its indexed documents lightning fast. Relational databases have slower query times as they have to navigate nebulous fields and tables.
 
MongoDB is a horizontally scalable database. Through a process called Sharding, you can spread your database over multiple machines and combine their resources. This is much more flexible than competing databases that use vertical scaling. Vertical scaling restricts databases into only being hosted on one machine.  
 
These qualities make it very useful for Web developers looking to build web applications quickly, with diverse data that need to scale flexibly and efficiently. Examples of this include Codecademy, Google Search and Uber.
 
However, if you need table joins, you are out of luck because of the NoSQL nature of the database. MongoDB is best when you have vast amounts of data but don’t need it to be relational. It also may be unsuitable as you have to hire DB admins who fully understand NoSQL. It is extremely memory hungry because of its reliance on a memory-mapped file. This means your database is only as scalable as its access to system memory.


## Q3: Discuss the implementation of Agile project management methodology (200-300 words)

Agile software development encompasses a set of frameworks and practices that adhere to the Manifesto for Agile Software Development and its twelve principles. 
 
In the 1990s, the software industry met with a developmental crisis. The problem was that the industry was just not fast enough to meet the demands of the customer. Traditionally, progress was made sequentially, and they revealed the final product upon its completion. Companies found that by the time they were unveiling their products, the customer's expectations had shifted.
 
In 2011, after years of experimentation and discussion, a group of developers formalised a new method that addressed the concerns of the industry. This was the Agile Manifesto, and it contained 4 core values and 12 guiding principles.
 
But philosophy is one thing. Agile needed some methodologies to help teams incorporate these values and principles into their projects. Popular examples of this are Scrum, Kanban, and Extreme programming, but all these frameworks follow the same process. 
 
Developers must plan their project with a clear end goal and with Agile’s values and principles in mind. Then they must break this process down into a roadmap that will represent all the features that will make up their final product. 
 
They then must break each feature down into short development cycles called sprints. Before these sprints begin, the team must plan workload expectations and who will work on what. The team will visually document this plan and ensure it is accessible to every stakeholder. 
 
During the development process, there should be daily meetings. In these meetings, team members will briefly speak about what they accomplished the day before and what they plan to achieve today. It is important these meetings do not exceed 15 minutes so they don’t impact productivity. 
 
When finishing a sprint, there will be two meetings. One will be a presentation with the stakeholder to present your progress. The second meeting will be a breakdown of the previous sprint, a discussion on what the team can improve and how team members handle workloads during the sprint. 
 
Teams incorporating these methodologies into their projects will enjoy the values and principles of Agile software development.

## Q4: Provide an overview and description of a standard source control process (100-200 words)

Source control is how developers maintain, share and archive their source code.  

A developer will have a working copy of a project on their local machine and a repository usually hosted in the cloud. Source control allows the developer to keep a record of changes made during development. It allows many people to work on the same code without affecting each other's changes and allows a developer to access their code from different computers. 

Developer's local files are a playground for them to experiment with code to their heart's content. When you want to share or document their code, they can commit their changes to a repository. Sometimes a repo can contain edits we want to apply to our working copy, we call this process updating and we do this by pulling down the updated code.

There are two types of history on a repository. Linear history is a sequential list of changes, but there is also sometimes a branching history. A branching history will contain split versions that will merge again at a later commit.

Good source control practice is to commit code with a singular purpose and with a descriptive commit message. It is also important to share your changes regularly and make sure you’re updating to other's changes.

## Q5: Provide an overview and description of a standard software testing process (100-200 words)

Software testing is utilizing software to discover and document bugs. It is one of the ways we verify our code executes successfully and as intended. 

The software testing process is a process that ensures that software is monitored and bugs are eliminated in a timely and efficient manner.

A project should begin with a Test strategy and a Test plan. These formal documents contain the software systems, configurations, features and details of how the tests will be carried out. It will also include Processes, approaches and a schedule. 

Next, testers need to design the tests around what information they gathered during the strategy and testing phase. 

Consequently, they need to execute the tests as designed as per their project management methodology. 

Finally, they need to consider the exit criteria. All planned tests should be have been covered with a 90% success rate and all critical defects must be 100% fixed 

## Q6: Discuss and analyse requirements related to information system security (100-200 words)

A business's security requirements range vastly depending on what the company does and who and what it is responsible for. 

Identifying what aspects your business needs to protect itself against is extremely important whether it be malware threats, system availability loss or data compromise.

It is important to adapt and stay vigilant as these threats grow more intelligent and aggressive every day. 
 
There are three obligations a business must consider when implementing these defenses. Protecting their business, ensuring legal compliance, and protecting customer data.

IT security should begin with a contingency plan for the worst-case scenario. Then they need to identify the threats and prioritise them by severity and likelihood. The business needs to raise awareness of bad practices within the business to ensure every one is as protected as possible. Importantly, defenses need to be implemented and maintained. Finally, end-users should be prioritised. 

The users must be aware of potential risks we must discover what we're doing to safeguard their privacy. Implemented practices should be user-friendly and easy to maintain. 

Once everything is in place it is important that the IT security team is confident but they must stay vigilant and prepared for the evolving threats of the tech industry.

## Q7: Discuss common methods of protecting information and data (100-200 words)

In this modern age, it is extremely important to ensure you are as protected as possible against cyber threats. 
 
As a user, they must encrypt our data whenever possible. Mail programs on major operating systems now have encryption plugins that encrypt and decrypt messages to ensure they are not intercepted during sending. Another thing to ensure is that their OS of choice is automatically updating so you have the latest possible security features. 
 
They must also backup our data. This has never been easier as we can create backups on physical hard drives but they should also upload our files to safe storage in the cloud. Most devices have some automatic way of storing user data in the cloud so if you enable this you're safe knowing your backups are constantly updated. If you stop using a device you should wipe your hard disk to factory settings so you are protected if it is stolen or becomes lost
 
We must also keep up to data with malware protection by installing the latest software and doing regular scans to prevent malware from stealing our private information.
 
Never reuse a password and make sure you use passphrases to protect yourself from dictionary attacks. Never store your password on any device in any form.  

## Q8: Research what your legal obligations are in relation to handling user data (100-200 words)

When you are in a business that deals with user data it is important that you know your legal obligations when handling that user information. 

In Australia, you must conform to Australia's privacy principles if you: Provide a health service to a person or people. If you disclose personal information about an individual to anyone else. If you incentivise collecting information about an individual, is a contracted service provider under a Commonwealth agreement, if you are involved in credit reporting, have an annual turnover of $3 million or if you are associated with a body corporate that is subject to anything above on this list.
  
If you are subject to these privacy principles you must take steps to ensure you meet the legal guidelines. 
 
First is it our job to identify what kind of data we are handling. Is it personal, financial, or health-related?
 
Once we know what information we are handling, our highest priority is to make our clients aware that we are collecting this information. We must then explain what we intend to do with this information and who it will be shared with. If the information is sensitive (racial, political, religious, professional, sexual or criminal) ensure that the individual has consented to the gathering of this information. The clients must be aware that they have the right and ability to access and change this information at their discretion. 
 
The collected information is also privy to disclosure restrictions that may vary depending on the country or area they are disclosed in. 
 
By following these guidelines an organisation can hope to both protect a user's privacy and keep yourself out of legal implication.
 

## Q9: Describe the structural aspects of the relational database model. Your description should include information about the structure in which data is stored and how relations are represented in that structure. (100-200 words)


A relational database is a set of tables which is given a uniquely identifying name. Within each table are rows representing specific values that relate to each other in a meaningful way. These values are associated with attributes or columns in the table.
 
It is an effective design concept as it is simple and thus, is easy to pick up.
 
The theory of a relational database was built on the mathematical concept of a relation. Unlike alternatives like object databases, it's mathematical foundation lends itself to database algorithms.
 
When planning a relational database a developer creates a database schema. It it within the schema that the relations, attributes and domains of the tables and columns are determined. A database key or superkey is a way for user to uniquely identify a row of data within a table. 
 

## Q10: Describe the integrity aspects of the relational database model. Your description should include information about the types of data integrity and how they can be enforced in a relational database. (100-200 words)

We have four operations we can perform on a relational database: insert, delete, modify and select. 

Data integrity restricts these operations within a relational database. They are split into three categories: Domain, key, and referential integrity.

Domain constraints protect the way we accept data into the fields of our tables. In the schema, we specify data types such as integer and strings and determine their intended lengths. If the data we input is not allowed by our constraints it will be rejected. We also set whether we allow a field to be Null or not. The database will default to Null but there are situations where this not appropriate. 

Key constraints as rules we create for interaction between different tables and fields. Primary key constraints restrict any duplicate primary keys from being inserted into a row. Foreign key constraints prevent a row from being added, modified or removed unless it's foreign key matches a primary key in its parent table. A unique key constraint is another way to protect unique records in your database without relying on a primary or foreign key. To achieve this you must define a field as unique while generating it. Once this is done it will only accept a single null value and cannot have identical values in the database.  

Referential integrity constraints restrict table interactions to those with a matching primary and foreign key. This prevents orphan files from being created in a database. An orphan record is one that references a primary key that does not exist. To ensure this does not happen, we set up our tables and fields with our primary foreign key column set to references.  

## Q11: Describe the manipulative aspects of the relational database model. Your description should include information about the ways in which data is manipulated (added, removed, changed, and retrieved) in a relational database. (100-200 words)

Data manipulation languages or DML are a computer language that gives a user commands to manipulate data in a database. 
 
DML is a high-level language as it was designed to be easily interpreted by a human and give them easy access to the database. through DML, the user can have access to the SELECT, UPDATE, INSERT INTO and DELETE FROM commands. These commands are subject to the rules of the database. If you break these rules the data will not be manipulated and the database will roll back the command.
 
The SELECT command is used to request specific rows from a table in your database. The syntax is simple as the language intends and you simply select a column name from a table name. 
 
The UPDATE command is used to alter data in rows of a table in your database. The query will act on a set of records, not just one record so it is important to specify which record you want to update by id. To update data the user selects a value in a column through a table and applies a condition to it. 
 
The INSERT INTO command is used to add new records into a table in your database. It is primarily used to add records to the end of a table with an auto-incremented primary key. To insert records into a table, the user simply inserts a value into a column in a table. 
 
The DELETE FROM command is used to remove records from a table. It can be complicated because a deleted record associated with any other table will take any other fields with a foreign key with it.  To delete the user specifies a table name and a condition.

## Q12/13: Identify and explain the workings of TWO sorting algorithms and TWO search algorithms and discuss and compare their performance/efficiency (i.e. Big O) (600-1000 words)

Computers use algorithms to process data. Algorithms are procedures that the computer can follow to perform tasks in a deliberate and useful way.

Sorting algorithms are important when looking through a list of elements and finding context between them. Common uses are alphabetizing names, ranging prices by low and high and sorting entries from first to last. 

There are many sorting algorithms dependent on the context of the search ranging from very primitive to complicated and efficient.

An example of a sorting algorithm is Bubble sort. Bubble sort contrasts the first two elements of an array and exchanges them if element one is higher than element two. Bubble sort continues comparing elements in pairs in descending order. It will only stop when it has worked through every element in the array. This is necessary as Bubble sort will need to compare every element in the list to get a result. 

While it is an effective way to sort arrays, it is primitive and inefficient.  It needs to look at every element in an array to complete sorting. Therefore, the smaller the set of the data, the faster it will sort through the pairs in your array. 

Big O determines Bubble sort's best-case scenario as ``O(n) `` meaning it takes `` n `` iterations where `` n `` is the total elements in the list. This occurs when all elements in the list have already been sorted, therefore, no element will be swapped. If the list is unsorted in any way the time complexity with be determined to be `` O(n^2) ``. A common use case is when an unsorted list is small and a simple algorithm will be sufficient.

Another example of a sorting algorithm is the Insertion sort. Insertion sort constructs its array by one sorted element at a time. While similar to bubble sort, it is quicker as it doesn’t have to check every pair reducing the number of swaps needed to complete sorting. It is still slow when sorting large lists but it is twice as fast as Bubble sort. 

It is Identical to Bubble sort by Big O’s standards. It’s fastest time complexity is ``O(n) `` when the list is pre-sorted. If the list is unsorted in any way, then its time complexity with be determined as `` O(n^2) ``. A common use case is when a list is mostly sorted but a few elements are out of order. 

Search algorithms are an important part of many programs and websites. Without search algorithms, we would have to search through long manual lists to find the specific information we were looking for. 

We define searching, as finding `` x `` in a list of distinct elements to determine whether it is in the element list. If `` x = 0 ``, our search will not return a result.  

There are different many different search algorithms that have different use-cases dependant on the needs of the search. 

An example of a search algorithm is Linear Search. Linear search looks first the first list item to determine whether it is within your search criteria. If it is not it will move on the next item until it works the way through the entire list. It’s fastest time complexity will be ``O(1) ``, this occurs if there is only one element on the list and it’s the one you’re searching for. 

The worst-case will be ``O(N)`` if you are searching for an item that is not on the list but it will still have to iterate through every element to discover that. 

As linear search is the most primitive form of search it’s only use case is when a list is extremely small or only has one value. 

Another example of a search algorithm is Binary search. Unlike other examples, I have provided, a Binary search is efficient as it can finesse its search based on the user’s criteria. A binary search first halves the total number of elements and then locks on to the desired element to identify whether it exists or not. Its efficiency is due to the fact it is always splitting the total number of elements it needs to search, efficiently removing irrelevant elements. It is important to note that the list must be presorted before Binary search can be utilized effectively 

It’s best-case run time is `` O(1) `` meaning that the time taken is linear. This occurs when the value searched for is the point where the list is first split. 

It’s average and worst-case run time is ``O(log n)``. The average case has to make log n divisions until only one element is left on the list. The worst case is when the element it is searching for is not on the list.

A common use for Binary search is in large databases organised by a numbered key. 

## Q14:  Conduct research into a marketplace website (app) and answer the following parts:  (50 - 100 words per)

### Airbnb

 ### a. What software is used by the app?

Airbnb uses the Programming languages Ruby and Javascript. They are built upon a combination of Ruby on Rails and React framework. The app is hosted on an Nginx webserver. 

Airbnb can be accessed on all popular web browsers. It also has a useful application for Android and Apple devices, mobile and tablet. 

  ### b. What hardware is used by the app?

When Airbnb was conceived it was hosted on a local SQL database but as demands grew they developed into the cloud. Profile and property Images as stored on Amazon S3. General data is stored in a cloud-based RDS relational database. Hosting is provided by Amazon EC2 which migates high traffic spikes.Key-value storage is handled by Redis.

 ### c. Describe the interaction of technologies within the app

For the back-end Airbnb relies on Rails, making developing new features and scaling a breeze. To complement the framework they use Apache Thrift to bind C code with Ruby. Airbnb has plenty of dynamic data so it relies on ReactJS to control It's front-end and give it flexibility and efficiency. It also uses HTML5, CSS, jQuery, and elements of Node JS.

Airbnb uses an Nginx webserver to handle traffic demands with a proxy server to lighten the load. It also offers security and scalability. It uses Redis for caching to increase response times.

For storage, AirBNB originally used MySQL but changed to cloud storage once demands increased. They use Amazon RDS as a cloud database, EC2 for hosting and S3 and EBS for cloud storage.  

For the large amounts of user data, Airbnb uses Presto, Druid, and Airpal to handle the analytics and processing. 

 ### d. Describe the way data is structured within the app
Data is structured within the app to give users an optimal experience when navigating. They rely on a knowledge graph that delivers structured data linking their unique offerings with travelers around the world. 

From the home page, they offer a carousel delivering informed travel destinations. Once a user has chosen a location the app links location amenities with user interests to best serve their trip. The app them recommends nearby locations as it is proven through their research that travelers often stay near where they want to visit.

 ### e. Identify entities which must be tracked by the app

On Airbnb there is one user type. This user can both provide properties and rent properties simultaneously. Therefore, you must have a table that connects rentees with renters and this is done through a booking table. When a renter puts up a property they select a country, state and city from Airbnbs accepted locations. They then use Airbnb's house and room type options to best describe their home. Rentees can leave reviews for properties that will be attached to that property for future renters. Transactions are handled separately and the currency is converted to the desired currency of the renter. 


 ### f. Identify the relationships and associations between the entities you have identified in part (e)

Users:

- has many Bookings 
- has many Wishlists 
- has many Accommodations 

Accommodations:

- has many Bookings
- has many Users through Bookings
- has one Country
- has one Currency 
- has one City
- has one Property type
- has one Room Type 
- has one State 

 Bookings:
  
- has one User 
- has one Wishlist 
- has one Transaction

 Wishlist: 
 - has one User 
 - has many Accommodations 

 Transactions:
 - has one Currency 
 - has one Booking 
 - has one Accommodation 

 Reviews 
- has one User
- has many Accommodations  
- has many Bookings 

 Countries: 
 - has many Accommodations  

 Cities: 
 - has many Accommodations  

 States: 
 - has many Accommodations  

 Currencies: 
 - has many Transactions 

 Property types: 
 - has many Accommodations  

 Room types: 
 - has many Accommodations 

 
 ### g. Design a schema using an Entity Relationship Diagram (ERD) appropriate for the database of this website (assuming a relational database model)
 
### Airbnb ERD:

https://drive.google.com/file/d/1umKHbH8gwv17mt3oNIBiQd6xEBQE0ZJf/view



 














 ## References: 
 ### Q1:
 https://www.techcareerbooster.com/blog/ruby-on-rails-architecture-overview-for-beginners
 
 https://adrianmejia.com/ruby-on-rails-architectural-design/
 
 https://rubyonrails.org/
 
 https://whatis.techtarget.com/definition/business-logic
 
 https://medium.com/@sagar.mane006/understanding-rest-representational-state-transfer-85256b9424aa

 ### Q2: 
 https://www.mongodb.com/what-is-mongodb
 
 https://www.guru99.com/what-is-mongodb.html
 
 https://data-flair.training/blogs/advantages-of-mongodb/
 
 http://makble.com/the-advantages-and-disadvantages-of-mongodb

 ### Q3: 
 https://zenkit.com/en/blog/agile-methodology-an-overview/
 
 https://www.agilealliance.org/agile101/
 
 https://www.workfront.com/blog/the-beginners-guide-to-agile-project-management-methodology
 
 https://plan.io/blog/ultimate-guide-to-implementing-agile-project-management-and-scrum/

 ### Q4: 
 https://homes.cs.washington.edu/~mernst/advice/version-control.html

 ### Q5: 
 https://www.testbytes.net/blog/software-testing-standards/ 
 
 https://www.softwaretestingstandard.org/part2.php

 https://www.tutorialspoint.com/software_testing/software_testing_iso_standards.htm
 
 https://reqtest.com/testing-blog/the-a-to-z-guide-to-the-software-testing-process/
 
 
 https://artoftesting.com/difference-between-test-plan-and-test-
 
### Q6: 

https://www.proserveit.com/blog/information-security-requirements

### Q7: 

https://digitalguardian.com/blog/101-data-protection-tips-how-keep-your-passwords-financial-personal-information-safe

### Q8: 

https://www.nfplaw.org.au/sites/default/files/media/Privacy_Guide_Cth.pdf

### Q9,Q11,Q12:
https://www2.cs.sfu.ca/CourseCentral/354/zaiane/material/notes/Chapter3/node2.html

http://www.rampant-books.com/t_super_sql_124_referential_integrity_dri.htm

https://dondi.lmu.build/share/db/relational1.pdf

https://opentextbc.ca/dbdesign01/chapter/chapter-9-integrity-rules-and-constraints/

https://coderacademy.instructure.com/courses/240/pages/introduction-to-databases?module_item_id=9871

https://www.guru99.com/relational-data-model-dbms.html

https://opentextbc.ca/dbdesign01/chapter/chapter-7-the-relational-data-model/

https://www.cs.uct.ac.za/mit_notes/database/htmls/chp02.html 

https://www.techopedia.com/definition/1179/data-manipulation-language-dml

https://www.simplilearn.com/data-manipulation-in-sql-tutorial

### Q12, Q13:
https://betterexplained.com/articles/sorting-algorithms/

https://codeburst.io/algorithms-i-searching-and-sorting-algorithms-56497dbaef20

https://pediaa.com/what-is-the-difference-between-bubble-sort-and-insertion-sort/

https://brilliant.org/wiki/bubble-sort/

https://brilliant.org/wiki/insertion/

https://brilliant.org/wiki/binary-search/

### Q14: 
https://hub.packtpub.com/what-software-stack-does-airbnb-use/

https://www.freelancinggig.com/blog/2018/09/28/what-programming-language-is-airbnb-written-in/

https://medium.com/airbnb-engineering/accelerating-services-at-airbnb-by-building-a-blazing-fast-thrift-binding-for-ruby-8f63044ba149

https://www.nginx.com/resources/wiki/community/why_use_it/

https://redis.io/topics/introduction

https://redislabs.com/wp-content/uploads/2016/03/15-Reasons-Caching-is-best-with-Redis-RedisLabs-1.pdf

https://medium.com/airbnb-engineering/druid-airbnb-data-platform-601c312f2a4c

https://medium.com/airbnb-engineering/data-infrastructure-at-airbnb-8adfb34f169c

https://learn.g2.com/structured-vs-unstructured-data