# Visual Studio Code Settings

## Extensions

- Bookmarks

- DotENV

- Dracula Official / Om Theme (A Dark Dracula Theme)

- Material Icon Theme

- WSL

- Color Highlight

- EditorConfig for VS Code

- ESLint

- GitLens

- Live Server

- Prettier - Code formatter

- vscode-styled-components

- Docker

- Code Runner

- GraphQL Prisma

- Markdownlint

## Settings

```json
{
 // Workbench
 "workbench.colorTheme": "OM Theme (No Italic)",
 "workbench.iconTheme": "material-icon-theme",
 "material-icon-theme.hidesExplorerArrows": true,
  "material-icon-theme.folders.color": "#6273a6",
 "workbench.sideBar.location": "right",

 // Explorer
 "explorer.compactFolders": false,
  "explorer.confirmDelete": true,

 // Editor and breadcrumbs
 "breadcrumbs.enabled": true,
 "editor.renderLineHighlight": "gutter",
 "editor.parameterHints.enabled": false,
 "editor.rulers": [ 80, 120 ],
 "editor.lineHeight": 24,
 "editor.fontSize": 20,
 "editor.tabSize": 2,
 "editor.formatOnSave": true,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
    "source.fixAll": true
  },

 // Files and search
 "files.defaultLanguage": "{activeEditorLanguage}",
  "files.exclude": {
    "USE_GITIGNORE": true
  },
  "search.exclude": {
    "**/node_modules": true,
    "**/bower_components": true,
    "**/coverage": true,
    "**/dist": true,
    "**/build": true,
    "**/.build": true,
    "**/.gh-pages": true
  },

  // Code runner
  "code-runner.clearPreviousOutput": true,
  "code-runner.ignoreSelection": true,
  "code-runner.saveFileBeforeRun": true,
  "code-runner.runInTerminal": true,
  "code-runner.preserveFocus": false,
  "code-runner.executorMap": {
   "typescript": "npx ts-node --files --transpile-only"
  },
 
 // Terminal
 "terminal.integrated.fontSize": 16,
}
```
