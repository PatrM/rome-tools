# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/css-parser/index.test.ts --update-snapshots` to update.

## `invalid > min-or-max`

```javascript
CSSRoot {
	body: [
		CSSRule {
			prelude: [
				CSSSelector {
					patterns: [
						CSSClassSelector {
							value: "style"
							loc: SourceLocation invalid/min-or-max/invalid.css 1:0-1:6
						}
					]
					loc: SourceLocation invalid/min-or-max/invalid.css 1:0-1:7
				}
			]
			block: CSSBlock {
				value: [
					CSSDeclaration {
						name: "width"
						value: [
							CSSFunction {
								name: "min"
								params: []
								loc: SourceLocation invalid/min-or-max/invalid.css 2:8-2:17
							}
						]
						important: false
						loc: SourceLocation invalid/min-or-max/invalid.css 2:1-2:17
					}
				]
				startingTokenValue: "{"
				loc: SourceLocation invalid/min-or-max/invalid.css 1:7-3:1
			}
			loc: SourceLocation invalid/min-or-max/invalid.css 1:0-3:1
		}
	]
	comments: []
	corrupt: false
	diagnostics: [
		{
			origins: [{entity: "ParserCore<css>"}]
			description: {
				advice: []
				category: ["parse"]
				categoryValue: "css"
				message: RAW_MARKUP {value: "The operators <emphasis>+</emphasis> and <emphasis>-</emphasis> need to have a space left and right"}
			}
			location: {
				language: "css"
				path: RelativePath<invalid/min-or-max/invalid.css>
				end: Position 2:18
				start: Position 2:17
			}
		}
	]
	path: RelativePath<invalid/min-or-max/invalid.css>
	loc: SourceLocation invalid/min-or-max/invalid.css 1:0-3:1
}
```