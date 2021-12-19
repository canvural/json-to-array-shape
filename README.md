# json-to-array-shape
Small tool to convert JSON into array shape. Supports generalizing types.

For example this input JSON:

```json
{
   "foo":[
      1,
      2,
      3
   ],
   "bar":"baz"
}
```

will be converted into this array shape: `array{foo: array{ 1,  2,  3}, bar: "baz"}` 

And with genealizing the types: `array<string, array<int, int>|string>`

# Contributing

Your contributions are always welcome! Especially PRs improving the design (I suck at it :sweat_smile:) are welcome! :tada:
