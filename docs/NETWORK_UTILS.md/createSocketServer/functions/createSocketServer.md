[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [createSocketServer](../README.md) / createSocketServer

# Function: createSocketServer()

> **createSocketServer**(`options`): `Promise`\<`any`\>

Defined in: [network/createSocketServer.ts:10](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/createSocketServer.ts#L10)

Bootstraps a TCP server with event handlers (Node.js only).

Example: createSocketServer({ port, onConnection })

## Parameters

### options

Server options and handlers.

#### onConnection?

(`socket`) => `void`

#### onError?

(...`args`) => `void`

#### port

`number`

## Returns

`Promise`\<`any`\>

The server instance.

## Author

## Dailker
