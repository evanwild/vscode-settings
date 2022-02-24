# vscode-settings

My good-looking VS Code settings for JS/React development.

### Extensions

- [Panda Theme](https://marketplace.visualstudio.com/items?itemName=tinkertrain.theme-panda)
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)

### settings.json

```json
{
  // Cursor
  "editor.cursorBlinking": "expand",
  "editor.cursorSmoothCaretAnimation": true,

  // Font
  "editor.fontFamily": "Monaco",
  "editor.fontSize": 16,
  "terminal.integrated.fontSize": 16,
  "editor.letterSpacing": 0.5,
  "editor.lineHeight": 25,

  // Colors
  "workbench.colorTheme": "Panda Syntax",
  "workbench.iconTheme": "material-icon-theme",
  "editor.bracketPairColorization.enabled": true,
  "workbench.colorCustomizations": {
    "[*]": {
      "editorBracketHighlight.foreground1": "#ffcc95",
      "editorBracketHighlight.foreground2": "#ff75b5",
      "editorBracketHighlight.foreground3": "#70c1ff"
    }
  },

  // JavaScript & React
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
