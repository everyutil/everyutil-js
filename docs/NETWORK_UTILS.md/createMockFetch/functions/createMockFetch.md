[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [createMockFetch](../README.md) / createMockFetch

# Function: createMockFetch()

> **createMockFetch**(`responseMap`): (`input`, `init?`) => `Promise`\<`Response`\>

Defined in: [network/createMockFetch.ts:10](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/createMockFetch.ts#L10)

Creates a mock fetch implementation from a route-to-response mapping.

Example: const mock = createMockFetch({ '/api': { status: 200, body: 'ok' } })

## Parameters

### responseMap

`Record`\<`string`, \{ `body?`: `any`; `headers?`: `Record`\<`string`, `string`\>; `status?`: `number`; \}\>

Route to response mapping.

## Returns

Mock fetch function.

> (`input`, `init?`): `Promise`\<`Response`\>

### Parameters

#### input

`RequestInfo`

#### init?

`RequestInit`

### Returns

`Promise`\<`Response`\>

## Author

## Dailker
