# vscode-screencast-template

This template includes workspace settings that adapt VS
Code when recording a screencast. This repository is
inspired by
[this article](https://dev.to/5t3ph/how-i-set-up-vscode-for-recording-a-screencast-be7)
by [Stephanie Eckles](https://twitter.com/5t3ph).

Use this repository as template and create a new repo
for each screencast using this template.

| Setting                       | Value                  | Default  | Description                                                                                                    |
| :---------------------------- | :--------------------- | :------- | :------------------------------------------------------------------------------------------------------------- |
| editor.fontSize               | 14                     | 14       | Leave as default an rather change zoom level.                                                                  |
| editor.lineHeight             | 22                     | 0 (auto) | Increase spacing.                                                                                              |
| window.zoomLevel              | 1                      | 0        | Zoom everything, not just the editor font.                                                                     |
| editor.defaultFormatter       | esbenp.prettier-vscode | null     | Use Prettier to format code.                                                                                   |
| editor.formatOnSave           | true                   | false    | Format code with Prettier on save.                                                                             |
| editor.lineNumbers            | off                    | on       | Declutter appearance by removing line numbers.                                                                 |
| editor.quickSuggestionsDelay  | 1500                   | 10       | Delay suggestions to keep them out of the recording. If you need a suggestion, just wait and cut it out later. |
| editor.hover.enabled          | false                  | true     | Turn off hovers, which are confusing in a screencast.                                                          |
| breadcrumbs.enabled           | false                  | true     | Turn off breadcrumbs, which occupy precious screen real estate.                                                |
| workbench.activityBar.visible | false                  | true     | Turn off activity bar, which occupies precious screen real estate.                                             |
| workbench.statusBar.visible   | false                  | true     | Turn off status bar, which occupies precious screen real estate.                                               |

## Keyboard shortcuts

| Shortcut | Description                                    |
| :------- | :--------------------------------------------- |
| ⌘B       | Toogle sidebar (cannot be hidden in settings). |
