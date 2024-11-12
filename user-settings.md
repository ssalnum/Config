{
  "window.zoomLevel": 0.6,
  "editor.minimap.enabled": false,
  "workbench.colorTheme": "Min Dark",
  "workbench.startupEditor": "none",
  "workbench.iconTheme": "symbols",
  "editor.fontFamily": "JetBrains Mono",
  "editor.fontSize": 16,
  "editor.lineHeight": 1.6,
  "editor.rulers": [80, 120],
  "editor.renderLineHighlight": "gutter",
  "editor.stickyScroll.enabled": false,
  "workbench.editor.labelFormat": "short",
  "explorer.compactFolders": false,
  "workbench.activityBar.location": "hidden",
  "editor.cursorBlinking": "smooth",
  "editor.cursorSmoothCaretAnimation": "on",
  "window.commandCenter": false,
  "workbench.layoutControl.enabled": false,
  "editor.hideCursorInOverviewRuler": true,
  "window.titleBarStyle": "native",
  "window.menuBarVisibility": "compact",
  "editor.smoothScrolling": true,
  "explorer.fileNesting.enabled": true,
  "explorer.fileNesting.patterns": {
    "tailwind.config.*": "tailwind.config*, postcss.config*"
  },
  "terminal.integrated.fontSize": 16,
  "terminal.integrated.fontFamily": "JetBrainsMono Nerd Font",
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit",
    "source.addMissingImports": "explicit"
  },
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact"
  ],
  "editor.lineNumbers": "relative",
  "workbench.sideBar.location": "right",
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "vim.leader": "<Space>",
  "vim.hlsearch": true,
  "vim.normalModeKeyBindingsNonRecursive": [
    // NAVIGATION
    // switch b/w buffers
    {
      "before": ["<S-h>"],
      "commands": [":bprevious"]
    },
    {
      "before": ["<S-l>"],
      "commands": [":bnext"]
    },
    // Navigation inserting a new line without entering insert mode
    {
      "before": ["leader", "o"],
      "after": ["o", "<Esc>"]
    },
    {
      "before": ["leader", "O"],
      "after": ["O", "<Esc>"]
    },
    // splits
    {
      "before": ["leader", "v"],
      "commands": [":vsplit"]
    },
    {
      "before": ["leader", "s"],
      "commands": [":split"]
    },
    // panes
    {
      "before": ["leader", "h"],
      "commands": ["workbench.action.focusLeftGroup"]
    },
    {
      "before": ["leader", "j"],
      "commands": ["workbench.action.focusBelowGroup"]
    },
    {
      "before": ["leader", "k"],
      "commands": ["workbench.action.focusAboveGroup"]
    },
    {
      "before": ["leader", "l"],
      "commands": ["workbench.action.focusRightGroup"]
    },
    {
      "before": ["leader", "f"],
      "commands": ["workbench.action.quickOpen"]
    },
    // toggle comment selection
    {
      "before": ["leader", "c"],
      "commands": ["editor.action.commentLine"]
    },
    // toggle comment selection
    {
      "before": ["leader", "w"],
      "commands": ["workbench.action.closeActiveEditor"]
    },
    {
      "before": ["leader", "n", "e"],
      "commands": "workbench.explorer.fileView.focus"
    }
  ],
  "symbols.hidesExplorerArrows": false,
  "livePreview.previewDebounceDelay": 100,
  "dart.flutterSdkPath": "C:\\flutter",
  "[dart]": {
    "editor.codeActionsOnSave": {
      "quickfix.insertSemicolon": "always"
    },
    "editor.formatOnSave": true,
    "editor.defaultFormatter": "Dart-Code.dart-code"
  },
  "git.autofetch": true,
  "dart.debugExternalPackageLibraries": true,
  "dart.debugSdkLibraries": false,
  "liveshare.languages.allowGuestCommandControl": true
}
