[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [index](../README.md) / mergeArchives

# Function: mergeArchives()

> **mergeArchives**(`parts`, `outputFilePath`, `options?`): `Promise`\<`void`\>

Defined in: [compression/mergeArchives.ts:11](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/compression/mergeArchives.ts#L11)

Merges previously split archive parts back into a single compressed archive.
Supports optional decryption with password.

## Parameters

### parts

`string`[]

Array of part file paths.

### outputFilePath

`string`

Output file path.

### options?

#### decrypt?

`boolean`

#### password?

`string`

## Returns

`Promise`\<`void`\>

## Author

## Dailker
