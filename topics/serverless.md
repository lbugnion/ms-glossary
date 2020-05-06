> YouTube: O3KuatPZjfs

> Keywords: Serverless, Azure Function, Logic App, Trigger, Connector

> [This topic was published here](http://gslb.ch/wod-serverless).

# [Serverless](/topic/serverless)

<!-- YOUTUBEEMBED -->

[*(Download the video and captions)*](#download)

## Links

### Documentation

- [An introduction to Azure Functions](http://gslb.ch/446)
- [Serverless computing](http://gslb.ch/445)

### Microsoft Learn

- [Create serverless applications](http://gslb.ch/441) (*learning path*)
- [Refactor Node.js and Express APIs to Serverless APIs with Azure Functions](http://gslb.ch/442) (*module*)
- [Build Serverless APIs with Azure Functions](http://gslb.ch/443) (*module*)
- [Build automated workflows to integrate data and apps with Azure Logic Apps](http://gslb.ch/444) (*learning path*)

### Other links

- [Azure Pricing Calculator](http://gslb.ch/461)

<a id="download"></a>

## Download

[You can download this video here](<!-- DOWNLOAD -->).

There are also captions for the following language(s):

<!-- DOWNLOAD-CAPTIONS -->

> Learn about [downloading and showing captions here](/captions).

## Transcript

Hello and welcome to [Microsoft Azure Words of the Day](/), this is the show that teaches you the Azure vocabulary!

Today's word of the day is: Serverless

Serverless means that your code runs on a server, but you don't have to worry about that server. It is abstracted. As a developer, you can concentrate on writing the code, testing it and deploying it. Several features are automated: Starting the application, listening to events to start the execution of the code, scaling up and down when the demand fluctuates, etc. 

Typically serverless solutions are paid by the execution time, in a consumption model. Most cloud providers offer free tiers with which you can run a serverless application for a certain amount of time, or a certain amount of executions, for free.

On Microsoft Azure, there are quite a few solutions that you can use to run your code in a serverless manner, for example Azure Functions, Logic Apps, SignalR as a service, etc etc

Here is one example of serverless application on Azure: in an Azure Function, you start the execution of your code by observing some triggers. There are a number of trigger types, for example HTTP trigger to respond to an HTTP request; timer trigger to execute code on a schedule; event grid trigger to answer to events happening in another Azure service; Cosmos DB trigger to execute code when something changes in a database; and many more.

Or another example of serverless application: A Logic App also starts its execution when an event happens. There are many sources of events, for example when you receive an email in Outlook or Gmail, when a document is modified in Office 365, and many many many more.

One really nice feature of serverless is that your application will automatically scale up and down. Here we see how an Azure Function application is automatically scaling up to additional servers. This way you are covered, if a lot of people like your product, we will provide additional servers to cover the demand. And since you only pay for what you actually consume, serverless solutions end up being quite cost effective.

There are more serverless solutions on Azure, so don't forget to check the links here in order to learn more about that. Thank you so much for watching Microsoft Azure Words of the Day. Today's word of the day was: Serverless.

*Last modified: <!-- DATETIME -->*