[**COMPRESSION_UTILS**](../../README.md)

***

[COMPRESSION_UTILS](../../README.md) / [decompressStream](../README.md) / decompressStream

# Function: decompressStream()

> **decompressStream**(`inputStream`, `outputStream`, `options?`): `Promise`\<`void`\>

Defined in: [decompressStream.ts:11](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/compression/decompressStream.ts#L11)

Decompresses a compressed stream using the specified method and writes the decompressed data to output.
Supports gzip, deflate, brotli.

## Parameters

### inputStream

`Readable`

Input stream.

### outputStream

`Writable`

Output stream.

### options?

#### method?

`"gzip"` \| `"deflate"` \| `"brotli"`

#### password?

`string`

## Returns

`Promise`\<`void`\>

## Author

## Dailker
