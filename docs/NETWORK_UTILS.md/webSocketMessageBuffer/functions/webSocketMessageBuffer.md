[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [webSocketMessageBuffer](../README.md) / webSocketMessageBuffer

# Function: webSocketMessageBuffer()

> **webSocketMessageBuffer**(`ws`, `bufferSize`): `string`[]

Defined in: [network/webSocketMessageBuffer.ts:11](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/webSocketMessageBuffer.ts#L11)

Buffers the last N messages from a WebSocket.

Example: webSocketMessageBuffer(ws, 10)

## Parameters

### ws

`WebSocket`

The WebSocket instance.

### bufferSize

`number`

Number of messages to retain.

## Returns

`string`[]

The message buffer (most recent last).

## Author

## Dailker
