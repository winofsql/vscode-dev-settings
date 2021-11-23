# vscode-dev-settings

2021/10/20 パブリックプレビュー

[記事( 窓の杜 )](https://forest.watch.impress.co.jp/docs/news/1360147.html)

<br>

![image](https://user-images.githubusercontent.com/1501327/142982754-89dd2453-d2e1-4bd6-86a0-d8f761bc994d.png)


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
    "terminal.integrated.fontSize": 16,
    "terminal.integrated.profiles.windows": {
        "PowerShell": {
            "source": "PowerShell",
            "icon": "terminal-powershell"
        },
        "Command Prompt": {
            "path": [
                "C:\\WINDOWS\\system32\\cmd.exe"
            ],
            "args": [],
            "icon": "terminal-cmd"
        },
        "Git Bash": {
            "source": "Git Bash"
        }
    },
    "files.associations": {
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
    "[jsonc]": {
        "editor.defaultFormatter": "vscode.json-language-features"
    },
    "[csv]": {
        "files.encoding": "shiftjis"
    },
    "[vbs]": {
        "files.encoding": "shiftjis"
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
