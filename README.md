# coffeelint-advanced-missing-fat-arrows

This is exactly like the coffeelint builtin `missing_fat_arrows` rule, except you can disable it with a `'use this'` directive in the first line of your function.

Install via npm, then configure in coffeelint.json like so:

```
"advanced_missing_fat_arrows": {
	"module": "coffeelint-advanced-missing-fat-arrows",
	"level": "warn"
}
```
