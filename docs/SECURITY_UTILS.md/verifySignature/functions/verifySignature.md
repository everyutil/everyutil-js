[**SECURITY_UTILS**](../../README.md)

***

[SECURITY_UTILS](../../README.md) / [verifySignature](../README.md) / verifySignature

# Function: verifySignature()

> **verifySignature**(`data`, `signature`, `publicKey`): `boolean`

Defined in: [verifySignature.ts:10](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/security/verifySignature.ts#L10)

Verifies a digital signature using a public RSA key (SHA256).

## Parameters

### data

`string`

The data that was signed.

### signature

`string`

The base64-encoded signature.

### publicKey

`string`

The public key (PEM format).

## Returns

`boolean`

True if valid, false otherwise.

## Author

## Dailker
