# Official Docs
- Installation Guide (Ubuntu): https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/
- mongo Shell Quick Reference: https://docs.mongodb.com/manual/reference/mongo-shell/

# Ubuntu
### Terminal Commands
```Bash
# start MongoDB
sudo systemctl start mongod

# stop MongoDB
sudo systemctl stop mongod

# restart MongoDB
sudo systemctl restart mongod

# check current status of MongoDB
sudo systemctl status mongod

# start/enter mongo shell 
mongo

# create a database/collection from a single JSON Array .json file
mongoimport --db=<dbName> --collection=<collectionName> --file=<filePath> --jsonArray
```

## Mongo Shell Commands
```Bash
# list all current DBs
show dbs

# switch to a DB
use <dbName>

# show all collections in the current DB
show collections

# display name of DB currently in use
db

# display all records in a collection
db.<collectionName>.find()

# drop a collection
db.<collectionName>.drop()
```