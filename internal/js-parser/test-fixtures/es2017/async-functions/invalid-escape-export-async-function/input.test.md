# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2017 > async-functions > invalid-escape-export-async-function`

### `ast`

```javascript
JSRoot {
	body: [
		JSExportLocalDeclaration {
			exportKind: "value"
			specifiers: [
				JSExportLocalSpecifier {
					exported: JSIdentifier {
						name: "async"
						loc: SourceLocation es2017/async-functions/invalid-escape-export-async-function/input.js 1:7-1:17 (async)
					}
					local: JSReferenceIdentifier {
						name: "async"
						loc: SourceLocation es2017/async-functions/invalid-escape-export-async-function/input.js 1:7-1:17 (async)
					}
					loc: SourceLocation es2017/async-functions/invalid-escape-export-async-function/input.js 1:7-1:17
				}
				JSExportLocalSpecifier {
					exported: JSIdentifier {
						name: "function"
						loc: SourceLocation es2017/async-functions/invalid-escape-export-async-function/input.js 1:18-1:26 (function)
					}
					local: JSReferenceIdentifier {
						name: "function"
						loc: SourceLocation es2017/async-functions/invalid-escape-export-async-function/input.js 1:18-1:26 (function)
					}
					loc: SourceLocation es2017/async-functions/invalid-escape-export-async-function/input.js 1:18-1:26
				}
				JSExportLocalSpecifier {
					exported: JSIdentifier {
						name: "y"
						loc: SourceLocation es2017/async-functions/invalid-escape-export-async-function/input.js 1:27-1:28 (y)
					}
					local: JSReferenceIdentifier {
						name: "y"
						loc: SourceLocation es2017/async-functions/invalid-escape-export-async-function/input.js 1:27-1:28 (y)
					}
					loc: SourceLocation es2017/async-functions/invalid-escape-export-async-function/input.js 1:27-1:28
				}
				JSExportLocalSpecifier {
					exported: JSIdentifier {
						name: ""
						loc: SourceLocation es2017/async-functions/invalid-escape-export-async-function/input.js 1:28-1:29 ()
					}
					local: JSReferenceIdentifier {
						name: ""
						loc: SourceLocation es2017/async-functions/invalid-escape-export-async-function/input.js 1:28-1:29 ()
					}
					loc: SourceLocation es2017/async-functions/invalid-escape-export-async-function/input.js 1:28-1:29
				}
				JSExportLocalSpecifier {
					exported: JSIdentifier {
						name: ""
						loc: SourceLocation es2017/async-functions/invalid-escape-export-async-function/input.js 1:29-1:30 ()
					}
					local: JSReferenceIdentifier {
						name: ""
						loc: SourceLocation es2017/async-functions/invalid-escape-export-async-function/input.js 1:29-1:30 ()
					}
					loc: SourceLocation es2017/async-functions/invalid-escape-export-async-function/input.js 1:29-1:30
				}
				JSExportLocalSpecifier {
					exported: JSIdentifier {
						name: ""
						loc: SourceLocation es2017/async-functions/invalid-escape-export-async-function/input.js 1:31-1:32 ()
					}
					local: JSReferenceIdentifier {
						name: ""
						loc: SourceLocation es2017/async-functions/invalid-escape-export-async-function/input.js 1:31-1:32 ()
					}
					loc: SourceLocation es2017/async-functions/invalid-escape-export-async-function/input.js 1:31-1:32
				}
				JSExportLocalSpecifier {
					exported: JSIdentifier {
						name: "await"
						loc: SourceLocation es2017/async-functions/invalid-escape-export-async-function/input.js 1:33-1:38 (await)
					}
					local: JSReferenceIdentifier {
						name: "await"
						loc: SourceLocation es2017/async-functions/invalid-escape-export-async-function/input.js 1:33-1:38 (await)
					}
					loc: SourceLocation es2017/async-functions/invalid-escape-export-async-function/input.js 1:33-1:38
				}
				JSExportLocalSpecifier {
					exported: JSIdentifier {
						name: "x"
						loc: SourceLocation es2017/async-functions/invalid-escape-export-async-function/input.js 1:39-1:40 (x)
					}
					local: JSReferenceIdentifier {
						name: "x"
						loc: SourceLocation es2017/async-functions/invalid-escape-export-async-function/input.js 1:39-1:40 (x)
					}
					loc: SourceLocation es2017/async-functions/invalid-escape-export-async-function/input.js 1:39-1:40
				}
			]
			loc: SourceLocation es2017/async-functions/invalid-escape-export-async-function/input.js 1:0-1:42
		}
	]
	comments: []
	corrupt: false
	diagnostics: [
		{
			origins: [{entity: "ParserCore<js>"}]
			description: {
				advice: [
					log {
						category: "info"
						text: [
							RAW_MARKUP {value: "Expected the opening "}
							"export specifiers"
							RAW_MARKUP {value: " character <emphasis>"}
							"{"
							RAW_MARKUP {value: "</emphasis>"}
						]
					}
				]
				category: ["parse"]
				categoryValue: "js"
				message: [RAW_MARKUP {value: "Unexpected character <emphasis>"}, "\\", RAW_MARKUP {value: "</emphasis>"}]
			}
			location: {
				language: "js"
				path: UIDPath<es2017/async-functions/invalid-escape-export-async-function/input.js>
				end: Position 1:6
				start: Position 1:7
			}
		}
	]
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<es2017/async-functions/invalid-escape-export-async-function/input.js>
	loc: SourceLocation es2017/async-functions/invalid-escape-export-async-function/input.js 1:0-2:0
}
```

### `diagnostics`

```

 es2017/async-functions/invalid-escape-export-async-function/input.js:1:7 parse(js) ━━━━━━━━━━━━━━━━

  ✖ Unexpected character \

    export \u0061sync function y() { await x }
           ^

  ℹ Expected the opening export specifiers character {


```
