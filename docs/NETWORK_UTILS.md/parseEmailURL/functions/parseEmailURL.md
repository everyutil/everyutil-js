[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [parseEmailURL](../README.md) / parseEmailURL

# Function: parseEmailURL()

> **parseEmailURL**(`url`): `object`

Defined in: [network/parseEmailURL.ts:10](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/parseEmailURL.ts#L10)

Parses an SMTP-style email URL (smtp://user:pass@host:port).

Example: parseEmailURL('smtp://user:pass@host:25')

## Parameters

### url

`string`

The email URL.

## Returns

`object`

Parsed info.

### host

> **host**: `string`

### password?

> `optional` **password**: `string`

### port?

> `optional` **port**: `string`

### protocol

> **protocol**: `string`

### username?

> `optional` **username**: `string`

## Author

## Dailker
