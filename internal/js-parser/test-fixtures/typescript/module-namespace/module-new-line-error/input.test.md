# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > module-namespace > module-new-line-error`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "typescript/module-namespace/module-new-line-error/input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/module-namespace/module-new-line-error/input.ts"
		end: Object {
			column: 0
			line: 3
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse/js"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: MARKUP {parts: Array [RAW_MARKUP {value: "Expected a semicolon or a line terminator"}]}
			}
			location: Object {
				filename: "typescript/module-namespace/module-new-line-error/input.ts"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 3
					line: 2
				}
				start: Object {
					column: 4
					line: 2
				}
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "typescript/module-namespace/module-new-line-error/input.ts"
				end: Object {
					column: 6
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSReferenceIdentifier {
				name: "module"
				loc: Object {
					filename: "typescript/module-namespace/module-new-line-error/input.ts"
					identifierName: "module"
					end: Object {
						column: 6
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "typescript/module-namespace/module-new-line-error/input.ts"
				end: Object {
					column: 3
					line: 2
				}
				start: Object {
					column: 0
					line: 2
				}
			}
			expression: JSReferenceIdentifier {
				name: "Foo"
				loc: Object {
					filename: "typescript/module-namespace/module-new-line-error/input.ts"
					identifierName: "Foo"
					end: Object {
						column: 3
						line: 2
					}
					start: Object {
						column: 0
						line: 2
					}
				}
			}
		}
		JSBlockStatement {
			body: Array []
			directives: Array []
			loc: Object {
				filename: "typescript/module-namespace/module-new-line-error/input.ts"
				end: Object {
					column: 6
					line: 2
				}
				start: Object {
					column: 4
					line: 2
				}
			}
		}
	]
}
```

### `diagnostics`

```

 typescript/module-namespace/module-new-line-error/input.ts:2:4 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Expected a semicolon or a line terminator

    1 │ module
  > 2 │ Foo {}
      │     ^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
