# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2020 > optional-chaining > member-access`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "es2020/optional-chaining/member-access/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2020/optional-chaining/member-access/input.js"
		end: Object {
			column: 12
			line: 5
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "es2020/optional-chaining/member-access/input.js"
				end: Object {
					column: 8
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSMemberExpression {
				loc: Object {
					filename: "es2020/optional-chaining/member-access/input.js"
					end: Object {
						column: 8
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				object: JSReferenceIdentifier {
					name: "foo"
					loc: Object {
						filename: "es2020/optional-chaining/member-access/input.js"
						identifierName: "foo"
						end: Object {
							column: 3
							line: 1
						}
						start: Object {
							column: 0
							line: 1
						}
					}
				}
				property: JSStaticMemberProperty {
					value: JSIdentifier {
						name: "bar"
						loc: Object {
							filename: "es2020/optional-chaining/member-access/input.js"
							identifierName: "bar"
							end: Object {
								column: 8
								line: 1
							}
							start: Object {
								column: 5
								line: 1
							}
						}
					}
					optional: true
					loc: Object {
						filename: "es2020/optional-chaining/member-access/input.js"
						identifierName: "bar"
						end: Object {
							column: 8
							line: 1
						}
						start: Object {
							column: 5
							line: 1
						}
					}
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "es2020/optional-chaining/member-access/input.js"
				end: Object {
					column: 13
					line: 3
				}
				start: Object {
					column: 0
					line: 3
				}
			}
			expression: JSMemberExpression {
				loc: Object {
					filename: "es2020/optional-chaining/member-access/input.js"
					end: Object {
						column: 13
						line: 3
					}
					start: Object {
						column: 0
						line: 3
					}
				}
				property: JSStaticMemberProperty {
					value: JSIdentifier {
						name: "baz"
						loc: Object {
							filename: "es2020/optional-chaining/member-access/input.js"
							identifierName: "baz"
							end: Object {
								column: 13
								line: 3
							}
							start: Object {
								column: 10
								line: 3
							}
						}
					}
					optional: true
					loc: Object {
						filename: "es2020/optional-chaining/member-access/input.js"
						identifierName: "baz"
						end: Object {
							column: 13
							line: 3
						}
						start: Object {
							column: 10
							line: 3
						}
					}
				}
				object: JSMemberExpression {
					loc: Object {
						filename: "es2020/optional-chaining/member-access/input.js"
						end: Object {
							column: 8
							line: 3
						}
						start: Object {
							column: 0
							line: 3
						}
					}
					object: JSReferenceIdentifier {
						name: "foo"
						loc: Object {
							filename: "es2020/optional-chaining/member-access/input.js"
							identifierName: "foo"
							end: Object {
								column: 3
								line: 3
							}
							start: Object {
								column: 0
								line: 3
							}
						}
					}
					property: JSStaticMemberProperty {
						value: JSIdentifier {
							name: "bar"
							loc: Object {
								filename: "es2020/optional-chaining/member-access/input.js"
								identifierName: "bar"
								end: Object {
									column: 8
									line: 3
								}
								start: Object {
									column: 5
									line: 3
								}
							}
						}
						optional: true
						loc: Object {
							filename: "es2020/optional-chaining/member-access/input.js"
							identifierName: "bar"
							end: Object {
								column: 8
								line: 3
							}
							start: Object {
								column: 5
								line: 3
							}
						}
					}
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "es2020/optional-chaining/member-access/input.js"
				end: Object {
					column: 12
					line: 5
				}
				start: Object {
					column: 0
					line: 5
				}
			}
			expression: JSMemberExpression {
				loc: Object {
					filename: "es2020/optional-chaining/member-access/input.js"
					end: Object {
						column: 12
						line: 5
					}
					start: Object {
						column: 0
						line: 5
					}
				}
				property: JSStaticMemberProperty {
					value: JSIdentifier {
						name: "baz"
						loc: Object {
							filename: "es2020/optional-chaining/member-access/input.js"
							identifierName: "baz"
							end: Object {
								column: 12
								line: 5
							}
							start: Object {
								column: 9
								line: 5
							}
						}
					}
					optional: true
					loc: Object {
						filename: "es2020/optional-chaining/member-access/input.js"
						identifierName: "baz"
						end: Object {
							column: 12
							line: 5
						}
						start: Object {
							column: 9
							line: 5
						}
					}
				}
				object: JSMemberExpression {
					loc: Object {
						filename: "es2020/optional-chaining/member-access/input.js"
						end: Object {
							column: 7
							line: 5
						}
						start: Object {
							column: 0
							line: 5
						}
					}
					object: JSReferenceIdentifier {
						name: "foo"
						loc: Object {
							filename: "es2020/optional-chaining/member-access/input.js"
							identifierName: "foo"
							end: Object {
								column: 3
								line: 5
							}
							start: Object {
								column: 0
								line: 5
							}
						}
					}
					property: JSStaticMemberProperty {
						value: JSIdentifier {
							name: "bar"
							loc: Object {
								filename: "es2020/optional-chaining/member-access/input.js"
								identifierName: "bar"
								end: Object {
									column: 7
									line: 5
								}
								start: Object {
									column: 4
									line: 5
								}
							}
						}
						loc: Object {
							filename: "es2020/optional-chaining/member-access/input.js"
							identifierName: "bar"
							end: Object {
								column: 7
								line: 5
							}
							start: Object {
								column: 4
								line: 5
							}
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