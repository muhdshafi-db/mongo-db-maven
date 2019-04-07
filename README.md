# mongo-db-maven
## Create DB directory and config file 
	E:\MongoData\data  
	E:\MongoData\mongo.config  
### content  
	##store data here
	dbpath=E:/MongoData/data

	##all output go here
	logpath=E:/MongoData/log/mongo.log
## start server  
	C:\Program Files\MongoDB\Server\4.0\bin>mongod.exe --dbpath E:\MongoData\data  
## start shell	  
	C:\Program Files\MongoDB\Server\4.0\bin>mongo.exe  
	
