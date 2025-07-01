[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [fetchWithAbort](../README.md) / fetchWithAbort

# Function: fetchWithAbort()

> **fetchWithAbort**(`url`, `options?`, `timeoutMs?`, `signal?`): `Promise`\<`Response`\>

Defined in: [network/fetchWithAbort.ts:11](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/fetchWithAbort.ts#L11)

Fetch with abort support (auto-cancels on timeout or event).

## Parameters

### url

`string`

The request URL.

### options?

`RequestInit` = `{}`

Fetch options.

### timeoutMs?

`number`

Timeout in ms (optional).

### signal?

`AbortSignal`

Optional external abort signal.

## Returns

`Promise`\<`Response`\>

The fetch response.

## Author

## Dailker
