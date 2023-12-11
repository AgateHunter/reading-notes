# MongoDB and Mongoose

|                SQL                 |                   NoSQL              |
|------------------------------------|--------------------------------------|
| Relational Databse (RDMS)          | Typically non-relational/distributed |
| Table based database               | Document based - no standard schema  |
| Scale by increasing hardware power | Scaled by increasing servers         |
| Predefined schema                  | Dynamic schema for unstructured data |
| Good for complex query             | Not as powerful for complex queries  |


1. What kind of data is a good fit for an SQL database?

- SQL databases handle large tables with many rows of data very well. 

2. Give a real world example.

- If you needed to keep the inventory of a public library, including the *title*, *author*, *quantity*, *publish date*, and *current status*, that would be best held in a table. This would work well in a SQL database.

3. What kind of data is a good fit a NoSQL database?

- Document based, key-value pairs, graph databases, or wide-column stores work best in NoSQL databases. These are types of data that do not have a standard structure schema they have to stick with.

4. Give a real world example.

- If you wanted to create a website where people could write and publish blog posts, using a NoSQL database would be best. The content isn't well sorted into a table, and it needs to be very flexible.

5. Which type of database is best for hierarchical data storage?

- NoSQL, as it has a better way to store key-value pairs, big data, and JSON data. 

6. Which type of database is best for scalability?

- SQL, because it is vertically scaable. By increasing the CPU, RAM, SSD, etc... you can manage larger loads. 


## SQL vs NoSQL

1. What does SQL stand for?

- **S**tructured **Q**uery **L**anguage

2. What is a relational database?

- A database that works by using a relational model. It will hvae these key concepts:
> - Table
> - Keys
> - Relationships
> - Normalization
> - Common Language (SQL)

3. What type of structure does a relational database work with>

- Relational databases work best with a **table** structure for organization and storage of data.

4. What is a schema?

- Schema is the structure that defines how data is going to be organized int he database. It shows how the relationship between data will be handled, and how it will be created and managed. 

5. What is a NoSQL database?

- NoSQL databases are able to handle many different models and structures; not just reliant upon relational databases.

6. How does it work?

- Each record in the database can have different fields that can still be recorded in the database. This means NoSQL is much more flexible and can use JSON, key-value pairs, columns, nodes, etc...

7. What is inside of a MongoDB databse?

- MongoDB uses *collections* that are a group of documents. This makes it a document-oriented database and stores files like JSON.

8. Which is more flexible - SQL or MongoDB? and why?

- It honestly depends on your use case for which database you'd want to use. With modern updates, some relational databases can have the flexibility that you often find in NoQL databases.

9. What is the disadvntage of a NoSQL databse?

- The flexibility and lack of standard structure/schema makes it challenging to move between different NoSQL databases. Unlike SQL databases, there are limited areas to go for support and users often have to rely on community forums for help. 
