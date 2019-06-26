> purs compile src/Main.purs

```
purs: Internal parser error: Invalid name: SourceToken {tokAnn = TokenAnn {tokRange = SourceRange {srcStart = SourcePos {srcLine = 4, srcColumn = 5}, srcEnd = SourcePos {srcLine = 4, srcColumn = 7}}, tokLeadingComments = [], tokTrailingComments = [Space 1]}, tokValue = TokString "" ""}
CallStack (from HasCallStack):
  error, called at src/Language/PureScript/CST/Utils.hs:79:17 in purescript-0.13.0-2mLnpIbmSLE8KJ0K8giZUZ:Language.PureScript.CST.Utils
purs: thread blocked indefinitely in an MVar operation
```
