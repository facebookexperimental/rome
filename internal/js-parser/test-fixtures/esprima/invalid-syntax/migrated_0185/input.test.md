# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > invalid-syntax > migrated_0185`

### `ast`

```javascript
JSRoot {
	body: [
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "hello"
				loc: SourceLocation esprima/invalid-syntax/migrated_0185/input.js 1:9-1:14 (hello)
			}
			body: JSBlockStatement {
				body: [
					JSVariableDeclarationStatement {
						declaration: JSVariableDeclaration {
							kind: "var"
							declarations: [
								JSVariableDeclarator {
									id: JSBindingIdentifier {
										name: "eval"
										loc: SourceLocation esprima/invalid-syntax/migrated_0185/input.js 1:36-1:40 (eval)
									}
									init: JSNumericLiteral {
										value: 10
										loc: SourceLocation esprima/invalid-syntax/migrated_0185/input.js 1:43-1:45
									}
									loc: SourceLocation esprima/invalid-syntax/migrated_0185/input.js 1:36-1:45
								}
							]
							loc: SourceLocation esprima/invalid-syntax/migrated_0185/input.js 1:32-1:46
						}
						loc: SourceLocation esprima/invalid-syntax/migrated_0185/input.js 1:32-1:46
					}
				]
				directives: [
					JSDirective {
						value: "use strict"
						loc: SourceLocation esprima/invalid-syntax/migrated_0185/input.js 1:18-1:31
					}
				]
				loc: SourceLocation esprima/invalid-syntax/migrated_0185/input.js 1:17-1:48
			}
			head: JSFunctionHead {
				async: false
				generator: false
				hasHoistedVars: true
				params: []
				loc: SourceLocation esprima/invalid-syntax/migrated_0185/input.js 1:14-1:16
			}
			loc: SourceLocation esprima/invalid-syntax/migrated_0185/input.js 1:0-1:48
		}
	]
	comments: []
	corrupt: false
	diagnostics: [
		{
			origins: [{entity: "ParserCore<js>"}]
			description: {advice: [], category: ["parse"], categoryValue: "js", message: ["eval", RAW_MARKUP {value: " is a reserved word"}]}
			location: {
				language: "js"
				path: UIDPath<esprima/invalid-syntax/migrated_0185/input.js>
				end: Position 1:40
				start: Position 1:36
			}
		}
	]
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<esprima/invalid-syntax/migrated_0185/input.js>
	loc: SourceLocation esprima/invalid-syntax/migrated_0185/input.js 1:0-2:0
}
```

### `diagnostics`

```

 esprima/invalid-syntax/migrated_0185/input.js:1:36 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ eval is a reserved word

    function hello() {'use strict'; var eval = 10; }
                                        ^^^^


```
