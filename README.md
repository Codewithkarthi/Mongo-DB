# Mongo-DB:
MongoDB is a document database. It stores data in a type of JSON format called BSON.It is a no sql database .

A record in MongoDB is a document, which is a data structure composed of key value pairs similar to the structure of JSON objects.


# Istall mongoshell (mongosh)

after installation check that the mongodb is installed 
" mongosh --version "

# Connect to the database
To connect to your database, you will need your database specific connection string.

In the MongoDB Atlas dashboard, under "Databases", click the "Connect" button for your Cluster.

Next, choose "Connect with the MongoDB Shell".

Copy your connection string.

Example
Your connection string should look similar to this:

mongosh "mongodb+srv://cluster0.ex4ht.mongodb.net/myFirstDatabase" --apiVersion 1 --username YOUR_USER_NAME
