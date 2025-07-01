[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [fetchWithRetry](../README.md) / fetchWithRetry

# Function: fetchWithRetry()

> **fetchWithRetry**(`url`, `options`, `retryCount`): `Promise`\<`Response`\>

Defined in: [network/fetchWithRetry.ts:8](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/fetchWithRetry.ts#L8)

Fetch wrapper that retries on failure.

## Parameters

### url

`string`

The URL to fetch.

### options

`RequestInit` = `{}`

Fetch options.

### retryCount

`number` = `3`

Number of retries.

## Returns

`Promise`\<`Response`\>

The fetch response.
