[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [parseSetCookie](../README.md) / parseSetCookie

# Function: parseSetCookie()

> **parseSetCookie**(`header`): `object`[]

Defined in: [network/parseSetCookie.ts:10](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/parseSetCookie.ts#L10)

Parses multiple Set-Cookie headers from a string or array.

Example: parseSetCookie("a=1; Path=/, b=2; Path=/") → [{ name: 'a', value: '1', ... }, ...]

## Parameters

### header

Set-Cookie header(s).

`string` | `string`[]

## Returns

`object`[]

Parsed cookies.

## Author

## Dailker
