# haskell-yesod-quasiquotes

- Support for [Yesod](https://www.yesodweb.com/)'s Shakespeare template syntax highlighting inside Haskell source files.

- Support for aeson-qq & hasql-th

- Support for graphql inside `gql` quasiquoter

## Dependencies

This extension requires
[haskell-syntax-highlighting](https://github.com/JustusAdam/language-haskell)
and
[vscode-language-yesod](https://github.com/e-bigmoon/vscode-language-yesod).

## Known Issues

- Cassius and route quasiquoters are not currently supported because of regex mismatching [upstream](https://github.com/e-bigmoon/vscode-language-yesod).
- Can't dynamically add new grammars and new associations, which means we have to update the
  extension for any new association to sql or json or hamlet.

## Release Notes

### 0.1.2

- Support for graphql inside `gql` quasiquoter.

### 0.1.1

- Support for hasql-th and aeson-qq quasiquoters

### 0.1.0

Initial release
  - Support for (|s|w|x)hamlet, lucius, julius, and model syntax highlighting within Haskell (.hs) source files
