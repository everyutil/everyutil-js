[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [fetchWithProgress](../README.md) / fetchWithProgress

# Function: fetchWithProgress()

> **fetchWithProgress**(`url`, `onProgress`): `Promise`\<`Blob`\>

Defined in: [network/fetchWithProgress.ts:11](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/fetchWithProgress.ts#L11)

Fetches a resource and tracks download progress. Uses XHR for progress events.

Example: fetchWithProgress("/file", progress => ...)

## Parameters

### url

`string`

The URL to fetch.

### onProgress

(`progress`) => `void`

Progress callback (0-1).

## Returns

`Promise`\<`Blob`\>

The downloaded Blob.

## Author

## Dailker
