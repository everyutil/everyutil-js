[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [retryFetch](../README.md) / retryFetch

# Function: retryFetch()

> **retryFetch**(`fn`, `retries`, `delay`): `Promise`\<`any`\>

Defined in: [network/retryFetch.ts:12](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/retryFetch.ts#L12)

Retries a fetch-like function with delay between attempts.

Example: retryFetch(() => fetch(url), 3, 1000)

## Parameters

### fn

() => `Promise`\<`any`\>

Fetch function.

### retries

`number`

Number of retries.

### delay

`number`

Delay in ms between retries.

## Returns

`Promise`\<`any`\>

The fetch result.

## Author

## Dailker
