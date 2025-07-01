[**FS_UTILS**](../../README.md)

***

[FS_UTILS](../../README.md) / [secureDelete](../README.md) / secureDelete

# Function: secureDelete()

> **secureDelete**(`filePath`, `passes?`): `Promise`\<`void`\>

Defined in: [secureDelete.ts:9](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/fs/secureDelete.ts#L9)

Securely deletes a file by overwriting it with random data before removal.

## Parameters

### filePath

`string`

Path to the file.

### passes?

`number` = `3`

Number of overwrite passes.

## Returns

`Promise`\<`void`\>

Resolves when file is securely deleted.

## Author

## Dailker
