
test the lexer

```
$ node dev/tokenize.js <<< 'let foo = "bar"'
LET let
IDENTIFIER foo
ASSIGN =
STRING "bar"
```
test the parser


---

langauge features:

    First class func () => {}
    signed integers literals 1234 -24
    string literals "hello world" "hello \" yo\"world"
    condition logic
    array literal [1, 2, "hey guys", 4]
    map literal #{key1: val1, 2: #{subkey: subval}# }#
    declartion let
    while loop while(true) {}
    operators + - / *
    comments //
