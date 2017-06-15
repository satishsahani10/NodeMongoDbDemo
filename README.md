# NodeMongoDbDemo

Steps to run the application

Installtion
1. Install node js
  https://nodejs.org/en/download/

2. Install mongodb
  https://www.mongodb.com/download-center

3. Navigate to mongod.exe folder and open up terminal and run following command to start MongoDB Server at default port.
  
  mongod --dbpath "c:/Users/Satish/Desktop/mongoData" 
  
4. Now open up another terminal of mongod and run following command.
  mongo
  
5. Now open up node js terminal and run the following command to install mongoose
  npm install --save mongoose
  
6. Then run the following command to install express framework
  npm install --save express
 
7. Then navigate to NodejsApp folder and run the following command
  npm start
  
  This will start listening on port 3000
  
  Now, Our API is running
  
 8. Then Navigate to NodeWebApp/Views folder and open index.html in any browser
 
 There you see list of options(Create user, Show All user, Update User and Delete user)
 
 Make sure the API is running before performing any action.
