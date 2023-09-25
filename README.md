# vscode-rich-presence-icons

![N|Solid](https://i.imgur.com/MQc2Dsl.png)

This repository allows you to change the annoying icons for the Discord Rich Presence extension in Vscode to others.
My repository contains some languages ​​that change these icons

## Connection

In order to use these icons you do not need to download anything. It’s simply enough to register the config in config.js in Vscode

```json
    "vscord.status.problems.text": "problems code",
    "vscord.ignore.workspacesText": "workspace text",
    "vscord.status.details.text.debugging": "debugging",
    "vscord.status.details.text.editing": "",
    "vscord.status.details.text.idle": "Сплю не трогайте",
    "vscord.status.details.text.notInFile": "Сплю не трогайте",
    "vscord.status.details.text.noWorkSpaceText": "Не воркаю, потому что могу",
    "vscord.status.details.text.viewing": "в {workspace} {problems}",
    "vscord.status.state.text.debugging": "Проверяет гоавнокод: {workspace}",
    "vscord.status.state.text.editing": "Воркаю в {file_name}{file_extension}:{current_line}:{current_column}",
    "vscord.status.state.text.idle": "кушать хочу",
    "vscord.status.state.text.notInFile": "я типо отдыхаю потому что  могу",
    "vscord.status.state.text.noWorkspaceFound": "Не для кого работать",
    "vscord.status.state.text.viewing": "Смотрю что высрал {file_name}{file_extension}",
    "vscord.status.image.large.debugging.key": "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRGjvL9DxTxI1C5RlQCPkpKfM0AjSnGEU8YfA&usqp=CAU",
    "vscord.status.image.large.debugging.text": "Дебажу это срань {LANG}",
    "vscord.status.image.large.editing.key": "https://cdn.dribbble.com/users/219482/screenshots/14676444/media/28fa0b64b0454de0d0664e364e4f95fc.gif",
    "vscord.status.image.large.editing.text": "Хуярю как не в себя в {LANG}",
    "vscord.status.image.small.editing.key": "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRNJ4-0BXxFmddUdqTqqGV0cf1ptXUHko3PeQ&usqp=CAU",
    "vscord.status.buttons.button1.active.enabled": true,
    "vscord.status.buttons.button1.active.label": "Мой гитхаб",
    "vscord.status.buttons.button1.active.url": "https://github.com/markussia",
    "vscord.status.buttons.button1.git.active.label": "открыть облако с кодом",
    "vscord.status.buttons.button1.idle.enabled": true,
    "vscord.behaviour.suppressNotifications": true,
    "vscord.behavoiur.prioritizeLanguagesOverExtensions": true
```
