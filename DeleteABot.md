
# Delete a bot


## Delete a bot on the Azure Portal

1. Once you have created your bot and deployed it to [Azure](https://portal.azure.com) to make it accessible from anywhere, you will find the bot on the dashboard as well as in the Resource Group you have created it in. In case you are not able to locate the bot, you can also click on the 'All Resources' under the FAVORITES tab on the left. This will open up a list of all the resources under your directory. Using the 'Filter by name...' search tab, you can enter the name of your bot and it will display your bot. 
2. The typical options would be the Web App Bot, App Service and the Application Insights. You will need to select the option which is of the type 'Web App Bot'.
3. Once you click on the option, it will open up Web App Bot tab with all its contents.
4. On the right of the Search tab, you will find the 'Delete' option. Below this option is the 'Essentials' tab which contains all the details regarding the current Web App Bot (Resource Group, Subscription, Subscription ID, etc). You can double verify the bot's details before selecting the "Delete" option.
5. Once you click on the "Delete" option, it will display a pop-up asking if you are sure you want to delete the bot. Once you select "OK", it will delete the bot.
6. If you check on the Notifications tab, it will display "Successfully deleted bot" with the message that the particular bot ha been deleted.
7. Just to verify if the deletion was successful, you can try searching for the bot on the Search tab and it will show "No results were found" in the Services tab.

Note: If you have created a new Resource Group under which the particular bot is the only existing bot, then you can create the entire Resource Group.


## Delete a bot using Azure CLI

The Azure command-line interface (CLI) is Microsoft's cross-platform command-line experience for managing Azure resources. Refer to [this](https://docs.microsoft.com/en-us/cli/azure/bot?view=azure-cli-latest) documentation for more information about the use of Azure CLI.

To delete an existing bot, use the following command:

```
az bot delete --name
              --resource-group
              [--subscription]
```
The required parameters are :

### --name -n

The resource name of the bot. Bot name must be between 4 and 42 characters in length. Bot name can only have the following characters -, a - z, A - Z, 0 - 9, and _.

### --resource-group -g

Name of resource group. You can configure the default group using az configure --defaults group=<name>.

The optional parameters are:

### --subscription

Name or ID of subscription. You can configure the default subscription using az account set -s NAME_OR_ID.


