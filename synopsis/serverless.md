# Synopsis: Serverless

## Submitted by

LBugnion@Microsoft.com

> [This topic was published here](http://azurewordsoftheday.cloud/topic/serverless/serverless).

## Phonetics

ˈsɜːvəlɛs

![Phonetics image](images/serverless/Serverless.png)

## Keywords:

Serverless, Azure Function, Logic App, Trigger, Connector

## Demos

- Showing the triggers.
- Show the documentation about bindings.
- Show a functions app scaling up.
- Show logic apps connectors.

## Links to docs

- [An introduction to Azure Functions](https://docs.microsoft.com/en-us/azure/azure-functions/functions-overview)
- [Serverless computing](https://azure.microsoft.com/en-us/overview/serverless-computing)

## Links to Learn

- [Create serverless applications](https://docs.microsoft.com/en-us/learn/paths/create-serverless-applications) (*learning path*)
- [Refactor Node.js and Express APIs to Serverless APIs with Azure Functions](https://docs.microsoft.com/en-us/learn/modules/shift-nodejs-express-apis-serverless) (*module*)
- [Build Serverless APIs with Azure Functions](https://docs.microsoft.com/en-us/learn/modules/build-api-azure-functions) (*module*)
- [Build automated workflows to integrate data and apps with Azure Logic Apps](https://docs.microsoft.com/en-us/learn/paths/build-workflows-with-logic-apps) (*learning path*)

## Script

> ~ 15 seconds intro

Hello and welcome to Microsoft Azure Words of the Day,
the show that teaches you the Azure vocabulary!
Today's word is: Serverless

> ~ 55 seconds on camera

Serverless means that your application runs on a server, but you don't have to worry about that server. It is abstracted. On Microsoft, there are a few solutions you can use to run code in a serverless manner, for example Azure Functions, or Logic Apps.

> Portal triggers

In an Azure Function, you can start the execution of your code by observing some triggers. There are a number of trigger types, for example HTTP triggers to respond to an HTTP request; timer trigger to execute code on a schedule; event grid triggers to answer to events happening in another Azure service; Cosmos DB trigger to execute code when something changes in a database; and many more.

> Documentation bindings

Azure Functions also have bindings, which allow them to input and output values from and to different sources. Don't forget to check the documentation here to get more information about that!

> logic app designer then cut to connectors

A Logic App also starts its execution when an event happens. There are many sources of events, for example when you receive an email in Outlook or Gmail, when a document is modified in Office 365, and many many many more.

> Demo scale up

One really nice feature of serverless is that your application will automatically scale up and down. Here we see how an Azure Function application is automatically scaling up to additional servers when a lot of requests arrive. This way you are covered, if a lot of people like your product, we will provide additional servers to cover the demand. And since you only pay for what you actually consume, serverless solutions end up being quite cost effective.

> Cut to camera

There are more serverless services on Azure, so don't forget to check the links here in order to learn more about that. Thank you so much for watching Microsoft Azure Words of the Day. Today's word of the day was: Serverless.
