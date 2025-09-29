# vscode

```json
{
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.acceptSuggestionOnCommitCharacter": true,
  "editor.lineHeight": 1.8,
  "editor.renderLineHighlight": "all",
  "editor.linkedEditing": true,
  "editor.largeFileOptimizations": false,
  "editor.tabSize": 4,
  "editor.fastScrollSensitivity": 5,
  "editor.suggest.snippetsPreventQuickSuggestions": false,
  "editor.overviewRulerBorder": false,
  "editor.fontLigatures": true,
  "editor.fontFamily": "JetBrains Mono",
  "editor.fontSize": 14,
  "editor.minimap.enabled": true,
  "editor.minimap.renderCharacters": false,
  "editor.minimap.showSlider": "always",
  "editor.minimap.size": "fit",
  "editor.cursorBlinking": "expand",
  "editor.cursorStyle": "line",
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.cursorWidth": 2,
  "editor.smoothScrolling": true,
  "editor.scrollBeyondLastLine": true,
  "editor.mouseWheelZoom": true,
  "editor.suggestSelection": "first",
  "editor.semanticHighlighting.enabled": false,
  "editor.unicodeHighlight.invisibleCharacters": false,
  "editor.unicodeHighlight.ambiguousCharacters": false,
  "editor.inlineSuggest.suppressSuggestions": true,
  "editor.formatOnSave": true,
  "editor.codeActionsOnSave": {
    "source.addMissingImports.ts": "explicit",
    "source.removeUnusedImports": "explicit",
    "source.organizeImports": "explicit"
  },

  "files.trimTrailingWhitespace": false,
  "files.associations": {
    ".env.production": "properties",
    ".env.docker": "properties"
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
  "workbench.colorTheme": "Default Dark+",
  "workbench.startupEditor": "none",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.editorAssociations": {
    "*.copilotmd": "vscode.markdown.preview.editor",
    "*.db": "sqlite-viewer.view"
  },

  "extensions.ignoreRecommendations": false,
  "extensions.autoUpdate": true,

  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.scrollback": 10000,
  "terminal.integrated.fontSize": 12,
  "terminal.integrated.defaultProfile.linux": "bash",
  "terminal.integrated.defaultProfile.windows": "Windows PowerShell",

  "git.autofetch": true,
  "git.confirmSync": false,
  "git.enableSmartCommit": false,
  "git.openRepositoryInParentFolders": "always",
  "git.suggestSmartCommit": false,

  "material-icon-theme.activeIconPack": "nest",

  "typescript.updateImportsOnFileMove.enabled": "always",

  "github.copilot.nextEditSuggestions.enabled": true,

  "biome.suggestInstallingGlobally": false,

  "chat.mcp.serverSampling": {
    "Global in Code: chromedevtools/chrome-devtools-mcp": {
      "allowedModels": ["copilot/grok-code-fast-1"]
    }
  },
  "chat.agent.maxRequests": 500,
  "chat.tools.terminal.autoApprove": {
    "ls": false,
    "dir": false,
    "curl": true,
    "cd": true,
    "npm run": true,
    "git status": true
  }
}

```
