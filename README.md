# ![LOGO](logo.png) Azure SQL Database **flow**ground Connector

## Description

A generated **flow**ground connector for the Azure SQL Database API (version 2014-04-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/sql-sql.core/2014-04-01/swagger.json<br/>
Generated at: 2019-05-07T17:39:12+03:00

## API Description

Provides create, read, update and delete functionality for Azure SQL Database resources including recommendations and operations.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Returns service tier advisors for specified database.

*Tags:* `ServiceTierAdvisors`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of database.

### Gets a service tier advisor.

*Tags:* `ServiceTierAdvisors`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of database.
* `serviceTierAdvisorName` - _required_ - The name of service tier advisor.

### Gets a database's transparent data encryption configuration.

*Tags:* `TransparentDataEncryption`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database for which the transparent data encryption applies.
* `transparentDataEncryptionName` - _required_ - The name of the transparent data encryption configuration.
    Possible values: current.

### Creates or updates a database's transparent data encryption configuration.

*Tags:* `TransparentDataEncryption`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database for which setting the transparent data encryption applies.
* `transparentDataEncryptionName` - _required_ - The name of the transparent data encryption configuration.
    Possible values: current.

### Returns a database's transparent data encryption operation result.

*Tags:* `TransparentDataEncryption`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database for which the transparent data encryption applies.
* `transparentDataEncryptionName` - _required_ - The name of the transparent data encryption configuration.
    Possible values: current.

### Returns elastic pool activities.

*Tags:* `ElasticPools`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `elasticPoolName` - _required_ - The name of the elastic pool for which to get the current activity.

### Returns activity on databases inside of an elastic pool.

*Tags:* `ElasticPools`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `elasticPoolName` - _required_ - The name of the elastic pool.

## License

**flow**ground :- Telekom iPaaS / azure-com-sql-sql-core-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
