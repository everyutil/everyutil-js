[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [getURLHashParams](../README.md) / getURLHashParams

# Function: getURLHashParams()

> **getURLHashParams**(`url`): `Record`\<`string`, `string`\>

Defined in: [network/getURLHashParams.ts:10](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/getURLHashParams.ts#L10)

Parses the hash fragment of a URL as key-value pairs.

Example: getURLHashParams("/a#foo=1&bar=2") → { foo: "1", bar: "2" }

## Parameters

### url

`string`

The URL.

## Returns

`Record`\<`string`, `string`\>

Hash params.

## Author

## Dailker
