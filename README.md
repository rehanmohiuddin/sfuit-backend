# sfuit-backend

This Repository is about Interconnecting the SfUIT-ESP8266 with SfUIT-Frontend, that is it consists all the backend process.
After the data received from ESP8266 to AWS IOT Core, these values are sent to Mongo DB and also parallely to our Web App thorugh JAVA SDK provided in AWS.
From subscribed topic which is ***apror/#***, we extract ID which is unique for each ESP8266 and then seperate colletive data of each ID accordingly.
**Here a unique  ID refers to a unique peron** 
The Data of User is then stored in MongoDb and sent to Web App simultaneously that is to users device.
If any abnormal data of user is encountered, then Notification is trigerred as per the health parameter of User.
All these Logics behind BackEnd are mentioned in CODE.

I have achieved all these using MERN stack, where Mongo DB is used for storing Unique User's data, Express JS is used for creating Roots and Node, an environment for running
MERN stack.

## CITATIONS
NPM Library
