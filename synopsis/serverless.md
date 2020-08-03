# Microsoft Glossary Synopsis: Serverless

## Submitted by

LBugnion@Microsoft.com

@LBugnion

> [This topic was published here](https://wordsoftheday.azurewebsites.net/topic/serverless/serverless).

## Short description

a way to run applications on a server without having to manage this server

## Phonetics

ˈsɜːvəlɛs

## Notes

- Consumption model
- Typically cheaper
- Some examples from Azure
  - Azure Functions
  - Logic apps
  - Others?
- Automatic scale

## Keywords

Serverless, Azure Function, Logic App, Trigger, Connector

## Demos

- Showing the triggers.
- Show the documentation about bindings.
- Show a functions app scaling up.
- Show logic apps connectors.

## Links to docs

- [An introduction to Azure Functions](https://docs.microsoft.com/azure/azure-functions/functions-overview)
- [Serverless computing](https://azure.microsoft.com/overview/serverless-computing)

## Links to Learn

- [Create serverless applications](https://docs.microsoft.com/learn/paths/create-serverless-applications) (*learning path*)
- [Refactor Node.js and Express APIs to Serverless APIs with Azure Functions](https://docs.microsoft.com/learn/modules/shift-nodejs-express-apis-serverless) (*module*)
- [Build Serverless APIs with Azure Functions](https://docs.microsoft.com/learn/modules/build-api-azure-functions) (*module*)
- [Build automated workflows to integrate data and apps with Azure Logic Apps](https://docs.microsoft.com/learn/paths/build-workflows-with-logic-apps) (*learning path*)

## Script

> ~ 15 seconds intro

Today's word is: Serverless.

Hello and welcome to Microsoft Azure Words of the Day,
the show that teaches you the Azure vocabulary!

> ~ 30 seconds on camera

Serverless means that your code is running on a server, but you don't have to worry about that server. It is abstracted. As a developer, you just have to worry about writing the code, testing it and deploying it. Several features are automated: Starting the application, listening to events to start the execution of the code, scaling up and down when the demand fluctuates, etc. It removes much of the infrastructure worries from the equation.

> Show the pricing calculator for functions

Typically serverless solutions are paid by the execution time, in a consumption model. This is different from a subscription model where you pay an amount every month or every year. Most cloud providers offer free tiers with which you can run a serverless application for a certain amount of time, or a certain amount of executions, for free.

> Logos on the screen

On Microsoft Azure, there are quite a few solutions you can use to run code in a serverless manner, for example Azure Functions, Logic Apps, SignalR as a service, etc etc

> Portal triggers

Here is one example of serverless application on Azure: in an Azure Function, you start the execution of your code by observing some triggers. There are a number of trigger types, for example HTTP triggers to respond to an HTTP request; timer trigger to execute code on a schedule; event grid triggers to answer to events happening in another Azure service; Cosmos DB trigger to execute code when something changes in a database; and many more.

> Documentation bindings

Azure Functions also have bindings, which allow them to input and output values from and to different sources. Don't forget to check the documentation here to get more information about that!

> Logic app designer then cut to connectors

Or another example of serverless application: A Logic App also starts its execution when an event happens. There are many sources of events, for example when you receive an email in Outlook or Gmail, when a document is modified in Office 365, and many many many more.

> Demo scale up

One really nice feature of serverless is that your application will automatically scale up and down. Here we see how an Azure Function application is automatically scaling up to additional servers when a lot of requests arrive. This way you are covered, if a lot of people like your product, we will provide additional servers to cover the demand. And since you only pay for what you actually consume, serverless solutions end up being quite cost effective.

> Cut to camera

There are more serverless services on Azure, so don't forget to check the links here in order to learn more about that. Thank you so much for watching Microsoft Azure Words of the Day. Today's word of the day was: Serverless.
