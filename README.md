# SwiftEngineWithMongoDB
Working demo of "SwiftEngine with MongoDB"

POST Request:
> url: http://swapniljain.site.swiftengine.net/messages.ssp

> body:
{
  "topic": "Greetings"
  "message": "Hello World!"
  "email": "swapnil23@live.com"
}


>> Confirmation email will be sent to ("email": "swapnil23@live.com")

>> Message body will be saved in MongoDB.

Get Request:
> url: 
http://swapniljain.site.swiftengine.net/getMessages.ssp/Greetings

>> Will print list of all messages with topic "Greetings".

