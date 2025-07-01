[**COMPRESSION_UTILS**](../../README.md)

***

[COMPRESSION_UTILS](../../README.md) / [splitArchive](../README.md) / splitArchive

# Function: splitArchive()

> **splitArchive**(`filePath`, `maxPartSizeBytes`, `options?`): `Promise`\<`string`[]\>

Defined in: [splitArchive.ts:11](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/compression/splitArchive.ts#L11)

Splits a large compressed file into smaller parts of a given size.
Supports optional encryption and password protection for each split part.

## Parameters

### filePath

`string`

Path to the archive.

### maxPartSizeBytes

`number`

Max part size in bytes.

### options?

#### encrypt?

`boolean`

#### password?

`string`

## Returns

`Promise`\<`string`[]\>

Array of part file paths.

## Author

## Dailker
