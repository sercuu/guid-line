## VS Code User Settings

```json
{
    "eslint.alwaysShowStatus": true,
    "editor.formatOnSave": true,
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true
    },
    "prettier.disableLanguages": ["js"],
    "scssFormatter.singleQuote": false,
    "scssFormatter.tabWidth": 4,
    "[javascript]": {
        "editor.formatOnSave": false,
        "editor.defaultFormatter": "dbaeumer.vscode-eslint"
    },
    "[jsonc]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[json]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    }
}
```
