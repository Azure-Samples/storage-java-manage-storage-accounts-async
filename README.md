---
page_type: sample
languages:
- java
products:
- azure
extensions:
- services: Storage
- platforms: java
---

# Getting Started with Storage - Manage Storage Account Async - in Java #


  Azure Storage sample for managing storage accounts -
   - Create two storage account
   - List storage accounts and regenerate storage account access keys
   - Delete both storage account.
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/storage-java-manage-storage-accounts-async.git

    cd storage-java-manage-storage-accounts-async

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.