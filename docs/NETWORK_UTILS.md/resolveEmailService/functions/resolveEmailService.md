[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [resolveEmailService](../README.md) / resolveEmailService

# Function: resolveEmailService()

> **resolveEmailService**(`domain`): `null` \| `string`

Defined in: [network/resolveEmailService.ts:10](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/resolveEmailService.ts#L10)

Maps an email domain to a common SMTP provider.

Example: resolveEmailService('gmail.com') → 'smtp.gmail.com'

## Parameters

### domain

`string`

Email domain.

## Returns

`null` \| `string`

SMTP host or null if unknown.

## Author

## Dailker
