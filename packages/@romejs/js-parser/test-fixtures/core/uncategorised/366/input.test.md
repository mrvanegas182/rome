# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 366`

```javascript
Program {
  comments: Array []
  corrupt: false
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: true
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 18
      index: 18
      line: 1
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
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Bad character escape sequence'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 17
          index: 17
          line: 1
        }
        start: Object {
          column: 17
          index: 17
          line: 1
        }
      }
    }
  ]
  body: Array [
    VariableDeclarationStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 18
          index: 18
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      declaration: VariableDeclaration {
        kind: 'var'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 18
            index: 18
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        declarations: Array [
          VariableDeclarator {
            id: BindingIdentifier {
              name: 'x'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 5
                  index: 5
                  line: 1
                }
                start: Object {
                  column: 4
                  index: 4
                  line: 1
                }
              }
            }
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 18
                index: 18
                line: 1
              }
              start: Object {
                column: 4
                index: 4
                line: 1
              }
            }
            init: RegExpLiteral {
              global: false
              insensitive: false
              multiline: false
              noDotNewline: false
              sticky: false
              unicode: false
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 18
                  index: 18
                  line: 1
                }
                start: Object {
                  column: 8
                  index: 8
                  line: 1
                }
              }
              expression: RegExpSubExpression {
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 13
                    index: 14
                    line: 1
                  }
                  start: Object {
                    column: 9
                    index: 9
                    line: 1
                  }
                }
                body: Array [
                  RegExpCharSet {
                    invert: false
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 13
                        index: 13
                        line: 1
                      }
                      start: Object {
                        column: 9
                        index: 9
                        line: 1
                      }
                    }
                    body: Array [
                      RegExpCharSetRange {
                        loc: Object {
                          filename: 'input.js'
                          end: Object {
                            column: 13
                            index: 13
                            line: 1
                          }
                          start: Object {
                            column: 10
                            index: 10
                            line: 1
                          }
                        }
                        end: RegExpCharacter {
                          value: 'z'
                          loc: Object {
                            filename: 'input.js'
                            end: Object {
                              column: 13
                              index: 13
                              line: 1
                            }
                            start: Object {
                              column: 12
                              index: 12
                              line: 1
                            }
                          }
                        }
                        start: RegExpCharacter {
                          value: 'a'
                          loc: Object {
                            filename: 'input.js'
                            end: Object {
                              column: 11
                              index: 11
                              line: 1
                            }
                            start: Object {
                              column: 10
                              index: 10
                              line: 1
                            }
                          }
                        }
                      }
                    ]
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