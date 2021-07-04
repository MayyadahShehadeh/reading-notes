## What kind of data is a good fit for an SQL database?
For an SQL Database, a good fit is table based data. Also, "SQL databases are best fit for heavy duty transactional type applications, as it is more stable and promises the atomicity as well as integrity of the data.", therefore it is also a good fit for "the complex query intensive environment" - Source

## Give a real world example.
An example of heavy duty transactional applications being used can be within a grocery store sale data.

## What kind of data is a good fit a NoSQL database?
"NoSQL databases can be classified on the basis of way of storing data as graph databases, key-value store databases, document store databases, column store database and XML databases." - Source


## Which type of database is best for hierarchical data storage?
The NoSql is best fit for hierarchial data due to the key value storing.

## Which type of database is best for scalability?
Overal I think that the NoSql would be the best fit for scalability, firstlt, both SQL and NoSQL have scalibility compatibilty - just one is vertically and the other is horzontally. To increase load on SQL you will just need to update the CPU,RAM,SSD,etc, for each server, where as the NoSQL requires simply adding servers.

## What does SQL stand for?
#SQL# stands for Structured Query Language
What is a realational database? Relational databases have a structure that will allow for access in relation to other data in the database.

## What type of structure does a relational database work with? 
A relational database works with data organized in tables.

## What is a ‘schema’?
A schema is a combination of rules that determine how data is added to a database. It can have different fields like id, name, description, etc. Each new entry will have values corresponding to the schema.

## What is a NoSQL database? How does it work?
What is inside of a Mongo database? MongoDB is a NoSQL database. It follows these guidelines below.

A NoSQL database is better at storing large amounts of data. No tables, but collections of data. There are documents inside of collections, which resemble JSON. They don't have to follow strict rules of needing all the same rules of a schema- they can have different key/value pairs.

## In general, no relations are found in a NoSQL.
This makes it less good for managing complex queries.

One disadvantage is that NoSQL databases can lead to duplicate data.

## Which is more flexible - SQL or MongoDB? and why.
This is flexible because you can add new data with different parameters that you hadn't initially set up. If you were using SQL, you would need to go back and add data if you added a new field.