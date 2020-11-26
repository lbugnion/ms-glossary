# Azure Words of the Day Synopsis: Cosmos DB

## Submitted by

Name: Laurent Bugnion

Email: lbugnion@microsoft.com

Twitter: @LBugnion

GitHub: LBugnion

## Short description

A fully managed NoSQL database running on Azure, for modern app development.

## Phonetics

https://tophonetics.com/

ˈkɑzmoʊs db

## Topics

- Global replication
- Multi model
- Service level agreements

## Keywords:

Database, SLA, service level agreement, MongoDB, Mongo, Cassandra, Gremlin, Gremlin Graph, NoSQL, No SQL, SQL, metrics

## Demos

- Show how to create a free DB
- Show the global replication
- Show the metrics 
- Show the data explorer / Azure storage explorer

## Links to docs

- [Welcome to Azure Cosmos DB](https://docs.microsoft.com/en-us/azure/cosmos-db/introduction)

## Links to Learn

> As part of the preparation, prepare a list of links to the documentation that you will use to prepare the content. These links will be included in the website too.
> [See the notes](../instructions/synopsis-template-notes.md#learn)

>For example:

- [Create serverless applications](https://docs.microsoft.com/en-us/learn/paths/create-serverless-applications) (*learning path*)
- [Refactor Node.js and Express APIs to Serverless APIs with Azure Functions](https://docs.microsoft.com/en-us/learn/modules/shift-nodejs-express-apis-serverless) (*module*)

## Script

Today's words of the day are: Cosmos DB.

Hello and welcome to Microsoft Azure Words of the Day, the show that teaches you the Azure vocabulary!

Cosmos DB is one of the core services of Azure, and in fact Azure and Microsoft itself run on Cosmos DB. This NoSQL database is available in every region where Azure itself is available.

> Demo: Show a Cosmos DB in the portal

NoSQL means that the data in Cosmos DB is semi-structured, somewhere between a traditional SQL database, also called relational data, and unstructured data such as audio or video files, PDFs etc. For example, using one of the Cosmos DB SDKs, you can easily serialize entities to Cosmos DB.

> Show data explorer with JSON documents

The data in Cosmos DB can easily be replicated worldwide to reduce the latency when your users are accessing it in different parts of the world. This also increase the availability of your data, with automatic failover in case one the regions becomes unavailable.

> Demo: Show the global replication in the Azure Portal

Another great feature of Cosmos DB is that it supports data in different models, such as Key-Value, Column-Family, Documents, Graph.

