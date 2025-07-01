[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [tcpPing](../README.md) / tcpPing

# Function: tcpPing()

> **tcpPing**(`host`, `port`): `Promise`\<`null` \| `number`\>

Defined in: [network/tcpPing.ts:11](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/tcpPing.ts#L11)

Lightweight TCP ping alternative (Node.js only).

Example: tcpPing('localhost', 80)

## Parameters

### host

`string`

Hostname or IP.

### port

`number`

Port number.

## Returns

`Promise`\<`null` \| `number`\>

Latency in ms or null if failed.

## Author

## Dailker
