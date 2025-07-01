[**COMPRESSION_UTILS**](../../README.md)

***

[COMPRESSION_UTILS](../../README.md) / [compressToZip](../README.md) / compressToZip

# Function: compressToZip()

> **compressToZip**(`files`, `zipPath`, `options?`): `Promise`\<`void`\>

Defined in: [compressToZip.ts:11](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/compression/compressToZip.ts#L11)

Compresses multiple files into a ZIP archive at the specified destination.
Note: Password protection is not supported by adm-zip (option is ignored).

## Parameters

### files

`string`[]

Files to compress.

### zipPath

`string`

Destination ZIP path.

### options?

#### compressionLevel?

`number`

#### encrypt?

`boolean`

#### password?

`string`

## Returns

`Promise`\<`void`\>

## Author

## Dailker
