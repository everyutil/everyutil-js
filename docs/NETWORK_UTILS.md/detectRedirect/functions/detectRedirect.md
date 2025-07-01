[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [detectRedirect](../README.md) / detectRedirect

# Function: detectRedirect()

> **detectRedirect**(`url`, `options?`, `maxRedirects?`): `Promise`\<`Response`\>

Defined in: [network/detectRedirect.ts:10](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/detectRedirect.ts#L10)

Detects and follows/limits redirects manually.

## Parameters

### url

`string`

The request URL.

### options?

`RequestInit`

Fetch options.

### maxRedirects?

`number` = `5`

Maximum redirects to follow.

## Returns

`Promise`\<`Response`\>

The final response.

## Author

## Dailker
