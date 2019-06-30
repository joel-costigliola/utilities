=== keys

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
