# ![LOGO](logo.png) RecoveryServicesBackupClient **flow**ground Connector

## Description

A generated **flow**ground connector for the RecoveryServicesBackupClient API (version 2016-12-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/recoveryservices-backup/2016-12-01/swagger.json<br/>
Generated at: 2019-06-11T18:14:09+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Fetches vault config.

*Tags:* `BackupVaultConfigs`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription Id.
* `api-version` - _required_ - Client Api Version.
* `resourceGroupName` - _required_ - The name of the resource group where the recovery services vault is present.
* `vaultName` - _required_ - The name of the recovery services vault.

### Updates vault config model type.

*Tags:* `BackupVaultConfigs`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription Id.
* `api-version` - _required_ - Client Api Version.
* `resourceGroupName` - _required_ - The name of the resource group where the recovery services vault is present.
* `vaultName` - _required_ - The name of the recovery services vault.

### Fetches resource storage config.

*Tags:* `BackupStorageConfigs`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription Id.
* `api-version` - _required_ - Client Api Version.
* `resourceGroupName` - _required_ - The name of the resource group where the recovery services vault is present.
* `vaultName` - _required_ - The name of the recovery services vault.

### Updates vault storage model type.

*Tags:* `BackupStorageConfigs`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription Id.
* `api-version` - _required_ - Client Api Version.
* `resourceGroupName` - _required_ - The name of the resource group where the recovery services vault is present.
* `vaultName` - _required_ - The name of the recovery services vault.

## License

**flow**ground :- Telekom iPaaS / azure-com-recoveryservices-backup-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
