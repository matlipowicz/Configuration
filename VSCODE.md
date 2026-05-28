# VSCode configuration

## User Profile Settings

```
{
  // THEME & FONT
  "workbench.colorCustomizations": {
    "[Tokyo Night]": {
      "breadcrumb.foreground": "#696d87",
      "breadcrumb.focusForeground": "#959cbd",
      "breadcrumb.activeSelectionForeground": "#959cbd",
      "activityBar.foreground": "#959cbd",
      "activityBar.inactiveForeground": "#5c607a",
      "gitDecoration.ignoredResourceForeground": "#696d87",
      "editorLineNumber.foreground": "#5c607a",
      "editorLineNumber.activeForeground": "#959cbd",
      "terminal.selectionBackground": "#58ffb1",
    },
  },
  "terminal.integrated.fontFamily": "MesloLGS NF",
  "workbench.colorTheme": "Tokyo Night",
  "workbench.iconTheme": "vscode-great-icons",
  "explorer.confirmDragAndDrop": false,
  "editor.fontFamily": "JetBrains Mono",
  "editor.fontSize": 14,
  "editor.fontWeight": "400",
  "editor.fontLigatures": true,
  "workbench.sideBar.location": "right",
  //FORMATTING
  "prettier.tabWidth": 2,
  "prettier.singleQuote": true,
  "prettier.printWidth": 150,
  "editor.formatOnSave": true,
  "editor.codeActionsOnSave": {
    "source.organizeImports": "never",
    "source.fixAll.eslint": "explicit",
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
  },
  "workbench.tree.enableStickyScroll": false,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.minimap.enabled": false,
  "editor.cursorBlinking": "expand",
  "editor.wordWrap": "on",
  "terminal.integrated.defaultProfile.osx": "zsh",
  "terminal.integrated.scrollback": 1000000,
  "typescript.updateImportsOnFileMove.enabled": "always",
  "window.newWindowDimensions": "maximized",
  "eslint.workingDirectories": ["frontend", "backend"],
  "nxConsole.showNodeVersionOnStartup": false,
  "liveshare.accessibility.soundsEnabled": false,
  "redhat.telemetry.enabled": true,
  "editor.suggest.showStatusBar": true,
  "github.copilot.nextEditSuggestions.enabled": false,
  "gitlens.ai.model": "vscode",
  "gitlens.ai.vscode.model": "copilot:gpt-4",
  "docker.extension.enableComposeLanguageServer": false,
  "chat.instructionsFilesLocations": {
    ".github/instructions": true,
    ".claude/rules": true,
    "~/.copilot/instructions": true,
    "~/.claude/rules": true,
    "/var/folders/pb/np2wyb4n51q_rjgkbh039khr0000gp/T/postman-http-request-post-response.instructions.md": true,
    "/var/folders/pb/np2wyb4n51q_rjgkbh039khr0000gp/T/postman-http-request-pre-request.instructions.md": true,
    "/var/folders/pb/np2wyb4n51q_rjgkbh039khr0000gp/T/postman-collections-post-response.instructions.md": true,
    "/var/folders/pb/np2wyb4n51q_rjgkbh039khr0000gp/T/postman-collections-pre-request.instructions.md": true,
    "/var/folders/pb/np2wyb4n51q_rjgkbh039khr0000gp/T/postman-folder-post-response.instructions.md": true,
    "/var/folders/pb/np2wyb4n51q_rjgkbh039khr0000gp/T/postman-folder-pre-request.instructions.md": true,
  },
  "[dockercompose]": {
    "editor.insertSpaces": true,
    "editor.tabSize": 2,
    "editor.autoIndent": "advanced",
    "editor.quickSuggestions": {
      "other": true,
      "comments": false,
      "strings": true,
    },
    "editor.defaultFormatter": "redhat.vscode-yaml",
  },
  "[github-actions-workflow]": {
    "editor.defaultFormatter": "redhat.vscode-yaml",
  },
  "workbench.secondarySideBar.defaultVisibility": "hidden",
  "files.watcherExclude": {
    "**/node_modules/**": true,
    "**/.next/**": true,
    "**/dist/**": true,
    "**/coverage/**": true,
    "**/.turbo/**": true,
    "**/.nx/cache/**": true,
  },
  "search.exclude": {
    "**/node_modules/**": true,
    "**/.next/**": true,
    "**/dist/**": true,
    "**/coverage/**": true,
    "**/.turbo/**": true,
    "**/.nx/cache/**": true,
  },
  "search.followSymlinks": false,
  "postman.mcp.notifications.postmanMCP": false,
  "terminal.integrated.persistentSessionScrollback": 1000000,

  // Extensions
  "jestrunner.jestCommand": "pnpm jest",
  "gitlens.views.fileHistory.mode": "contributors",
  "workbench.editor.centeredLayoutAutoResize": false,
  "workbench.editor.customLabels.enabled": false,
  "workbench.editor.closeOnFileDelete": true,
  "chat.viewSessions.orientation": "stacked",
  "claudeCode.preferredLocation": "panel",
}


```

## List of extensions

```
aaron-bond.better-comments
avetis.tokyo-night
adpyke.codesnap
bradlc.vscode-tailwindcss
bruceyuhb.hsl-preview
dbaeumer.vscode-eslint
dionannd.tokyo-night-ported-nvim
dsznajder.es7-react-js-snippets
eamodio.gitlens
ecmel.vscode-html-css
emmanuelbeziat.vscode-great-icons
enkia.tokyo-night
esbenp.prettier-vscode
firefox-devtools.vscode-firefox-debug
firsttris.vscode-jest-runner
formulahendry.auto-rename-tag
formulahendry.code-runner
github.copilot
github.copilot-chat
github.vscode-github-actions
mgmcdermott.vscode-language-babel
mikestead.dotenv
ms-azuretools.vscode-docker
ms-vscode-remote.remote-containers
ms-vsliveshare.vsliveshare
naumovs.color-highlight
redhat.vscode-yaml
ritwickdey.liveserver
simonsiefke.svg-preview
steoates.autoimport
streetsidesoftware.code-spell-checker
xabikos.javascriptsnippets
yoavbls.pretty-ts-errors
yzhang.markdown-all-in-one
```
