[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [uploadFileWithProgress](../README.md) / uploadFileWithProgress

# Function: uploadFileWithProgress()

> **uploadFileWithProgress**(`file`, `url`, `onProgress`): `Promise`\<`Response`\>

Defined in: [network/uploadFileWithProgress.ts:12](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/uploadFileWithProgress.ts#L12)

Uploads a file to a URL with progress events.

Example: uploadFileWithProgress(file, url, p => ...)

## Parameters

### file

`File`

The file to upload.

### url

`string`

The upload URL.

### onProgress

(`progress`) => `void`

Progress callback (0-1).

## Returns

`Promise`\<`Response`\>

The fetch response.

## Author

## Dailker
