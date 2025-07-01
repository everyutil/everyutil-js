[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [index](../README.md) / watchFileWithDebounce

# Function: watchFileWithDebounce()

> **watchFileWithDebounce**(`path`, `debounceMs`, `callback`): `void`

Defined in: [fs/watchFileWithDebounce.ts:9](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/fs/watchFileWithDebounce.ts#L9)

Watches a file but debounces rapid changes, calling the callback only once after inactivity.

## Parameters

### path

`string`

File path.

### debounceMs

`number`

Debounce time in ms.

### callback

() => `void`

Callback function.

## Returns

`void`

## Author

## Dailker
