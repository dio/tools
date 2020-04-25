# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > yield > parameter-default-inside-arrow-inside-generator-2`

```javascript
Program {
  comments: Array []
  corrupt: false
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 1
      index: 53
      line: 3
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  diagnostics: Array [
    Object {
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'yield is not allowed in generator parameters'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 20
          index: 37
          line: 2
        }
        start: Object {
          column: 20
          index: 37
          line: 2
        }
      }
    }
  ]
  body: Array [
    FunctionDeclaration {
      id: BindingIdentifier {
        name: 'fn'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 12
            index: 12
            line: 1
          }
          start: Object {
            column: 10
            index: 10
            line: 1
          }
        }
      }
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 1
          index: 53
          line: 3
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      head: FunctionHead {
        async: false
        generator: true
        hasHoistedVars: false
        params: Array []
        predicate: undefined
        rest: undefined
        returnType: undefined
        thisType: undefined
        typeParameters: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 15
            index: 15
            line: 1
          }
          start: Object {
            column: 12
            index: 12
            line: 1
          }
        }
      }
      body: BlockStatement {
        directives: Array []
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 1
            index: 53
            line: 3
          }
          start: Object {
            column: 15
            index: 15
            line: 1
          }
        }
        body: Array [
          ExpressionStatement {
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 34
                index: 51
                line: 2
              }
              start: Object {
                column: 2
                index: 19
                line: 2
              }
            }
            expression: ArrowFunctionExpression {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 33
                  index: 50
                  line: 2
                }
                start: Object {
                  column: 2
                  index: 19
                  line: 2
                }
              }
              body: BlockStatement {
                body: Array []
                directives: Array []
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 33
                    index: 50
                    line: 2
                  }
                  start: Object {
                    column: 31
                    index: 48
                    line: 2
                  }
                }
              }
              head: FunctionHead {
                async: false
                hasHoistedVars: false
                predicate: undefined
                rest: undefined
                returnType: undefined
                thisType: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 31
                    index: 48
                    line: 2
                  }
                  start: Object {
                    column: 2
                    index: 19
                    line: 2
                  }
                }
                params: Array [
                  BindingAssignmentPattern {
                    operator: '='
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 26
                        index: 43
                        line: 2
                      }
                      start: Object {
                        column: 3
                        index: 20
                        line: 2
                      }
                    }
                    left: BindingIdentifier {
                      name: 'x'
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 4
                          index: 21
                          line: 2
                        }
                        start: Object {
                          column: 3
                          index: 20
                          line: 2
                        }
                      }
                    }
                    right: BinaryExpression {
                      operator: '+'
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 26
                          index: 43
                          line: 2
                        }
                        start: Object {
                          column: 7
                          index: 24
                          line: 2
                        }
                      }
                      left: NumericLiteral {
                        value: 3
                        format: undefined
                        loc: Object {
                          filename: 'input.js'
                          end: Object {
                            column: 8
                            index: 25
                            line: 2
                          }
                          start: Object {
                            column: 7
                            index: 24
                            line: 2
                          }
                        }
                      }
                      right: BinaryExpression {
                        operator: '**'
                        loc: Object {
                          filename: 'input.js'
                          end: Object {
                            column: 26
                            index: 43
                            line: 2
                          }
                          start: Object {
                            column: 11
                            index: 28
                            line: 2
                          }
                        }
                        right: NumericLiteral {
                          value: 2
                          format: undefined
                          loc: Object {
                            filename: 'input.js'
                            end: Object {
                              column: 26
                              index: 43
                              line: 2
                            }
                            start: Object {
                              column: 25
                              index: 42
                              line: 2
                            }
                          }
                        }
                        left: CallExpression {
                          loc: Object {
                            filename: 'input.js'
                            end: Object {
                              column: 21
                              index: 38
                              line: 2
                            }
                            start: Object {
                              column: 11
                              index: 28
                              line: 2
                            }
                          }
                          arguments: Array [
                            YieldExpression {
                              argument: undefined
                              delegate: false
                              loc: Object {
                                filename: 'input.js'
                                end: Object {
                                  column: 20
                                  index: 37
                                  line: 2
                                }
                                start: Object {
                                  column: 15
                                  index: 32
                                  line: 2
                                }
                              }
                            }
                          ]
                          callee: MemberExpression {
                            loc: Object {
                              filename: 'input.js'
                              end: Object {
                                column: 14
                                index: 31
                                line: 2
                              }
                              start: Object {
                                column: 11
                                index: 28
                                line: 2
                              }
                            }
                            object: ReferenceIdentifier {
                              name: 'a'
                              loc: Object {
                                filename: 'input.js'
                                end: Object {
                                  column: 12
                                  index: 29
                                  line: 2
                                }
                                start: Object {
                                  column: 11
                                  index: 28
                                  line: 2
                                }
                              }
                            }
                            property: StaticMemberProperty {
                              value: Identifier {
                                name: 'b'
                                loc: Object {
                                  filename: 'input.js'
                                  end: Object {
                                    column: 14
                                    index: 31
                                    line: 2
                                  }
                                  start: Object {
                                    column: 13
                                    index: 30
                                    line: 2
                                  }
                                }
                              }
                              loc: Object {
                                filename: 'input.js'
                                end: Object {
                                  column: 14
                                  index: 31
                                  line: 2
                                }
                                start: Object {
                                  column: 13
                                  index: 30
                                  line: 2
                                }
                              }
                            }
                          }
                        }
                      }
                    }
                  }
                ]
              }
            }
          }
        ]
      }
    }
  ]
}
```