# vs-code-theme- 



{
  "workbench.iconTheme": "material-icon-theme",
  "liveServer.settings.donotVerifyTags": true,
  "liveServer.settings.CustomBrowser": "chrome:PrivateMode",
  "liveServer.settings.port": 0,
  "liveServer.settings.donotShowInfoMsg": true,
  "explorer.confirmDelete": false,
  "explorer.confirmDragAndDrop": false,
  "json.schemas": [],
  "diffEditor.ignoreTrimWhitespace": true,
  "git.autofetch": true,
  "git.confirmSync": false,
  "git.suggestSmartCommit": false,
  "security.workspace.trust.untrustedFiles": "open",

  /* ---------- CURSOR DESIGN ---------- */
  "editor.cursorBlinking": "expand",
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.cursorSurroundingLines": 8,
  "editor.cursorWidth": 2,

  /* ---------- FONT & CODE LOOK ---------- */
  "editor.fontFamily": "JetBrains Mono, Fira Code, Consolas",
  "editor.fontSize": 14,
  "editor.fontLigatures": true,
  "editor.lineHeight": 22,

  /* ---------- EDITOR CLEAN DESIGN ---------- */
  "editor.minimap.enabled": true,
  "editor.minimap.renderCharacters": false,
  "editor.scrollbar.vertical": "hidden",
  "editor.scrollbar.horizontal": "hidden",
  "editor.renderLineHighlight": "gutter",
  "editor.bracketPairColorization.enabled": true,
  "editor.smoothScrolling": true,

  /* ---------- DEEP BLUR EFFECT ---------- */
  "window.titleBarStyle": "custom",
  "window.systemColorTheme": "dark",
  "window.autoDetectColorScheme": false,
  "workbench.sideBar.location": "left",
  "apc.electron": {
    "frame": false,
    "transparent": true,
    "vibrancy": "ultra-dark",
    "backgroundColor": "rgba(0,0,0,0)"
  },
  "apc.stylesheet": {
    "body": "backdrop-filter: blur(20px) !important;",
    ".monaco-workbench": "background: rgba(10, 10, 15, 0.7) !important;",
    ".editor-container": "backdrop-filter: blur(15px) !important;",
    ".sidebar": "backdrop-filter: blur(20px) !important; background: rgba(16, 16, 30, 0.6) !important;",
    ".activitybar": "backdrop-filter: blur(25px) !important; background: rgba(16, 16, 30, 0.5) !important;"
  },

  /* ---------- COLOR CUSTOM (DEEP DARK + BLUR + RIGHT-CLICK + SEARCH) ---------- */
  "workbench.colorCustomizations": {
    "editor.background": "#0A0A0F",
    "editor.foreground": "#D4D4D4",
    "editorCursor.foreground": "#FF9E64",
    "editorCursor.background": "#FF9E64",
    "editorLineNumber.foreground": "#3D4556",
    "editorLineNumber.activeForeground": "#FF9E64",
    "editor.selectionBackground": "#2A3F5F80",
    "editor.selectionHighlightBackground": "#2E3440",
    "editorBracketMatch.background": "#1E2030",
    "editorBracketMatch.border": "#FF9E64",

    /* Right-click menu */
    "menu.background": "#12121A",
    "menu.foreground": "#E4E4E7",
    "menu.selectionBackground": "#1F2937",
    "menu.selectionForeground": "#FF9E64",
    "menu.separatorBackground": "#2A2A3F",

    /* Search / Find widget */
    "editorWidget.background": "#12121A",
    "editorWidget.foreground": "#E4E4E7",
    "editorWidget.border": "#FF9E64",
    "editorWidget.resizeBorder": "#FF9E64",

    /* Input fields / search bar */
    "input.background": "#12121A",
    "input.foreground": "#E4E4E7",
    "input.border": "#FF9E64",
    "inputOption.activeBackground": "#1F2937",

    /* Sidebar, ActivityBar, Tabs, StatusBar */
    "sideBar.background": "#0D0D12",
    "sideBar.foreground": "#A0A8B7",
    "sideBarSectionHeader.background": "#0D0D12",
    "activityBar.background": "#08080C",
    "activityBar.foreground": "#6B9FE8",
    "activityBar.inactiveForeground": "#4A5568",
    "statusBar.background": "#0A0A0F",
    "statusBar.foreground": "#6B9FE8",
    "statusBar.noFolderBackground": "#0A0A0F",
    "titleBar.activeBackground": "#0A0A0F",
    "titleBar.activeForeground": "#B4BFCE",
    "titleBar.inactiveBackground": "#08080C",
    "titleBar.inactiveForeground": "#4A5568",
    "titleBar.border": "#00000000",
    "tab.activeBackground": "#12121A",
    "tab.inactiveBackground": "#0A0A0F",
    "tab.activeForeground": "#E4E4E7",
    "tab.inactiveForeground": "#5A5F6F",
    "tab.border": "#00000000",
    "tab.activeBorder": "#FF9E64",
    "tab.activeBorderTop": "#00000000",
    "panel.background": "#0D0D12",
    "panel.border": "#1A1A24",
    "panelTitle.activeBorder": "#FF9E64",
    "terminal.background": "#0A0A0F",
    "terminal.foreground": "#C8D0DF",
    "editorGroupHeader.tabsBackground": "#08080C",
    "dropdown.background": "#12121A",
    "list.hoverBackground": "#1A1A24",
    "list.activeSelectionBackground": "#1F2937",
    "list.inactiveSelectionBackground": "#16161E"
  },

  /* ---------- FORMATTERS ---------- */
  "[html]": { "editor.defaultFormatter": "vscode.html-language-features" },
  "[javascript]": { "editor.defaultFormatter": "esbenp.prettier-vscode" },
  "[javascriptreact]": { "editor.defaultFormatter": "esbenp.prettier-vscode" },
  "javascript.updateImportsOnFileMove.enabled": "always",

  /* ---------- UI ---------- */
  "terminal.integrated.gpuAcceleration": "auto",
  "breadcrumbs.enabled": false,
  "workbench.startupEditor": "none",
  "workbench.editor.tabSizing": "shrink",
  "workbench.editorAssociations": {
    "*.copilotmd": "vscode.markdown.preview.editor",
    "*.js": "default"
  },
  "chat.instructionsFilesLocations": {
    ".github/instructions": true,
    "C:\\Users\\user\\AppData\\Local\\Temp\\postman-collections-post-response.instructions.md": true,
    "C:\\Users\\user\\AppData\\Local\\Temp\\postman-collections-pre-request.instructions.md": true,
    "C:\\Users\\user\\AppData\\Local\\Temp\\postman-folder-post-response.instructions.md": true,
    "C:\\Users\\user\\AppData\\Local\\Temp\\postman-folder-pre-request.instructions.md": true,
    "C:\\Users\\user\\AppData\\Local\\Temp\\postman-http-request-post-response.instructions.md": true,
    "C:\\Users\\user\\AppData\\Local\\Temp\\postman-http-request-pre-request.instructions.md": true
  },
  "workbench.colorTheme": "Tokyo Night"
}
