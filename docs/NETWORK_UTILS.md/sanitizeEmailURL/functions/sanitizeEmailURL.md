[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [sanitizeEmailURL](../README.md) / sanitizeEmailURL

# Function: sanitizeEmailURL()

> **sanitizeEmailURL**(`url`): `string`

Defined in: [network/sanitizeEmailURL.ts:10](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/sanitizeEmailURL.ts#L10)

Strips credentials or masks sensitive data in an email URL.

Example: sanitizeEmailURL('smtp://user:pass@host:25') → 'smtp://***:***@host:25'

## Parameters

### url

`string`

The email URL.

## Returns

`string`

The sanitized URL.

## Author

## Dailker
