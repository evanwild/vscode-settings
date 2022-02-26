# vscode-settings

My good-looking VS Code settings for JS/React development.

### Extensions

- [Alabaster Theme](https://marketplace.visualstudio.com/items?itemName=tonsky.theme-alabaster)
- [Rubber Theme](https://marketplace.visualstudio.com/items?itemName=apust.rubber-theme)
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)

### settings.json

```json
{
  "editor.cursorBlinking": "expand",
  "editor.cursorSmoothCaretAnimation": true,

  "editor.fontFamily": "Monaco",
  "editor.fontSize": 16,
  "terminal.integrated.fontSize": 16,
  "editor.letterSpacing": 0.5,
  "editor.lineHeight": 25,

  "workbench.iconTheme": "material-icon-theme",
  "workbench.preferredLightColorTheme": "Alabaster",
  "workbench.preferredDarkColorTheme": "Rubber",
  "window.autoDetectColorScheme": true,
  "workbench.colorTheme": "Rubber",

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
