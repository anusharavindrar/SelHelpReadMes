# Restore a bot

It is not possible to restore a bot if accidentally deleted the resources on Azure.

Notes:

* Botframework does not have the ability to recover a bot but it maybe theoritically possible to restore from Cosmos backups assuming the bot wasn't updated since the backup and someone hasn't claimed that botId. BotFramework doesn't directly manage the backups, so one needs to get in touch with Azure an then maually pick through the backup turning out to be an expensive operation in terms of someone's time.

* The usual Azure response is once you delete an Azure resource, you must contact support to see if they can get it back. Some services say if you contact them within 30 days they can restore a resource, others say once you delete it, it is gone.

* If a customer deletes a file from the Azure Bot Service, they should be able to restore it if they have it backed up. KUDU has file upload so that should work. If a customer needs to restore or create a new Azure Bot Service and they have the code, that is just a matter of deploying the code into the resource. 
