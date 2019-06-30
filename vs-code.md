#### keys

```js
// Place your key bindings in this file to overwrite the defaults
[
    {
        "key": "alt+shift+z",
        "command": "editor.emmet.action.wrapWithAbbreviation",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+alt+down",
        "command": "editor.action.copyLinesDownAction",
        "when": "editorFocus"
    },
    {
        "key": "ctrl+shift+d",
        "command": "-editor.action.copyLinesDownAction",
        "when": "editorFocus"
    }, 
    {
      "key": "ctrl+`",
      "command": "workbench.action.terminal.focus"
    },
    {
      "key": "ctrl+`",
      "command": "workbench.action.focusActiveEditorGroup",
      "when": "terminalFocus"
    }
  ]
```

#### settings.json

```js
{
    "editor.multiCursorModifier": "ctrlCmd",
    "editor.snippetSuggestions": "top",
    "editor.formatOnPaste": true,
    "html.format.wrapLineLength": 130,
    "html.format.enable": false,
    "editor.tabSize": 2,
    "[html]": {
        "editor.tabSize": 2    
},
"editor.detectIndentation": false,
"editor.minimap.enabled": false,
"window.zoomLevel": 1,
"editor.suggestSelection": "first",
"vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
"vsicons.dontShowNewVersionMessage": true
}
