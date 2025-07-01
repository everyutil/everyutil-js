[**COMPRESSION_UTILS**](../../README.md)

***

[COMPRESSION_UTILS](../../README.md) / [compressStream](../README.md) / compressStream

# Function: compressStream()

> **compressStream**(`inputStream`, `outputStream`, `options?`): `Promise`\<`void`\>

Defined in: [compressStream.ts:11](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/compression/compressStream.ts#L11)

Compresses a readable stream and writes the compressed data to a writable stream.
Supports gzip, deflate, brotli.

## Parameters

### inputStream

`Readable`

Input stream.

### outputStream

`Writable`

Output stream.

### options?

#### level?

`number`

#### method?

`"gzip"` \| `"deflate"` \| `"brotli"`

#### password?

`string`

## Returns

`Promise`\<`void`\>

## Author

## Dailker
