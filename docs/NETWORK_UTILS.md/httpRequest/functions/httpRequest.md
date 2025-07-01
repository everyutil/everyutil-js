[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [httpRequest](../README.md) / httpRequest

# Function: httpRequest()

> **httpRequest**(`options`, `body?`): `Promise`\<\{ `body`: `Buffer`; `headers`: `any`; `status`: `number`; \}\>

Defined in: [network/httpRequest.ts:11](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/httpRequest.ts#L11)

Simple HTTP request wrapper using Node's native modules.

Example: httpRequest({ hostname, port, path, method })

## Parameters

### options

`any`

HTTP request options.

### body?

Optional request body.

`string` | `Buffer`

## Returns

`Promise`\<\{ `body`: `Buffer`; `headers`: `any`; `status`: `number`; \}\>

Response object.

## Author

## Dailker
