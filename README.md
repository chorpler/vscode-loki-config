# vscode-loki-config README

Syntax highlighting for Mayo Clinic's Swift (Loki) proteomics pipeline config files

## Features

- Syntax highlighting for Mayo Clinic's Swift (Loki) proteomics pipeline config files

## Requirements

- None

## Extension Settings

Suggested colors for adding to settings:

```json
    "editor.tokenColorCustomizations": {
        "textMateRules": [
            {
                "scope": "entity.name.section.lokiconfig",
                "settings":  {
                    "foreground": "#FFA657",
                    "fontStyle": ""
                }
            },
            {
                "scope": "entity.name.instance.lokiconfig",
                "settings":  {
                    "foreground": "#006dc6",
                    "fontStyle": ""
                }
            },
            {
                "scope": "comment.line.number-sign.lokiconfig",
                "settings":  {
                    "foreground": "#006609",
                    "fontStyle": ""
                }
            },
            {
                "scope": "variable.other.key-divider.lokiconfig",
                "settings":  {
                    "foreground": "#a00000",
                    "fontStyle": ""
                }
            },
            {
                "scope": "variable.other.key.lokiconfig",
                "settings":  {
                    "foreground": "#7EE787",
                    "fontStyle": "bold"
                }
            },
            {
                "scope": "variable.other.key-part2.lokiconfig",
                "settings":  {
                    "foreground": "#7EE787",
                    "fontStyle": ""
                }
            },
            {
                "scope": "variable.other.key-part3.lokiconfig",
                "settings":  {
                    "foreground": "#368b3d",
                    "fontStyle": ""
                }
            }
        ]
    }
```
Include if your extension adds any VS Code settings through the `contributes.configuration` extension point.

For example:

This extension contributes the following settings:

* `myExtension.enable`: Enable/disable this extension.
* `myExtension.thing`: Set to `blah` to do something.

## Known Issues

- Doesn't do deep parsing to highlight JSON objects

## Release Notes

- None

### 0.0.1

Initial test package

---

## Working with Markdown

You can author your README using Visual Studio Code. Here are some useful editor keyboard shortcuts:

* Split the editor (`Cmd+\` on macOS or `Ctrl+\` on Windows and Linux).
* Toggle preview (`Shift+Cmd+V` on macOS or `Shift+Ctrl+V` on Windows and Linux).
* Press `Ctrl+Space` (Windows, Linux, macOS) to see a list of Markdown snippets.

## For more information

* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

**Enjoy!**
