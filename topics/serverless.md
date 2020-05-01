> YouTube: QG2iVUOxA68

> Keywords: Serverless, Azure Function, Logic App, Trigger, Connector

> [This topic was published here](http://azurewordsoftheday.cloud/topic/serverless/serverless).

# [Serverless](/topic/serverless/serverless)

<!--YOUTUBEEMBED -->

## Links

### Documentation

- [An introduction to Azure Functions](http://gslb.ch/446)
- [Serverless computing](http://gslb.ch/445)

### Microsoft Learn

- [Create serverless applications](http://gslb.ch/441) (*learning path*)
- [Refactor Node.js and Express APIs to Serverless APIs with Azure Functions](http://gslb.ch/442) (*module*)
- [Build Serverless APIs with Azure Functions](http://gslb.ch/443) (*module*)
- [Build automated workflows to integrate data and apps with Azure Logic Apps](http://gslb.ch/444) (*learning path*)

## Transcript

Hello and welcome to [Microsoft Azure Words of the Day](/), this is the show that teaches you the Azure vocabulary!

Today's word of the day is: Serverless

Serverless means that your code is running on a server, but you don't have to worry about that server. It is abstracted. On Microsoft Azure, there are a few solutions you can use to run code in a serverless manner, for example Azure Functions, Logic Apps, SignalR as a service, etc etc

In an Azure Function, you can start the execution of your code by observing some triggers. There are a number of trigger types, for example HTTP triggers to respond to an HTTP request; timer trigger to execute code on a schedule; event grid triggers to answer to events happening in another Azure service; Cosmos DB trigger to execute code when something changes in a database; and many more.

Azure Functions also have bindings, which allow them to input and output values from and to different sources. Don't forget to check the documentation here to get more information about that!

A Logic App also starts its execution when an event happens. There are many sources of events, for example when you receive an email in Outlook or Gmail, when a document is modified in Office 365, and many many many more.

One really nice feature of serverless is that your application will automatically scale up and down. Here we see how an Azure Function application is automatically scaling up to additional servers when a lot of requests arrive. This way you are covered, if a lot of people like your product, we will provide additional servers to cover the demand. And since you only pay for what you actually consume, serverless solutions end up being quite cost effective.

There are more serverless services on Azure, so don't forget to check the links here to know more about that. Thank you so much for watching Microsoft Azure Words of the Day. Today's word of the day was: Serverless.