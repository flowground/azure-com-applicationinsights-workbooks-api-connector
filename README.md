# ![LOGO](logo.png) ApplicationInsightsManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ApplicationInsightsManagementClient API (version 2018-06-17-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/applicationinsights-workbooks_API/2018-06-17-preview/swagger.json<br/>
Generated at: 2019-05-07T17:37:16+03:00

## API Description

Azure Application Insights workbook type.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Get all Workbooks defined within a specified resource group and category.

#### Input Parameters
* `subscriptionId` - _required_ - The Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `category` - _required_ - Category of workbook to return.
    Possible values: workbook, TSG, performance, retention.
* `tags` - _optional_ - Tags presents on each workbook returned.
* `sourceId` - _required_ - Azure Resource Id that will fetch all related workbooks.
* `canFetchContent` - _optional_ - Flag indicating whether or not to return the full content for each applicable workbook. If false, only return summary content for workbooks.
* `api-version` - _required_ - Client Api Version.

### Delete a workbook.

#### Input Parameters
* `subscriptionId` - _required_ - The Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `resourceName` - _required_ - The name of the Application Insights component resource.
* `api-version` - _required_ - Client Api Version.

### Get a single workbook by its resourceName.

#### Input Parameters
* `subscriptionId` - _required_ - The Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `resourceName` - _required_ - The name of the Application Insights component resource.
* `api-version` - _required_ - Client Api Version.

### Updates a workbook that has already been added.

#### Input Parameters
* `subscriptionId` - _required_ - The Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `resourceName` - _required_ - The name of the Application Insights component resource.
* `sourceId` - _required_ - Azure Resource Id that will fetch all related workbooks.
* `api-version` - _required_ - Client Api Version.

### Create a new workbook.

#### Input Parameters
* `subscriptionId` - _required_ - The Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `resourceName` - _required_ - The name of the Application Insights component resource.
* `sourceId` - _required_ - Azure Resource Id that will fetch all related workbooks.
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-applicationinsights-workbooks-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
