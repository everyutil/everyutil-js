[**STRING_UTILS**](../../README.md)

***

[STRING_UTILS](../../README.md) / [extractKeywords](../README.md) / extractKeywords

# Function: extractKeywords()

> **extractKeywords**(`str`, `stopwords?`): `string`[]

Defined in: [extractKeywords.ts:11](https://github.com/dailker/everyutil-js/blob/7799f3f003cb23f425be3f1c83c38483e2648188/src/string/extractKeywords.ts#L11)

Extracts keywords from a string, removing stopwords and punctuation.

Example: extractKeywords("The cat sat on the mat.", ["the", "on"]) → ['cat', 'sat', 'mat']

## Parameters

### str

`string`

The input string.

### stopwords?

`string`[] = `[]`

Words to exclude from the result.

## Returns

`string`[]

Array of keywords.

## Author

## Dailker
