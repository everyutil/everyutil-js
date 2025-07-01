[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [awaitICEGatheringComplete](../README.md) / awaitICEGatheringComplete

# Function: awaitICEGatheringComplete()

> **awaitICEGatheringComplete**(`pc`): `Promise`\<`void`\>

Defined in: [network/awaitICEGatheringComplete.ts:10](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/awaitICEGatheringComplete.ts#L10)

Awaits ICE candidate gathering to complete for a peer connection.

Example: await awaitICEGatheringComplete(pc)

## Parameters

### pc

`RTCPeerConnection`

The peer connection.

## Returns

`Promise`\<`void`\>

Resolves when ICE gathering is complete.

## Author

## Dailker
