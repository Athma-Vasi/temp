{
  "deno.inlayHints.functionLikeReturnTypes.enabled": true,
  "deno.inlayHints.variableTypes.enabled": true,
  "deno.inlayHints.propertyDeclarationTypes.enabled": true,
  "deno.suggest.completeFunctionCalls": true,
  "editor.tabSize": 2,
  "editor.bracketPairColorization.enabled": true,
  "editor.bracketPairColorization.independentColorPoolPerBracketType": true,
  "editor.guides.bracketPairs": true,
  "editor.fontFamily": "'Iosevka Extended','Droid Sans Mono', 'monospace', monospace",
  "editor.fontSize": 24,
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.inlineSuggest.enabled": true,
  "editor.wordWrap": "on",
  "editor.fontLigatures": true,
  "explorer.confirmDragAndDrop": false,
  "fiveServer.browser": ["microsoft-edge-beta"],
  "files.autoSave": "onFocusChange",
  "juliaFormatter.indent": 2,
  "prettier.singleQuote": true,
  "terminal.integrated.fontSize": 19,
  "terminal.integrated.defaultProfile.linux": "zsh",
  "window.zoomLevel": -2,
  "workbench.activityBar.visible": false,
  "workbench.colorTheme": "Atom One Light",
  "terminal.integrated.commandsToSkipShell": ["language-julia.interrupt"],
  "julia.symbolCacheDownload": true,
  "julia.enableTelemetry": false,
  "totalTypeScript.hiddenTips": [
    "ts-object-type",
    "union-type",
    "basic-types",
    "passing-generics-to-types",
    "null-keyword",
    "type-alias-declaration",
    "array-type",
    "typing-function-parameters",
    "tuple-type",
    "keyof"
  ],
  "totalTypeScript.hideAllTips": false,
  "totalTypeScript.hideBasicTips": true,

  "tailwindCSS.includeLanguages": {
    "typescript": "javascript", // if you are using typescript
    "typescriptreact": "javascript" // if you are using typescript with react
  },
  "editor.quickSuggestions": {
    "strings": true // forces VS Code to trigger completions when editing "string" content
  },
  "tailwindCSS.experimental.classRegex": [
    "tw`([^`]*)", // tw`...`
    "tw\\.[^`]+`([^`]*)`", // tw.xxx<xxx>`...`
    "tw\\(.*?\\).*?`([^`]*)" // tw(Component)<xxx>`...`
  ]
}
