# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/css-parser/index.test.ts --update-snapshots` to update.

## `invalid > calc-space`

```javascript
CSSRoot {
	comments: Array []
	corrupt: false
	integrity: undefined
	loc: SourceLocation invalid/calc-space/input.css 1:0-3:1
	path: RelativeFilePath<invalid/calc-space/input.css>
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse"}]
			location: Object {
				integrity: undefined
				language: "css"
				sourceText: undefined
				end: Position 2:20
				path: RelativeFilePath<invalid/calc-space/input.css>
				start: Position 2:16
			}
			description: Object {
				category: "parse"
				categoryValue: "css"
				message: RAW_MARKUP {value: "An operator is needed."}
				advice: Array [
					log {
						category: "info"
						text: RAW_MARKUP {value: "Consider adding <emphasis>+ or -</emphasis>"}
					}
				]
			}
		}
	]
	body: Array [
		CSSRule {
			loc: SourceLocation invalid/calc-space/input.css 1:0-3:1
			prelude: Array [
				CSSSelector {
					loc: SourceLocation invalid/calc-space/input.css 1:0-1:7
					patterns: Array [
						CSSClassSelector {
							value: "style"
							loc: SourceLocation invalid/calc-space/input.css 1:0-1:6
						}
					]
				}
			]
			block: CSSBlock {
				value: Array [
					CSSDeclaration {
						name: "width"
						value: Array [
							CSSCalcFunction {
								name: "calc"
								loc: SourceLocation invalid/calc-space/input.css 2:13-2:20
								params: Array [
									CSSCalcSum {
										value: Array [
											CSSCalcProduct {
												value: Array [
													CSSCalcValue {
														value: CSSDimension {
															value: 2
															unit: "px"
															loc: SourceLocation invalid/calc-space/input.css 2:13-2:13
														}
														loc: SourceLocation invalid/calc-space/input.css 2:13-2:16
													}
												]
												loc: SourceLocation invalid/calc-space/input.css 2:16-2:16
											}
										]
										loc: SourceLocation invalid/calc-space/input.css 2:13-2:16
									}
								]
							}
							CSSRaw {
								value: undefined
								loc: SourceLocation invalid/calc-space/input.css 2:20-2:21
							}
						]
						important: false
						loc: SourceLocation invalid/calc-space/input.css 2:1-2:21
					}
				]
				startingTokenValue: "{"
				loc: SourceLocation invalid/calc-space/input.css 1:7-3:1
			}
		}
	]
}
```