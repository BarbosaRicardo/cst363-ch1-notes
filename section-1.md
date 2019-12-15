#Other Client/server architectures
- A client/server system can include additional servers, an application server ot a web server 
- Application servers hold business components that do part of the processing of the application 
    - These components are used to process database requests from the user interface running on the client 
- Web servers are meant to hold web applications and web services. 
    - Web applications are made to run on a web server 
    - Web services are like business components designed to run on a web browser
- In a web-based system, a web browser running on a client sends a request to a web server over the internet 
    - The web server processes the request and passes any requests for data on to the DBMS 
- More complex system architecture can include two or more application servers, web servers, and database servers 

#AN INTRODUCTION TO THE RELATIONAL DATABASE MODEL 
- A relational databse consists of tables.  
    - Tables consists of rows and columns, which can also be referred to as records and fields 
- A table is typically modeled after a real-world entity, such as an invoice or a vendor 
- A column represents some attribute of the entity, such as the amount of an invoice or a vendor's address
- A row contains a set of values for a single instance of the entitym such as one invoice or one vendor
- The intersection of a row and a column is sometimes called a cell. 
    - A cell stores a single value 
- Most tables have a primary key that uniquely id's each row in the table. 
    - The pk is usually a single column, but it can also consist of two or emore columns
    - If a pk uses two more more columns, it's called a composite primary key.
- In addition to primary keys, some DBMS let you define one or more non-primary keys.
    - In MySQL, these keys are called unique keys. 
    - Like a primary key, a non-primary key uniquely identifies each row in the table 
- A table can also be defined with one or more indexesf. An index priovudes an efficient way to access 
    data from a table based on the values in specific columns.
    - An index is automatically created for a table's primary and non-primary keys.



