# ![LOGO](logo.png) CognitiveServicesManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the CognitiveServicesManagementClient API (version 2017-04-18).

Generated from: https://api.apis.guru/v2/specs/azure.com/cognitiveservices/2017-04-18/swagger.json<br/>
Generated at: 2019-05-07T17:37:48+03:00

## API Description

Cognitive Services Management Client

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all the available Cognitive Services account operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - Version of the API to be used with the client request. Current version is 2017-04-18

### Returns all the resources of a particular type belonging to a subscription.

*Tags:* `CognitiveServicesAccounts`

#### Input Parameters
* `api-version` - _required_ - Version of the API to be used with the client request. Current version is 2017-04-18
* `subscriptionId` - _required_ - Azure Subscription ID.

### Check available SKUs.

*Tags:* `CognitiveServicesAccounts`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `api-version` - _required_ - Version of the API to be used with the client request. Current version is 2017-04-18
* `location` - _required_ - Resource location.

### Gets the list of Microsoft.CognitiveServices SKUs available for your Subscription.

*Tags:* `Skus` `CognitiveServicesAccounts`

#### Input Parameters
* `api-version` - _required_ - Version of the API to be used with the client request. Current version is 2017-04-18
* `subscriptionId` - _required_ - Azure Subscription ID.

### Returns all the resources of a particular type belonging to a resource group

*Tags:* `CognitiveServicesAccounts`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription.
* `subscriptionId` - _required_ - Azure Subscription ID.
* `api-version` - _required_ - Version of the API to be used with the client request. Current version is 2017-04-18

### Deletes a Cognitive Services account from the resource group.

*Tags:* `CognitiveServicesAccounts`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription.
* `accountName` - _required_ - The name of Cognitive Services account.
* `api-version` - _required_ - Version of the API to be used with the client request. Current version is 2017-04-18
* `subscriptionId` - _required_ - Azure Subscription ID.

### Returns a Cognitive Services account specified by the parameters.

*Tags:* `CognitiveServicesAccounts`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription.
* `accountName` - _required_ - The name of Cognitive Services account.
* `api-version` - _required_ - Version of the API to be used with the client request. Current version is 2017-04-18
* `subscriptionId` - _required_ - Azure Subscription ID.

### Updates a Cognitive Services account

*Tags:* `CognitiveServicesAccounts`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription.
* `accountName` - _required_ - The name of Cognitive Services account.
* `api-version` - _required_ - Version of the API to be used with the client request. Current version is 2017-04-18
* `subscriptionId` - _required_ - Azure Subscription ID.

### Create Cognitive Services Account. Accounts is a resource group wide resource type. It holds the keys for developer to access intelligent APIs. It's also the resource type for billing.

*Tags:* `CognitiveServicesAccounts`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription.
* `accountName` - _required_ - The name of Cognitive Services account.
* `api-version` - _required_ - Version of the API to be used with the client request. Current version is 2017-04-18
* `subscriptionId` - _required_ - Azure Subscription ID.

### Lists the account keys for the specified Cognitive Services account.

*Tags:* `CognitiveServicesAccounts`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription.
* `accountName` - _required_ - The name of Cognitive Services account.
* `api-version` - _required_ - Version of the API to be used with the client request. Current version is 2017-04-18
* `subscriptionId` - _required_ - Azure Subscription ID.

### Regenerates the specified account key for the specified Cognitive Services account.

*Tags:* `CognitiveServicesAccounts`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription.
* `accountName` - _required_ - The name of Cognitive Services account.
* `api-version` - _required_ - Version of the API to be used with the client request. Current version is 2017-04-18
* `subscriptionId` - _required_ - Azure Subscription ID.

### List available SKUs for the requested Cognitive Services account

*Tags:* `CognitiveServicesAccounts`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription.
* `accountName` - _required_ - The name of Cognitive Services account.
* `api-version` - _required_ - Version of the API to be used with the client request. Current version is 2017-04-18
* `subscriptionId` - _required_ - Azure Subscription ID.

### Get usages for the requested Cognitive Services account

*Tags:* `CognitiveServicesAccounts`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription.
* `accountName` - _required_ - The name of Cognitive Services account.
* `api-version` - _required_ - Version of the API to be used with the client request. Current version is 2017-04-18
* `subscriptionId` - _required_ - Azure Subscription ID.
* `$filter` - _optional_ - An OData filter expression that describes a subset of usages to return. The supported parameter is name.value (name of the metric, can have an or of multiple names).

## License

**flow**ground :- Telekom iPaaS / azure-com-cognitiveservices-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
