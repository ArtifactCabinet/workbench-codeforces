# Snippets

```haskell
-- print lengths of each liens
main = interact (unlines . map inputLength  . lines)
inputLength input = show $ length input
```