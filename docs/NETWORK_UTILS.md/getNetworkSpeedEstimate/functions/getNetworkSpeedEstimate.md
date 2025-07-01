[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [getNetworkSpeedEstimate](../README.md) / getNetworkSpeedEstimate

# Function: getNetworkSpeedEstimate()

> **getNetworkSpeedEstimate**(): `Promise`\<`null` \| \{ `latencyMs`: `number`; `speedMbps`: `number`; \}\>

Defined in: [network/getNetworkSpeedEstimate.ts:9](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/getNetworkSpeedEstimate.ts#L9)

Estimates network speed by downloading a known asset and timing it.

Example: getNetworkSpeedEstimate() → { speedMbps: 10.5, latencyMs: 120 }

## Returns

`Promise`\<`null` \| \{ `latencyMs`: `number`; `speedMbps`: `number`; \}\>

Speed and latency or null if failed.

## Author

## Dailker
