[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [retryFetchWithBackoff](../README.md) / retryFetchWithBackoff

# Function: retryFetchWithBackoff()

> **retryFetchWithBackoff**(`fn`, `retries`, `baseDelay`, `factor`): `Promise`\<`any`\>

Defined in: [network/retryFetchWithBackoff.ts:13](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/retryFetchWithBackoff.ts#L13)

Retries a fetch-like function with exponential backoff.

Example: retryFetchWithBackoff(fn, 5, 100, 2)

## Parameters

### fn

() => `Promise`\<`any`\>

Fetch function.

### retries

`number`

Number of retries.

### baseDelay

`number` = `100`

Initial delay in ms.

### factor

`number` = `2`

Backoff multiplier.

## Returns

`Promise`\<`any`\>

The fetch result.

## Author

## Dailker
