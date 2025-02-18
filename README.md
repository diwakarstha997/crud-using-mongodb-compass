# Creating Database on MongoDB compass and Peforming queries through mongosh
> In this document we are exploring how we can create database and collections , and how can we perfrom queries in them using MongoDb Compass and Mongosh(MongoDb Shell). For this we are taking finance tracker as an example for which we will be creating a database and five collections within them.

# Tools Used
1. MongoDb Compass
2. mongosh (MongoDb Shell)

# Prerequisite
Install the mogngoDb and mongo compass based on your system [MongoDb Installation Documentation](https://www.mongodb.com/docs/manual/administration/install-community/) & [MongoDb Compass Installation Documentation](https://www.mongodb.com/docs/compass/current/install/). 

# Steps to create database with collections using mongo compass
## 1. Creating Connection / Using exisiting Connection 
> Firstly, launch mogodb compass, you can see Add new connection 

![Add new connection](add-new-connection.png)

> OR, select the existing connection you have created one to start connection

![Select existing connection](existing-connection.png)

## 2. Creating a Database in Connection
> To create a database click (+) icon on existing connection

![Add new database](add-new-database.png)

> Fill the database information with one collection and click create

![Create-database](create-database.png)

> Database has been created successfully 

![Create-database](database.png)

## 3. Adding collection to Database and inserting data
> To add collection just on right side of the database, click on add icon.

![Add collection](add-collection.png)

> After that form appears asking the collecton name, in our case it's expense and click on create collection after filling the info

![Collection form](collection-form.png)

> Now lets add some data to the collection named expense for that select collection and click on add data, this gives you two option either insert document or just inport json file. Here we will be inserting document

![Add data](add-data.png)

> Add json data to the document, here we are inserting expense data and click insert.

![Insert data](insert-data.png)
