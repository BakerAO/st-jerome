# Writing An Interpreter In Go


## Commands
go test ./...
go test -v -run TestOperatorPrecedenceParsing ./parser



## To Change:
1. Add `>=`, `<=`
2. Change parser constructor to instantiate lexer
3. See if the token package can be renamed or split up
4. Break up parser
5. Change expectPeek to expectPeekAndNext
