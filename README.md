# vscode

```json
{
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.acceptSuggestionOnCommitCharacter": true, // aceitar sugestões ao digitar caracteres de commit
  "editor.formatOnSave": true, // formatar ao salvar
  "editor.formatOnType": false, // formatar ao digitar
  "editor.formatOnPaste": false, // formatar ao colar
  "editor.lineHeight": 1.8, // espaçamento entre linhas
  "editor.renderWhitespace": "all", // mostrar espaços em branco
  "editor.renderLineHighlight": "all", // destaque da a linha atual
  "editor.linkedEditing": true,
  "editor.largeFileOptimizations": true, // otimizações para arquivos grandes
  "editor.tabSize": 4,
  "editor.fastScrollSensitivity": 5, // sensibilidade do scroll ao segurar o Alt
  "editor.suggest.snippetsPreventQuickSuggestions": false,
  "editor.overviewRulerBorder": false,
  "editor.fontLigatures": true,
  "editor.fontFamily": "JetBrains Mono", // fonte do editor - https://www.jetbrains.com/pt-br/lp/mono/
  "editor.fontSize": 14,
  "editor.minimap.enabled": true,
  "editor.minimap.renderCharacters": true,
  "editor.minimap.showSlider": "always",
  "editor.cursorBlinking": "expand",
  "editor.cursorStyle": "line",
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.cursorWidth": 2,
  "editor.smoothScrolling": true,
  "editor.scrollBeyondLastLine": true, // scroll além da última linha
  "editor.mouseWheelZoom": true,
  "editor.suggestSelection": "first",
  "editor.semanticHighlighting.enabled": false,
  "editor.unicodeHighlight.invisibleCharacters": false,
  "editor.unicodeHighlight.ambiguousCharacters": false,
  "editor.inlineSuggest.suppressSuggestions": false, // sugestões inline

  "files.trimTrailingWhitespace": false,
  "files.associations": {
    ".env.production": "properties",
    ".env.example": "properties",
    ".env.local": "properties",
    "*.gs": "javascript"
  },

  "javascript.updateImportsOnFileMove.enabled": "always",

  "explorer.compactFolders": false,
  "explorer.fileNesting.enabled": false,
  "explorer.confirmDragAndDrop": false,
  "explorer.confirmDelete": false,

  "window.autoDetectColorScheme": false,
  "window.closeWhenEmpty": false,
  "window.density.editorTabHeight": "compact",
  "window.zoomPerWindow": true,

  "workbench.activityBar.iconClickBehavior": "toggle",
  "workbench.navigationControl.enabled": false,
  "workbench.activityBar.location": "default",
  "workbench.panel.showLabels": false,
  "workbench.startupEditor": "none",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.editor.autoLockGroups": {
    "jsProfileVisualizer.cpuprofile.table": true
  },
  "workbench.editorAssociations": {
    "*.copilotmd": "vscode.markdown.preview.editor",
    "*.db": "sqlite-viewer.view",
    "*.md": "vscode.markdown.preview.editor"
  },

  "extensions.ignoreRecommendations": false,

  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.scrollback": 10000,
  "terminal.integrated.fontSize": 12,
  "terminal.integrated.defaultProfile.linux": "zsh",
  "terminal.integrated.defaultProfile.windows": "Windows PowerShell",

  "git.autofetch": true,
  "git.enableSmartCommit": true,
  "git.openRepositoryInParentFolders": "always",
  "git.suggestSmartCommit": true,

  "material-icon-theme.activeIconPack": "nest",
  "material-icon-theme.hidesExplorerArrows": true,
  "material-icon-theme.folders.associations": {
    "infra": "Cluster",
    "dev": "Debug",
    "prod": "Server"
  },

  "typescript.updateImportsOnFileMove.enabled": "always",

  "biome.suggestInstallingGlobally": false,

  "github.copilot.nextEditSuggestions.enabled": true,
  "github.copilot.enable": {
    "*": true,
    "plaintext": false,
    "markdown": true,
    "scminput": false
  },

  // chat settings
  "chat.mcp.autostart": "never",
  "chat.mcp.gallery.enabled": true,
  "chat.agent.maxRequests": 500,
  "chat.tools.terminal.autoApprove": {
    "ls": true,
    "dir": true,
    "curl": true,
    "cd": true,
    "git status": true,
    "git diff": true,
    "npm run": true,
    "npm i": true,
    "npm start": true,
    "docker logs": true,
    "mkdir": true,
    "npm install": true,
    "npm test": true,
    "Test-Path": true
  }
}
```
