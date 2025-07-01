[**SECURITY_UTILS**](../../README.md)

***

[SECURITY_UTILS](../../README.md) / [validateReferer](../README.md) / validateReferer

# Function: validateReferer()

> **validateReferer**(`origin`, `whitelist`): `boolean`

Defined in: [validateReferer.ts:9](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/security/validateReferer.ts#L9)

Validates referer/origin against a whitelist for CSRF protection.

## Parameters

### origin

`string`

The referer/origin header.

### whitelist

`string`[]

Allowed origins.

## Returns

`boolean`

True if valid.

## Author

## Dailker
