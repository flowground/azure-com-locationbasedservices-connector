# ![LOGO](logo.png) Azure Location Based Services Resource Provider **flow**ground Connector

## Description

A generated **flow**ground connector for the Azure Location Based Services Resource Provider API (version 2017-01-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/locationbasedservices/2017-01-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:17+03:00

## API Description

Resource Provider

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### List operations available for the Location Based Services Resource Provider

#### Input Parameters
* `api-version` - _required_ - Client Api Version.

### Get all Location Based Services Accounts in a Subscription

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Moves Location Based Services Accounts from one ResourceGroup (or Subscription) to another

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group that contains Location Based Services Account to move.

### Get all Location Based Services Accounts in a Resource Group

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure Resource Group.

### Delete a Location Based Services Account

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure Resource Group.
* `accountName` - _required_ - The name of the Location Based Services Account.

### Get a Location Based Services Account

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure Resource Group.
* `accountName` - _required_ - The name of the Location Based Services Account.

### Updates a Location Based Services Account. Only a subset of the parameters may be updated after creation, such as Sku and Tags.

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure Resource Group.
* `accountName` - _required_ - The name of the Location Based Services Account.

### Create or update a Location Based Services Account. A Location Based Services Account holds the keys which allow access to the Location Based Services REST APIs.

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure Resource Group.
* `accountName` - _required_ - The name of the Location Based Services Account.

### Get the keys to use with the Location Based Services APIs. A key is used to authenticate and authorize access to the Location Based Services REST APIs. Only one key is needed at a time; two are given to provide seamless key regeneration.

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure Resource Group.
* `accountName` - _required_ - The name of the Location Based Services Account.

### Regenerate either the primary or secondary key for use with the Location Based Services APIs. The old key will stop working immediately.

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure Resource Group.
* `accountName` - _required_ - The name of the Location Based Services Account.

## License

**flow**ground :- Telekom iPaaS / azure-com-locationbasedservices-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
