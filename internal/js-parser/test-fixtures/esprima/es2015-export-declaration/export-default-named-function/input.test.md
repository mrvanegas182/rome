# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-export-declaration > export-default-named-function`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/es2015-export-declaration/export-default-named-function/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-export-declaration/export-default-named-function/input.js"
		end: Object {
			column: 0
			line: 2
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSExportDefaultDeclaration {
			loc: Object {
				filename: "esprima/es2015-export-declaration/export-default-named-function/input.js"
				end: Object {
					column: 32
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			declaration: JSFunctionDeclaration {
				id: JSBindingIdentifier {
					name: "foo"
					loc: Object {
						filename: "esprima/es2015-export-declaration/export-default-named-function/input.js"
						identifierName: "foo"
						end: Object {
							column: 27
							line: 1
						}
						start: Object {
							column: 24
							line: 1
						}
					}
				}
				loc: Object {
					filename: "esprima/es2015-export-declaration/export-default-named-function/input.js"
					end: Object {
						column: 32
						line: 1
					}
					start: Object {
						column: 15
						line: 1
					}
				}
				body: JSBlockStatement {
					body: Array []
					directives: Array []
					loc: Object {
						filename: "esprima/es2015-export-declaration/export-default-named-function/input.js"
						end: Object {
							column: 32
							line: 1
						}
						start: Object {
							column: 30
							line: 1
						}
					}
				}
				head: JSFunctionHead {
					async: false
					generator: false
					hasHoistedVars: false
					params: Array []
					rest: undefined
					returnType: undefined
					thisType: undefined
					typeParameters: undefined
					loc: Object {
						filename: "esprima/es2015-export-declaration/export-default-named-function/input.js"
						end: Object {
							column: 29
							line: 1
						}
						start: Object {
							column: 27
							line: 1
						}
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
