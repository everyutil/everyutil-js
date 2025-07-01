[**SECURITY_UTILS**](../../README.md)

***

[SECURITY_UTILS](../../README.md) / [detectTokenReuse](../README.md) / detectTokenReuse

# Function: detectTokenReuse()

> **detectTokenReuse**(`jwt`, `historyCache`): `boolean`

Defined in: [detectTokenReuse.ts:9](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/security/detectTokenReuse.ts#L9)

Prevents JWT replay attacks by tracking token IDs.

## Parameters

### jwt

`string`

The JWT token.

### historyCache

`Set`\<`string`\>

Set of used token IDs.

## Returns

`boolean`

True if token is reused, false otherwise.

## Author

## Dailker
