# vscode-rich-presence-icons

![N|Solid](https://i.imgur.com/MQc2Dsl.png)

This repository allows you to change the annoying icons for the Discord Rich Presence extension in Vscode to others.
My repository contains some languages ​​that change these icons

## Connection

In order to use these icons you do not need to download anything. It’s simply enough to register the config in settings.js in Vscode

```json
      "vscord.status.problems.text": "problems code",
    "vscord.ignore.workspacesText": "workspace text",
    "vscord.status.details.text.debugging": "debugging",
    "vscord.status.details.text.editing": "",
    "vscord.status.details.text.idle": "sleep user",
    "vscord.status.details.text.notInFile": "not file edit",
    "vscord.status.details.text.noWorkSpaceText": "no workspace",
    "vscord.status.details.text.viewing": "view file",
    "vscord.status.state.text.debugging": "debugging",
    "vscord.status.state.text.editing": "editing file",
    "vscord.status.state.text.idle": "idle file",
    "vscord.status.state.text.notInFile": "no in file edit",
    "vscord.status.state.text.noWorkspaceFound": "no worksapce",
    "vscord.status.state.text.viewing": "view code",
    "vscord.status.image.large.debugging.key": "path large img debugging",
    "vscord.status.image.large.debugging.text": "large img text debugging",
    "vscord.status.image.large.editing.key": "large img text",
    "vscord.status.image.large.editing.text": "large img text ",
    "vscord.status.image.small.editing.key": "small img edit",
```
config with all icons:

```json
    "vscord.status.image.large.debugging.key": "https://raw.githubusercontent.com/Markussia/icons-vscode-rich/main/DEBUG.png",
    "vscord.status.image.large.editing.key": "https://raw.githubusercontent.com/Markussia/icons-vscode-rich/main/{LANG}.png",
    "vscord.status.image.small.editing.key": "https://raw.githubusercontent.com/Markussia/icons-vscode-rich/main/large/large-{LANG}.png"
```


![N|Solid](https://i.imgur.com/LGK5gx3.png)
