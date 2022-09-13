## settings.json

```json

{
  "editor.fontSize": 16,
  "terminal.integrated.fontSize": 12,
  "workbench.colorTheme": "Aura Soft Dark",
  "workbench.iconTheme": "material-icon-theme",
  "editor.minimap.enabled": false,
  "editor.wordWrap": "on",
  "workbench.editor.tabSizing": "shrink",
  "explorer.compactFolders": false,

  // formatter
  "prettier.tabWidth": 2,
  "prettier.semi": false,
  "prettier.singleQuote": true,
  "prettier.trailingComma": "none",
  "prettier.arrowParens": "avoid",
  "prettier.endOfLine": "auto",
  "editor.tabSize": 2,
  "editor.formatOnSave": true,
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "liveServer.settings.donotShowInfoMsg": true,
  "liveServer.settings.donotVerifyTags": true,
  "files.autoSave": "afterDelay",
  "powermode.presets": "flames",
  "powermode.enabled": true,
  "editor.suggestSelection": "first",
  "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  "git.enableSmartCommit": true,
  "tabnine.experimentalAutoImports": true,
  "explorer.confirmDragAndDrop": false,
  "window.zoomLevel": 1,
  "terminal.integrated.profiles.windows": {
    "PowerShell": {
      "source": "PowerShell",
      "icon": "terminal-powershell"
    },
    "Command Prompt": {
      "path": [
        "${env:windir}\\Sysnative\\cmd.exe",
        "${env:windir}\\System32\\cmd.exe"
      ],
      "args": [],
      "icon": "terminal-cmd"
    },
    "Git Bash": {
      "source": "Git Bash"
    },
    "Ubuntu (WSL)": {
      "path": "C:\\WINDOWS\\System32\\wsl.exe",
      "args": ["-d", "Ubuntu"]
    }
  },
  "terminal.integrated.defaultProfile.windows": "Ubuntu (WSL)",
  "bracket-pair-colorizer-2.depreciation-notice": true
}


```
