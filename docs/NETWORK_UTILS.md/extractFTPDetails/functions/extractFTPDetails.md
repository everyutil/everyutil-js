[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [extractFTPDetails](../README.md) / extractFTPDetails

# Function: extractFTPDetails()

> **extractFTPDetails**(`url`): `object`

Defined in: [network/extractFTPDetails.ts:10](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/extractFTPDetails.ts#L10)

Parses an FTP URL (ftp://user:pass@host:port/path).

Example: extractFTPDetails('ftp://user:pass@host:21/path')

## Parameters

### url

`string`

The FTP URL.

## Returns

`object`

Parsed info.

### host

> **host**: `string`

### password?

> `optional` **password**: `string`

### path?

> `optional` **path**: `string`

### port?

> `optional` **port**: `string`

### protocol

> **protocol**: `string`

### username?

> `optional` **username**: `string`

## Author

## Dailker
