[**COLOR_UTILS**](../../README.md)

***

[COLOR_UTILS](../../README.md) / [parseCssVariables](../README.md) / parseCssVariables

# Function: parseCssVariables()

> **parseCssVariables**(`styleString`): `Record`\<`string`, `string`\>

Defined in: [parseCssVariables.ts:10](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/color/parseCssVariables.ts#L10)

Parses CSS variables and returns color values.

Example: parseCssVariables(":root { --main: #336699; }") → { '--main': '#336699' }

## Parameters

### styleString

`string`

CSS style string.

## Returns

`Record`\<`string`, `string`\>

Map of variable names to color values.

## Author

## Dailker
