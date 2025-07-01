[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [verifyHostAgainstCert](../README.md) / verifyHostAgainstCert

# Function: verifyHostAgainstCert()

> **verifyHostAgainstCert**(`host`, `cert`): `boolean`

Defined in: [network/verifyHostAgainstCert.ts:9](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/verifyHostAgainstCert.ts#L9)

Validates a host against the CN/SAN of an SSL certificate (Node.js only).

## Parameters

### host

`string`

The hostname to verify.

### cert

`any`

The certificate object.

## Returns

`boolean`

True if host matches cert, false otherwise.

## Author

## Dailker
