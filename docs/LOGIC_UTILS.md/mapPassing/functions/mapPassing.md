[**LOGIC_UTILS**](../../README.md)

***

[LOGIC_UTILS](../../README.md) / [mapPassing](../README.md) / mapPassing

# Function: mapPassing()

> **mapPassing**\<`T`, `R`\>(`items`, `predicate`, `transform`): `R`[]

Defined in: [mapPassing.ts:9](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/logic/mapPassing.ts#L9)

Applies transform only to passing items.

## Type Parameters

### T

`T`

### R

`R`

## Parameters

### items

`T`[]

The array of items to filter and transform.

### predicate

(`x`) => `boolean`

The predicate function to determine which items pass.

### transform

(`x`) => `R`

The transformation function to apply to passing items.

## Returns

`R`[]

The array of transformed items that passed the predicate.

## Author

## Dailker
