[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [createFakeServer](../README.md) / createFakeServer

# Function: createFakeServer()

> **createFakeServer**(`routes`): () => `void`

Defined in: [network/createFakeServer.ts:10](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/createFakeServer.ts#L10)

Creates a lightweight local mock server with route responses (browser only, Service Worker style).

Example: createFakeServer({ '/api': { status: 200, body: 'ok' } })

## Parameters

### routes

`Record`\<`string`, \{ `body?`: `any`; `headers?`: `Record`\<`string`, `string`\>; `status?`: `number`; \}\>

Route to response mapping.

## Returns

Function to unregister the fake server.

> (): `void`

### Returns

`void`

## Author

## Dailker
