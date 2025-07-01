[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [normalizeHeaders](../README.md) / normalizeHeaders

# Function: normalizeHeaders()

> **normalizeHeaders**(`headers`): `Record`\<`string`, `string`\>

Defined in: [network/normalizeHeaders.ts:10](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/normalizeHeaders.ts#L10)

Normalizes headers to lowercase keys (plain object only).

Example: normalizeHeaders({ 'X-Foo': 'bar' }) → { 'x-foo': 'bar' }

## Parameters

### headers

`Record`\<`string`, `string`\>

Headers object.

## Returns

`Record`\<`string`, `string`\>

Normalized headers.

## Author

## Dailker
