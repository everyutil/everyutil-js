[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [mockServerResponse](../README.md) / mockServerResponse

# Function: mockServerResponse()

> **mockServerResponse**(`method`, `route`, `handler`): () => `void`

Defined in: [network/mockServerResponse.ts:12](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/mockServerResponse.ts#L12)

Mocks server response for a method/route with a handler function.

Example: mockServerResponse('GET', '/api', (req) => ...)

## Parameters

### method

`string`

HTTP method.

### route

`string`

Route to match.

### handler

(`req`) => `Response` \| `Promise`\<`Response`\>

Handler function.

## Returns

Restore function.

> (): `void`

### Returns

`void`

## Author

## Dailker
