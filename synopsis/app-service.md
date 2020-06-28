# Azure Words of the Day Synopsis: App Service

## Submitted by

LBugnion@Microsoft.com

@LBugnion

> [This topic was published here](http://azurewordsoftheday.cloud/topic/app-service/app-service).

## Short description

a web server "as a service" on Azure, allowing you to run HTTP-based applications on Windows and Linux

## Phonetics

![Phonetics image](images/app-service/app-service.png)

## Keywords:

App Service, Web Server, ASP.NET, Web Api

## Demos

- Show the app service in the portal
- Show the Tailwind traders app, mention supported frameworks
- Show metrics in the portal, mention Application Insights
- Show Log Stream

## Links to docs

- [App Service overview](https://docs.microsoft.com/en-us/azure/app-service/overview)
- [App Service documentation](https://docs.microsoft.com/en-us/azure/app-service)

## Links to Learn

- [Deploy a website to Azure with Azure App Service](https://docs.microsoft.com/en-us/learn/paths/deploy-a-website-with-azure-app-service) *(learning path)*
- [Capture Web Application Logs with App Service Diagnostics Logging](https://docs.microsoft.com/en-us/learn/modules/capture-application-logs-app-service) *(module)*
- [Create and publish a web application with Azure App Service and Visual Studio Code](https://docs.microsoft.com/en-us/learn/modules/create-publish-webapp-app-service-vs-code) *(module)*

<a id="script"></a>

## Script

> ~ 15 seconds intro

Today's words are: App Service. 

Hello and welcome to Microsoft Azure Words of the Day,
the show that teaches you the Azure vocabulary!

> ~ 35 seconds on camera

An App Service is a web server running as a service on Azure. So you can run web based applications, that means HTTP based applications such as a mobile backend, a website, a web API etc. The really cool thing is that you can choose Windows or Linux as your operating system, so you have a choice. And you can deploy your code, either in a Docker container, or directly from a Github repository, other repositories or from a continuous deployment solution. 

> Demo portal, ~ 30 seconds

Around App Services, you can also configure a lot of features for example different deployment solutions,  Authorization and Authentication, Identity, Backups, Custom domains, TLS and SSL to enable HTTPS, you can also automatically scale up and down for example to respond to a lot of demand very fast.

> cut to Tailwind, ~ 15 seconds

Let's check the application, now this here is an ASP.NET Core application running a React.JS front end, but App Services also support classic .NET, Java, Node.js, Ruby, Python, PHP, so you have a choice for your framework.

> Cut to graphs, ~ 15 seconds

In the Azure portal you can check the health of your app service, and there is also Application Insights which is a very rich monitoring solution.

If I scroll down further we can see more monitoring solutions, for example the Log Stream which allows me to see what is happening in my application in real time. That's quite handy to avoid having to download the logs.

> Cut to camera, ~ 30 seconds

App Services have a lot of additional functionalities, so don't forget to check the links here in order to know more about that. Thank you so much for watching Microsoft Azure Words of the Day. Today's words of the day were: App Service.
