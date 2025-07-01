[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [getUserMediaSafe](../README.md) / getUserMediaSafe

# Function: getUserMediaSafe()

> **getUserMediaSafe**(`constraints`): `Promise`\<`null` \| `MediaStream`\>

Defined in: [network/getUserMediaSafe.ts:10](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/getUserMediaSafe.ts#L10)

Promisified, fallback-enabled getUserMedia.

Example: getUserMediaSafe({ video: true })

## Parameters

### constraints

`MediaStreamConstraints`

Media constraints.

## Returns

`Promise`\<`null` \| `MediaStream`\>

MediaStream or null if failed.

## Author

## Dailker
