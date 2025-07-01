[**NETWORK_UTILS**](../../README.md)

***

[NETWORK_UTILS](../../README.md) / [index](../README.md) / FileDiff

# Interface: FileDiff

Defined in: [fs/FileDiff.ts:5](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/fs/FileDiff.ts#L5)

Represents a difference between two files or directories.

## Author

## Dailker

## Properties

### destStat?

> `optional` **destStat**: `Stats`

Defined in: [fs/FileDiff.ts:9](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/fs/FileDiff.ts#L9)

***

### path

> **path**: `string`

Defined in: [fs/FileDiff.ts:6](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/fs/FileDiff.ts#L6)

***

### srcStat?

> `optional` **srcStat**: `Stats`

Defined in: [fs/FileDiff.ts:8](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/fs/FileDiff.ts#L8)

***

### type

> **type**: `"modified"` \| `"added"` \| `"removed"` \| `"conflict"`

Defined in: [fs/FileDiff.ts:7](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/fs/FileDiff.ts#L7)
