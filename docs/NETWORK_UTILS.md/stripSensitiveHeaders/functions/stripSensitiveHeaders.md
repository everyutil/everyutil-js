[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [stripSensitiveHeaders](../README.md) / stripSensitiveHeaders

# Function: stripSensitiveHeaders()

> **stripSensitiveHeaders**(`headers`): `Record`\<`string`, `string`\> \| `Headers`

Defined in: [network/stripSensitiveHeaders.ts:10](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/stripSensitiveHeaders.ts#L10)

Removes sensitive headers (cookies, auth) from outgoing headers.

Example: stripSensitiveHeaders(headers) → { ... }

## Parameters

### headers

Headers object or plain object.

`Record`\<`string`, `string`\> | `Headers`

## Returns

`Record`\<`string`, `string`\> \| `Headers`

Cleaned headers.

## Author

## Dailker
