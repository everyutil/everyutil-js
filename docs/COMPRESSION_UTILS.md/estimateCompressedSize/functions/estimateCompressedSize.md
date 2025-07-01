[**COMPRESSION_UTILS**](../../README.md)

***

[COMPRESSION_UTILS](../../README.md) / [estimateCompressedSize](../README.md) / estimateCompressedSize

# Function: estimateCompressedSize()

> **estimateCompressedSize**(`filePath`, `options?`): `Promise`\<`number`\>

Defined in: [estimateCompressedSize.ts:10](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/compression/estimateCompressedSize.ts#L10)

Estimates the size of a file once compressed without creating the full compressed file.
Allows selection of compression method and level.

## Parameters

### filePath

`string`

Path to the file.

### options?

#### level?

`number`

#### method?

`"gzip"` \| `"deflate"`

## Returns

`Promise`\<`number`\>

Estimated compressed size in bytes.

## Author

## Dailker
