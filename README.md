# ![LOGO](logo.png) elmah.io **flow**ground Connector

## Description

A generated **flow**ground connector for the elmah.io API (version v3).

Generated from: https://api.apis.guru/v2/specs/elmah.io/v3/swagger.json<br/>
Generated at: 2019-05-07T17:40:20+03:00

## API Description



## Authorization

Supported authorization schemes:
- API Key
## Actions

### Fetch a list of deployments.

*Tags:* `Deployments`

### Create a new deployment.

*Tags:* `Deployments`

### Delete a deployment by its ID.

> This endpoint doesn't clear the version number of messages already annotated with this deployment version.

*Tags:* `Deployments`

#### Input Parameters
* `id` - _required_ - The ID of the deployment to delete.

### Fetch a deployment by its ID.

*Tags:* `Deployments`

#### Input Parameters
* `id` - _required_ - The ID of the deployment to fetch.

### Fetch a list of logs.

*Tags:* `Logs`

### Create a new log.

*Tags:* `Logs`

### Fetch a log by its ID.

*Tags:* `Logs`

#### Input Parameters
* `id` - _required_ - The ID of the log to fetch.

### Deletes a list of messages by logid and query.

*Tags:* `Messages`

#### Input Parameters
* `logId` - _required_ - The ID of the log containing the message.

### Fetch messages from a log.

*Tags:* `Messages`

#### Input Parameters
* `logId` - _required_ - The ID of the log containing the messages.
* `pageIndex` - _optional_ - The page number of the result.
* `pageSize` - _optional_ - The number of messages to load (max 100) or 15 if not set.
* `query` - _optional_ - A full-text or Lucene query to limit the messages by.
* `from` - _optional_ - A start date and time to search from (not included).
* `to` - _optional_ - An end date and time to search to (not included).
* `includeHeaders` - _optional_ - Include headers like server variables and cookies in the result (slower).

### Create a new message.

*Tags:* `Messages`

#### Input Parameters
* `logId` - _required_ - The ID of the log which should contain the new message.

### Delete a message by its ID.

*Tags:* `Messages`

#### Input Parameters
* `id` - _required_ - The ID of the message to delete.
* `logId` - _required_ - The ID of the log containing the message.

### Fetch a message by its ID.

*Tags:* `Messages`

#### Input Parameters
* `id` - _required_ - The ID of the message to fetch.
* `logId` - _required_ - The ID of the log containing the message.

### Hide a message by its ID.

*Tags:* `Messages`

#### Input Parameters
* `id` - _required_ - The ID of the message to hide.
* `logId` - _required_ - The ID of the log containing the message.

## License

**flow**ground :- Telekom iPaaS / elmah-io-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
