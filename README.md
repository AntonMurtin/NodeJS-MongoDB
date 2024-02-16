# Get-Started Node.JS

Repository to help getting started with MongoDB Node.JS driver connecting to MongoDB Atlas.

## Information

npm install
Prerequisites
You need git to clone the repository. You can get git from http://git-scm.com/.

A number of node.js tools is necessary to initialize and test the project. You must have node.js and its package manager (npm) installed. You can get them from http://nodejs.org/. The tools/modules used in this project are listed in package.json and include express, mongodb and mongoose.

Have Docker running on your machine. You can download and install from: https://docs.docker.com/install/

### MongoDB Atlas

In order to execute the code example, you need to specify `MONGODB_URI` environment variable to connect to a MongoDB cluster. If you don't have any you can create one by signing up [MongoDB Atlas Free-tier M0](https://docs.atlas.mongodb.com/getting-started/). 

##  Execution Steps 

Execute the helper shell script followed by the MongoDB URI that you would like to connect to. 
```
./get-started.sh "mongodb+srv://usr:pwd@example.mongodb.net/dbname?retryWrites=true"
```

To use a different driver version, specify the driver version after the MongoDB URI. For example:
```
./get-started.sh "mongodb+srv://usr:pwd@example.mongodb.net/dbname?retryWrites=true" 4.4.1
```

## Tutorials

* [MongoDB Node.JS driver documentation](https://docs.mongodb.com/drivers/node/)
* [Quickstart Node.JS and MongoDB: How to Connect](https://www.mongodb.com/blog/post/quick-start-nodejs-mongodb--how-to-get-connected-to-your-database)


## Disclaimer

This software is not supported by [MongoDB, Inc](https://www.mongodb.com)
under any of their commercial support subscriptions or otherwise. Any usage is at your own risk.

url: https://long-rose-chicken-tam.cyclic.app