# vscode-settings

My good-looking VS Code settings for JS/React development.

### Font
- [JetBrains Mono](https://www.jetbrains.com/lp/mono/)

### Extensions

- [GitHub Theme](https://marketplace.visualstudio.com/items?itemName=GitHub.github-vscode-theme)
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)

### settings.json

```json
{
  "editor.cursorBlinking": "phase",
  "editor.cursorSmoothCaretAnimation": true,

  "editor.fontFamily": "Jetbrains Mono",
  "editor.fontSize": 16,
  "terminal.integrated.fontSize": 16,
  "editor.letterSpacing": 0.5,
  "editor.lineHeight": 25,

  "workbench.colorTheme": "GitHub Dark",
  "workbench.iconTheme": "material-icon-theme",
  "editor.bracketPairColorization.enabled": true,

  "editor.tabSize": 2,
  "editor.insertSpaces": true,
  "editor.formatOnPaste": true,
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "prettier.singleQuote": true,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  }
}
```
