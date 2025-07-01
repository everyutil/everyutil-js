[**SECURITY_UTILS**](../../README.md)

***

[SECURITY_UTILS](../../README.md) / [createEphemeralToken](../README.md) / isTokenExpired

# Function: isTokenExpired()

> **isTokenExpired**(`tokenCreatedAt`, `ttlMs`): `boolean`

Defined in: [createEphemeralToken.ts:25](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/security/createEphemeralToken.ts#L25)

Checks if a token is expired based on creation time and TTL.

## Parameters

### tokenCreatedAt

`number`

Token creation timestamp (ms).

### ttlMs

`number`

Time-to-live in ms.

## Returns

`boolean`

True if expired.

## Author

## Dailker
