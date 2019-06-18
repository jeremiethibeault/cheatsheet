# MongoDB

## Commands

### mongod

- `mongod --dbpath data/db` : Starts the MongoDB deamon with the provided path of the database.

### mongo

- `mongo` : Opens a Mongo database.

### use

- `use MyDatabase` : Opens or creates a new database `MyDatabase`.

### db object

- `db.createCollection("myTable")` : Creates a table `myTable`.
- `db.myTable.insertMany([{"Property": "Value"}, {"Property2" : "Value"}]` : Insert items in `myTable`.
- `db.myTable.find({}).pretty()` : Outputs the content of `myTable`.