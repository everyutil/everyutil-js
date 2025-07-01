[**FS_UTILS**](../../README.md)

***

[FS_UTILS](../../README.md) / [atomicWriteFile](../README.md) / atomicWriteFile

# Function: atomicWriteFile()

> **atomicWriteFile**(`path`, `data`, `options?`): `Promise`\<`void`\>

Defined in: [atomicWriteFile.ts:10](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/fs/atomicWriteFile.ts#L10)

Writes data to a file atomically to avoid partial writes (writes to a temp file then renames).

## Parameters

### path

`string`

File path.

### data

Data to write.

`string` | `Buffer`

### options?

#### encoding?

`string`

## Returns

`Promise`\<`void`\>

## Author

## Dailker
