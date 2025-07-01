[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [extractPathParams](../README.md) / extractPathParams

# Function: extractPathParams()

> **extractPathParams**(`url`, `routePattern`): `Record`\<`string`, `string`\>

Defined in: [network/extractPathParams.ts:11](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/extractPathParams.ts#L11)

Extracts path parameters from a URL given a route pattern.

Example: extractPathParams("/user/123", "/user/:id") → { id: "123" }

## Parameters

### url

`string`

The URL.

### routePattern

`string`

The route pattern.

## Returns

`Record`\<`string`, `string`\>

Extracted params.

## Author

## Dailker
