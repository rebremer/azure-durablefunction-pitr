# Restore data lake

This repo shows an example how to do point-in-time recovery (pitr) on an Azure Storage account with Hierarchical Namespace Enables (HNS). For that purpose, an Azure Durable Functions is used following the fan-in/fan-out pattern described [here](https://docs.microsoft.com/en-us/azure/azure-functions/durable/durable-functions-cloud-backup?tabs=python). 

## Setup & Demo Flow

This gives a short, high-level overview of how this repo may be used.

![Overview](overview.jpg)

Todo, commands can be found in ```script.ps1```