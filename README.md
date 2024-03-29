## Multiplayer Movement Sync - AWS

* Uses API Gateway to establish a websocket connection 
* Three Lambda functions that handle match making, game play communication, and disconnections respectively
* A game session DynamoDb table is used to track the websocket connection ids and game status

## Companion Unity Repository

* https://github.com/BatteryAcid/multiplayer-movement-sync-unity

## Tutorial Video 

* https://youtu.be/cMGLFkG1iDg  
    
## 👋 Let's talk shop 👇  
[Discord] https://discord.gg/psjbBDvNBK  
[Twitter] https://twitter.com/BatteryAcidDev

### Sources ###

* https://www.freecodecamp.org/news/real-time-applications-using-websockets-with-aws-api-gateway-and-lambda-a5bb493e9452/
* https://aws.amazon.com/blogs/compute/announcing-websocket-apis-in-amazon-api-gateway/
* https://github.com/aws-samples/simple-websockets-chat-app

