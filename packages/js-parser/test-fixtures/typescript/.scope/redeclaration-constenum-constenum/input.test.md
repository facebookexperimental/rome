# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > scope > redeclaration-constenum-constenum`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "input.ts"
		end: Object {
			column: 17
			index: 35
			line: 2
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		TSEnumDeclaration {
			id: JSBindingIdentifier {
				name: "Foo"
				loc: Object {
					filename: "input.ts"
					identifierName: "Foo"
					end: Object {
						column: 14
						index: 14
						line: 1
					}
					start: Object {
						column: 11
						index: 11
						line: 1
					}
				}
			}
			const: true
			members: Array []
			loc: Object {
				filename: "input.ts"
				end: Object {
					column: 17
					index: 17
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
		}
		TSEnumDeclaration {
			id: JSBindingIdentifier {
				name: "Foo"
				loc: Object {
					filename: "input.ts"
					identifierName: "Foo"
					end: Object {
						column: 14
						index: 32
						line: 2
					}
					start: Object {
						column: 11
						index: 29
						line: 2
					}
				}
			}
			const: true
			members: Array []
			loc: Object {
				filename: "input.ts"
				end: Object {
					column: 17
					index: 35
					line: 2
				}
				start: Object {
					column: 0
					index: 18
					line: 2
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