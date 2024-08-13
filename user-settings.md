
{
  "window.zoomLevel": 0.8,
  "editor.minimap.enabled": false,
  "workbench.colorTheme": "Min Dark",
  "workbench.startupEditor": "none",
  "workbench.iconTheme": "symbols",
  "editor.fontFamily": "JetBrains Mono",
  "editor.lineHeight": 1.6,
  "editor.rulers": [80, 120],
  "editor.renderLineHighlight": "gutter",
  "editor.stickyScroll.enabled": false,
  "liveServer.settings.useLocalIp": true,
  "workbench.editor.labelFormat": "short",
  "explorer.compactFolders": false,
  "workbench.activityBar.location": "hidden",
  "editor.cursorBlinking": "smooth",
  "editor.cursorSmoothCaretAnimation": "on",
  "window.commandCenter": false,
  "workbench.layoutControl.enabled": false,
  "editor.hideCursorInOverviewRuler": true,
  "window.titleBarStyle": "native",
  "apc.electron": {
    "titleBarStyle": "hidden",
    "titleBarOverlay": {
      "color": "#1a1a1a",
      "symbolColor": "#c5c5c5",
      "height": 43
    },
    "opacity": 1,
    "vibrancy": "dark",
    "frame": false
  },
  "apc.header": {
    "height": 36
  },
  "apc.listRow": {
    "height": 24
  },
  "apc.font.family": "Inter",
  "apc.stylesheet": {
    ".titlebar-left > a": "display: none",
    ".monaco-workbench .part>.composite.header-or-footer, .monaco-workbench .part>.composite.title": "justify-content: start",
    ".frameless-title-bar:not(.statusbar-top) .monaco-workbench:not(.fullscreen) .auxiliarybar .inline-auxiliarybar-placeholder, .inline-title-bar:not(.statusbar-top) .monaco-workbench:not(.fullscreen) .auxiliarybar .inline-auxiliarybar-placeholder, .frameless-title-bar:not(.activitybar-top):not(.statusbar-top) .monaco-workbench:not(.fullscreen) .sidebar .composite.title .title-label, .inline-title-bar:not(.activitybar-top):not(.statusbar-top) .monaco-workbench:not(.fullscreen) .sidebar .composite.title .title-label": "display: none",
    ".editor-actions": "display: none",
    ".nosidebar .inline-tabs-placeholder": "width: 75px",
    ".pane-header": "padding: 0 8px",
    ".pane-body": "padding: 8px 6px 8px 4px",
    ".split-view-view:first-child .pane-header": "display: none !important;",
    ".monaco-list-row": "border-radius: 4px;",
    ".monaco-workbench .monaco-list:not(.element-focused):focus:before": "display: none;"
  },
  "window.menuBarVisibility": "compact",
  "editor.smoothScrolling": true,
  "explorer.fileNesting.enabled": true,
  "symbols.hidesExplorerArrows": false,
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
  "editor.scrollbar.vertical": "hidden",
  "editor.scrollbar.horizontal": "hidden",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
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
  ]
}