---
page_type: sample
languages: java
products: azure
services: Eventhub
platforms: java
author: yaohaizh
---

## Getting Started with Eventhub - Manage Event Hub - in Java ##


  Azure Event Hub sample for managing event hub -
    - Create an event hub namespace
    - Create an event hub in the namespace with data capture enabled along with a consumer group and rule
    - List consumer groups in the event hub
    - Create a second event hub in the namespace
    - Create a consumer group in the second event hub
    - List consumer groups in the second event hub
    - Create an event hub namespace along with event hub.
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/eventhub-java-manage-event-hub.git

    cd eventhub-java-manage-event-hub

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.