# vscode-dev-settings

2021/10/20 パブリックプレビュー

[記事( 窓の杜 )](https://forest.watch.impress.co.jp/docs/news/1360147.html)

<br>

![image](https://user-images.githubusercontent.com/1501327/142982754-89dd2453-d2e1-4bd6-86a0-d8f761bc994d.png)

<br>

```json
{
    "editor.fontSize": 16,
    "editor.suggestSelection": "first",
    "editor.detectIndentation": false,
    "editor.renderWhitespace": "boundary",
    "workbench.startupEditor": "newUntitledFile",
    "files.exclude": {
        "**/.classpath": true,
        "**/.project": true,
        "**/.settings": true,
        "**/.factorypath": true
    },
    "files.associations": {
        "*.csv": "bat",
        "*.jsp": "java",
        "*.htm": "html",
        "*.hta": "html",
        "*.xlsx": "excel"
    },
    "[javascript]": {
        "editor.defaultFormatter": "vscode.typescript-language-features"
    },
    "[html]": {
        "editor.defaultFormatter": "vscode.html-language-features"
    },
    "[bat]": {
        "files.encoding": "shiftjis"
    },
    "[powershell]": {
        "files.encoding": "shiftjis"
    },
    "workbench.editor.enablePreview": false,
    "editor.mouseWheelZoom": true,
    "workbench.iconTheme": "material-icon-theme",
    "material-icon-theme.folders.color": "#bfc553",
    "material-icon-theme.opacity": 0.8,
    "material-icon-theme.showWelcomeMessage": false,
    "files.autoSave": "afterDelay"
}
```

<br>

![image](https://user-images.githubusercontent.com/1501327/143179438-c3f1d1bc-c655-4fde-ae31-a43ba95ed884.png)

<br>
ショートカットキーの定義参照
```
workbench.action.openGlobalKeybindingsFile
```

```json
[
    {
        "key": "ctrl+f1",
        "command": "workbench.action.closeFolder",
        "when": "emptyWorkspaceSupport && workbenchState != 'empty'"
    },
    {
        "key": "shift+alt+k",
        "command": "workbench.action.openGlobalKeybindingsFile"
    },
    {
        "key": "ctrl+shift+delete",
        "command": "editor.action.trimTrailingWhitespace",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+f7",
        "command": "editor.action.transformToUppercase"
    },
    {
        "key": "ctrl+f6",
        "command": "editor.action.transformToLowercase"
    },
    {
        "key": "shift+alt+pausebreak",
        "command": "editor.action.formatSelection",
        "when": "editorHasDocumentSelectionFormattingProvider && editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+shift+numpad_divide",
        "command": "workbench.action.splitEditorInGroup",
        "when": "activeEditorCanSplitInGroup"
    },
    {
        "key": "ctrl+shift+numpad_divide",
        "command": "workbench.action.joinEditorInGroup",
        "when": "sideBySideEditorActive"
    },
    {
        "key": "ctrl+f2",
        "command": "workbench.action.closeAllEditors"
    },
    {
        "key": "ctrl+shift+numpad_subtract",
        "command": "workbench.action.positionPanelRight"
    },
    {
        "key": "ctrl+shift+numpad_add",
        "command": "workbench.action.positionPanelBottom"
    },
    {
        "key": "shift+alt+w",
        "command": "workbench.action.openWorkspaceSettingsFile"
    }
]
```