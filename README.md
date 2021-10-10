# Notas

Backend con autenticación de JWT y MongoDB Atlas AWS
# MONGO DB SETUP

 Cloud option: go to https://www.mongodb.com/cloud/atlas and sigin. After create a cluster, choose in "your_cluster" connect button the connecet using MongoDbCluster. You will have to download it. You must create a user too. Then copy your conection url in the .env file DB_CONECTION constant.

 Local (windows): 
  1- Download and install MongoDb
  2- Add to the environment path where your mongoDB is installed (for example: C:\Program Files\MongoDB\Server\5.0\bin\)
  3- Now in your CMD you will can run mongo typing "mongo"
  4- use "show database" for see them

  TO check your DB collections you can use Compass with "mongodb://localhost" conection string OR 
  use the VSC plugin MongoDB for VS Code  

