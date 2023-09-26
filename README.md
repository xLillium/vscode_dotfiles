```
[
    // =====================
    // = TOGGLE VIM MODE 
    // =====================
    {
        "key": "oem_7",
        "command": "toggleVim",
        "comment": "Toggle Vim Mode with ²"
    },

    // =====================
    // = APPEARANCE
    // =====================
    {
        "key": "ctrl+oem_plus",
        "command": "editor.action.fontZoomIn",
        "comment": "Zoom in text"
    },
    {
        "key": "ctrl+6",
        "command": "editor.action.fontZoomOut",
        "comment": "Zoom out text"
    },
    {
        "key": "ctrl+shift+6",
        "command": "workbench.action.zoomOut",
        "comment": "Zoom out workspace"
    },

    // =====================
    // = TERMINAL
    // =====================
    {
        "key": "ctrl+shift+j",
        "command": "workbench.action.togglePanel",
        "comment": "Toggle panel visibility"
    },
    {
        "key": "ctrl+shift+c",
        "command": "workbench.action.terminal.new",
        "when": "terminalFocus",
        "comment": "Create new terminal"
    },
    {
        "key": "ctrl+shift+x",
        "command": "workbench.action.terminal.kill",
        "when": "terminalFocus",
        "comment": "Kill active terminal"
    },
    {
        "key": "ctrl+shift+n",
        "command": "workbench.action.terminal.focusNext",
        "when": "terminalFocus",
        "comment": "Focus next terminal"
    },
    {
        "key": "ctrl+shift+p",
        "command": "workbench.action.terminal.focusPrevious",
        "when": "terminalFocus",
        "comment": "Focus previous terminal"
    },

    // =====================
    // = FILE TREE
    // =====================
    {
        "key": "ctrl+shift+c",
        "command": "workbench.action.toggleSidebarVisibility",
        "when": "!terminalFocus",
        "comment": "Toggle sidebar visibility"
    },
    {
        "key": "ctrl+shift+e",
        "command": "workbench.files.action.focusFilesExplorer",
        "when": "editorTextFocus",
        "comment": "Focus Files Explorer"
    },
    {
        "key": "ctrl+shift+e",
        "command": "workbench.action.toggleSidebarVisibility",
        "when": "filesExplorerFocus && !inputFocus",
        "comment": "Toggle sidebar visibility when in Files Explorer and no input focus"
    },
    {
        "key": "n",
        "command": "explorer.newFile",
        "when": "filesExplorerFocus && !inputFocus",
        "comment": "Create new file in Files Explorer"
    },
    {
        "key": "shift+n",
        "command": "explorer.newFolder",
        "when": "explorerViewletFocus",
        "comment": "Create new folder in Files Explorer"
    },
    {
        "key": "r",
        "command": "renameFile",
        "when": "filesExplorerFocus && !inputFocus",
        "comment": "Rename file in Files Explorer"
    },
    {
        "key": "d",
        "command": "deleteFile",
        "when": "filesExplorerFocus && !inputFocus",
        "comment": "Delete file in Files Explorer"
    },

    // =====================
    // = SEARCH
    // =====================
    {
        "key": "ctrl+shift+s",
        "command": "workbench.view.search.focus",
        "when": "editorTextFocus",
        "comment": "Focus search"
    },
    {
        "key": "ctrl+shift+s",
        "command": "workbench.action.toggleSidebarVisibility",
        "when": "focusedView == workbench.view.search",
        "comment": "Toggle sidebar visibility when in search view"
    },

    // =====================
    // = GIT
    // =====================
    {
        "key": "ctrl+shift+g",
        "command": "workbench.view.scm",
        "when": "workbench.scm.active && !gitlens:disabled && config.gitlens.keymap == 'chorded'",
        "comment": "Open Source Control Management view"
    },
    {
        "key": "ctrl+shift+g",
        "command": "workbench.action.toggleSidebarVisibility",
        "when": "focusedView == workbench.scm",
        "comment": "Toggle sidebar visibility when in Source Control Management view"
    },

    // =====================
    // = EXTRA
    // =====================
    {
        "key": "ctrl+w",
        "command": "workbench.action.toggleZenMode",
        "comment": "Toggle Zen Mode"
    }
]
```
