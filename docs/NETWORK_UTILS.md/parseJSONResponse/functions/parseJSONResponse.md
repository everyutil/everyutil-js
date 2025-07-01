[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [parseJSONResponse](../README.md) / parseJSONResponse

# Function: parseJSONResponse()

> **parseJSONResponse**\<`T`\>(`response`): `Promise`\<`null` \| `T`\>

Defined in: [network/parseJSONResponse.ts:6](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/parseJSONResponse.ts#L6)

Safely parses a JSON response, returning null on error.

## Type Parameters

### T

`T` = `any`

## Parameters

### response

`Response`

The fetch Response object.

## Returns

`Promise`\<`null` \| `T`\>

The parsed JSON or null.
