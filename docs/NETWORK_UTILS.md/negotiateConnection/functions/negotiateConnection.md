[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [negotiateConnection](../README.md) / negotiateConnection

# Function: negotiateConnection()

> **negotiateConnection**(`pc`, `remoteDesc`): `Promise`\<`RTCSessionDescriptionInit`\>

Defined in: [network/negotiateConnection.ts:11](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/negotiateConnection.ts#L11)

Automates offer/answer negotiation for a peer connection.

Example: await negotiateConnection(pc, remoteDesc)

## Parameters

### pc

`RTCPeerConnection`

The peer connection.

### remoteDesc

`RTCSessionDescriptionInit`

Remote offer/answer.

## Returns

`Promise`\<`RTCSessionDescriptionInit`\>

Local description.

## Author

## Dailker
