```
{
  "window.titleBarStyle": "custom",
  "window.zoomLevel": 0.3,
  "workbench.colorTheme": "Ayu Mirage Bordered",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.startupEditor": "none",
  "workbench.productIconTheme": "fluent-icons",
  "workbench.editor.openSideBySideDirection": "down",
  "editor.fontFamily": "'Cascadia Code', Menlo, Consolas, 'Courier New', monospace",
  "terminal.integrated.fontFamily": "MesloLGS NF",
  "terminal.integrated.fontSize": 12,
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[csharp]": {
    "editor.defaultFormatter": "ms-dotnettools.csharp"
  },
  "editor.stickyScroll.enabled": true,
  "editor.minimap.autohide": true,
  "terminal.integrated.cursorBlinking": true,
  "remote.autoForwardPortsSource": "hybrid",
  "todohighlight.keywords": [
    "FIXME:",
    "REVIEW:",
    "DEBUG:",
    {
      "text": "INFO:",
      "color": "green",
      "backgroundColor": "rgba(0,0,0,0)",
      "border": "none",
      "isWholeLine": false
    },
    {
      "text": "NOTE:",
      "color": "#ff0000",
      "backgroundColor": "yellow",
      "overviewRulerColor": "grey",
      "regex": {
        "pattern": "(?<=^|\"|\\s)NOTE[:]?(?!\\w)"
      },
      "isWholeLine": false
    },
    {
      "text": "WARNING:",
      "before": {
        "contentText": "⚠️"
      },
      "after": {
        "contentText": "⚠️"
      },
      "color": "red",
      "border": "1px solid red",
      "borderRadius": "2px",
      "backgroundColor": "rgba(0,0,0,.2)"
    }
  ],
  "todohighlight.include": [
    "**/*.js",
    "**/*.jsx",
    "**/*.ts",
    "**/*.tsx",
    "**/*.html",
    "**/*.php",
    "**/*.css",
    "**/*.scss",
    "**/*.cs"
  ],
  "codeium.enableConfig": {
    "*": false
  },
  "codeium.enableCodeLens": false,
  "files.autoSave": "afterDelay",
  "diffEditor.ignoreTrimWhitespace": false,
  "[sql]": {
    "editor.defaultFormatter": "ms-mssql.mssql"
  },
  "security.allowedUNCHosts": ["wsl.localhost"],
  "editor.renderLineHighlight": "none",
  "editor.guides.bracketPairs": "active",
  "editor.matchBrackets": "never",
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit",
    "source.fixAll": "explicit"
  },
  "javascript.validate.enable": false,
  "eslint.alwaysShowStatus": true,
  "eslint.format.enable": true,
  "code-runner.showExecutionMessage": false,
  "code-runner.clearPreviousOutput": true,
  "mssql.connections": [
    {
      "server": "OM-PC",
      "database": "master",
      "authenticationType": "SqlLogin",
      "user": "sa",
      "password": "",
      "emptyPasswordInput": false,
      "savePassword": true,
      "profileName": "OM-PC",
      "encrypt": "Mandatory",
      "trustServerCertificate": true
    }
  ],
  "editor.tabSize": 4,
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2
  },
  "[json]": {
    "editor.tabSize": 2
  },
  "editor.insertSpaces": true,
  "workbench.colorCustomizations": {
    "[Ayu Mirage Bordered]": {
      "tab.activeBorder": "#ffcc66",
      "tab.activeBorderTop": "#242936",
      "sideBar.background": "#1C222C",
      "progressBar.background": "#1C222C",
      "editor.background": "#1C222C",
      "editor.selectionBackground": "#2B3944",
      "editor.selectionHighlightBackground": "#2B3944",
      "editor.selectionHighlightBorder": "#0000",
      "editor.wordHighlightBackground": "#0000",
      "editor.wordHighlightBorder": "#0000"
    }
  },
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": [
          "punctuation.accessor.js",
          "punctuation.separator.key-value.js",
          "punctuation.terminator.statement.js"
        ],
        "settings": {
          "foreground": "#CCCAC2"
        }
      },
      {
        "scope": ["entity.name.type.class"],
        "settings": {
          "foreground": "#FFD173"
        }
      },
      {
        "scope": ["keyword.operator"],
        "settings": {
          "foreground": "#FFAD66"
        }
      }
    ]
  },

  "editor.semanticTokenColorCustomizations": {
    "enabled": true,
    "rules": {
      "variable.defaultLibrary": "#5ccfe6"
    }
  },
  "sonarlint.rules": {
    "javascript:S125": {
      "level": "off"
    }
  },
  "cSpell.userWords": ["Amol", "Madake"],
  "editor.fontLigatures": true
}

```
