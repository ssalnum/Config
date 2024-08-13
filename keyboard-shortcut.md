
// Place your key bindings in this file to override the defaults
[
    // NAVIGATION
    {
        "key": "ctrl+shift+a",
        "command": "workbench.action.terminal.focusNext",
        "when": "terminalFocus"
    },
    {
        "key": "ctrl+shift+b",
        "command": "workbench.action.terminal.focusPrevious",
        "when": "terminalFocus"
    },
    {
        "key": "ctrl+shift+j",
        "command": "workbench.action.togglePanel"
    },
    {
        "key": "ctrl+shift+n",
        "command": "workbench.action.terminal.new",
        "when": "terminalFocus"
    },
    {
        "key": "ctrl+shift+w",
        "command": "workbench.action.terminal.kill",
        "when": "terminalFocus"
    },
    // FILE TREE
    {
        "command": "workbench.action.toggleSidebarVisibility",
        "key": "ctrl+e"
    },
    {
        "key": "ctrl+e",
        "command": "workbench.files.action.focusFilesExplorer",
        "when": "editorTextFocus"
    },
    {
        "key": "n",
        "command": "explorer.newFile",
        "when": "filesExplorerFocus && !inputFocus"
    },
    {
        "key": "r",
        "command": "renameFile",
        "when": "filesExplorerFocus && !inputFocus"
    },
    {
        "key": "shift+n",
        "command": "explorer.newFolder",
        "when": "explorerViewletFocus"
    },
    {
        "key": "shift+n",
        "command": "workbench.action.newWindow",
        // && vim.mode != 'Insert' to prevent opening new window on insert mode
        "when": "!explorerViewletFocus && vim.mode != 'Insert'"
    },
    {
        "key": "d",
        "command": "deleteFile",
        "when": "filesExplorerFocus && !inputFocus"
    },
    // EXTRA
    {
        "key": "ctrl+z",
        "command": "workbench.action.toggleZenMode"
    }
]