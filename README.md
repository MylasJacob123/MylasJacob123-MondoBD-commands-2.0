**Start the MongoDB Server by opening a terminal or command prompt and type the following command :**

mongod

**Check MongoDB Service to see if MongoDB is installed as a service, ensure the service is active by typing the following command :**

net start MongoDB

**To start your mongo shell type the following command :**

mongosh

**To create or switch to Database type :**

use Codetribe

**To create a collection or collections :**

db.createCollection("Facilitators"),
db.createCollection("Trainees"), 
db.createCollection("Projects")

**To see collections type  the following command :**

show collections

**To use and see the data of a specific collection type  the following command :**

db.Facilitators.find(),
db.Trainees.find(),
db.Projects.find()

**To insert data into collection type the following :**

db.Facilitators.insertOne({name: "KB", location: "Kimberley", course: "Fullstack Development"}),

db.Trainees.insertOne({name: "Lebogang Mylas", location: "Kimberley", facilitator: "KB"}),

db.Projects.insertOne({name: "First MongoDB Project", course: "Fullstack Development", lesson: "MongoDB"}),
