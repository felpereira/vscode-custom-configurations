# VSCODE Custom Configurations

```json
{
  "[json]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "[javascript]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "[prisma]": {
    "editor.defaultFormatter": "Prisma.prisma"
  },
  "apc.electron": {
    "frame": false,
    "stylesheet": {
      ".editor-actions": "display: none",
      ".monaco-list-row": "border-radius: 4px;",
      ".monaco-workbench .monaco-list:not(.element-focused):focus:before": "display: none;",
      ".nosidebar .inline-tabs-placeholder": "width: 75px",
      ".pane-body": "padding: 8px",
      ".pane-header": "padding: 0 8px",
      ".split-view-view:first-child .pane-header": "display: none !important;",
      ".title-label > h2": "display: none"
    },
    "titleBarStyle": "hiddenInset",
    "trafficLightPosition": {
      "x": 11,
      "y": 10
    }
  },
  "cSpell.enableFiletypes": [
    "!asciidoc",
    "!c",
    "!cpp",
    "!csharp",
    "!go",
    "!handlebars",
    "!haskell",
    "!jade",
    "!java",
    "!latex",
    "!php",
    "!pug",
    "!python",
    "!restructuredtext",
    "!rust",
    "!scala",
    "!scss"
  ],
  "cSpell.language": "en,pt-br",
  "cSpell.userWords": [
    "autofetch",
    "autofocus",
    "checkin",
    "Checkin",
    "datetimepicker",
    "esnext",
    "flowtype",
    "Funcionarios",
    "hookform",
    "icns",
    "monaco",
    "nosidebar",
    "precommit",
    "prepush",
    "secullum",
    "Secullum",
    "sonarlint",
    "stylesheet",
    "uglifyjs",
    "wysiwyg",
    "zxing"
  ],
  "editor.acceptSuggestionOnCommitCharacter": false,
  "editor.accessibilitySupport": "off",
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit"
  },
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.fontFamily": "JetBrainsMono Nerd Font",
  "editor.fontSize": 14,
  "editor.formatOnPaste": true,
  "editor.formatOnSave": true,
  "editor.hideCursorInOverviewRuler": true,
  "editor.lineHeight": 1.8,
  "editor.parameterHints.enabled": false,
  "editor.renderLineHighlight": "gutter",
  "editor.rulers": [
    80,
    120
  ],
  "editor.semanticHighlighting.enabled": false,
  "editor.suggestSelection": "first",
  "editor.tabSize": 2,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "emmet.syntaxProfiles": {
    "javascript": "jsx"
  },
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "graphql"
  ],
  "explorer.compactFolders": false,
  "explorer.confirmDelete": false,
  "explorer.confirmDragAndDrop": false,
  "explorer.fileNesting.enabled": true,
  "explorer.fileNesting.patterns": {
    ".env": ".env*",
    ".env.local": ".env*",
    "package.json": ".eslint*, prettier*, tsconfig*, vite*, pnpm-lock*, bun.lockb, nest*",
    "tailwind.config.js": "tailwind.config*, postcss.config*"
  },
  "explorer.sortOrder": "foldersNestsFiles",
  "extensions.ignoreRecommendations": true,
  "files.associations": {
    ".env.*": "dotenv",
    ".prettierrc": "json",
    "*.css": "css"
  },
  "files.autoGuessEncoding": true,
  "files.autoSave": "afterDelay",
  "files.exclude": {
    "**\/.DS_Store": true,
    "**\/.git": true,
    "**\/.hg": true,
    "**\/.svn": true,
    "**\/CVS": true,
    ".vscode": true
  },
  "git.enableSmartCommit": true,
  "git.openRepositoryInParentFolders": "always",
  "git.autofetch": true,
  "gitlens.codeLens.authors.enabled": false,
  "gitlens.codeLens.recentChange.enabled": false,
  "javascript.suggest.autoImports": true,
  "javascript.updateImportsOnFileMove.enabled": "always",
  // "security.workspace.trust.untrustedFiles": "newWindow",
  "security.promptForLocalFileProtocolHandling": false,
  "sonarlint.rules": {
    "java:S116": {
      "level": "off"
    },
    "javascript:S1105": {
      "level": "on"
    },
    "javascript:S126": {
      "level": "on"
    },
    "javascript:S131": {
      "level": "on"
    },
    "javascript:S1440": {
      "level": "on"
    },
    "javascript:S1535": {
      "level": "on"
    },
    "javascript:S1539": {
      "level": "on"
    },
    "javascript:S1821": {
      "level": "on"
    },
    "javascript:S2138": {
      "level": "on"
    },
    "javascript:S3513": {
      "level": "on"
    },
    "javascript:S3533": {
      "level": "on"
    },
    "javascript:S4139": {
      "level": "on"
    },
    "javascript:S4326": {
      "level": "on"
    }
  },
  "symbols.files.associations": {
    "*.e2e-spec.ts": "ts-test",
    "*.guard.ts": "typescript",
    "*.module.ts": "nest",
    "*.spec.ts": "ts-test",
    ".env.example": "gear",
    "vitest.config.e2e.ts": "vite"
  },
  "symbols.hidesExplorerArrows": false,
  "terminal.integrated.defaultProfile.osx": "fish",
  "terminal.integrated.env.osx": {
    "FIG_NEW_SESSION": "1"
  },
  "terminal.integrated.env.windows": {},
  "terminal.integrated.fontSize": 14,
  "terminal.integrated.fontFamily": "monospace",
  "terminal.integrated.gpuAcceleration": "off",
  "terminal.integrated.showExitAlert": false,
  "typescript.suggest.autoImports": true,
  "typescript.updateImportsOnFileMove.enabled": "always",
  "typescript.tsserver.log": "off",
  "update.showReleaseNotes": false,
  "window.openFoldersInNewWindow": "on",
  "window.restoreWindows": "preserve",
  "window.titleBarStyle": "custom",
  "workbench.activityBar.location": "top",
  "workbench.editor.empty.hint": "hidden",
  "workbench.editor.labelFormat": "default",
  "workbench.iconTheme": "vscode-icons",
  "workbench.productIconTheme": "fluent-icons",
  "workbench.startupEditor": "newUntitledFile",
  "window.systemColorTheme": "dark",
  "window.openWithoutArgumentsInNewWindow": "off",
  "security.workspace.trust.untrustedFiles": "open",
}
}
```
