[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [urlMatchesPattern](../README.md) / urlMatchesPattern

# Function: urlMatchesPattern()

> **urlMatchesPattern**(`url`, `pattern`): `boolean`

Defined in: [network/urlMatchesPattern.ts:11](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/network/urlMatchesPattern.ts#L11)

Checks if a URL matches a wildcard string or RegExp pattern.

Example: urlMatchesPattern("https://a.com/page", "https://*.com/*") → true

## Parameters

### url

`string`

The URL to test.

### pattern

Wildcard string ("*" allowed) or RegExp.

`string` | `RegExp`

## Returns

`boolean`

True if matches.

## Author

## Dailker
