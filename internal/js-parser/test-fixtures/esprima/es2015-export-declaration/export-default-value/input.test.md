# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-export-declaration > export-default-value`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/es2015-export-declaration/export-default-value/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-export-declaration/export-default-value/input.js"
		end: Object {
			column: 0
			index: 20
			line: 2
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSExportDefaultDeclaration {
			loc: Object {
				filename: "esprima/es2015-export-declaration/export-default-value/input.js"
				end: Object {
					column: 19
					index: 19
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			declaration: JSReferenceIdentifier {
				name: "foo"
				loc: Object {
					filename: "esprima/es2015-export-declaration/export-default-value/input.js"
					identifierName: "foo"
					end: Object {
						column: 18
						index: 18
						line: 1
					}
					start: Object {
						column: 15
						index: 15
						line: 1
					}
				}
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```