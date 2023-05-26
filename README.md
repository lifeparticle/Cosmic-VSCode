# 1. Extensions

| Category         | Extension                                                                                                            |
| ---------------- | -------------------------------------------------------------------------------------------------------------------- |
| **Code Quality** | [Prettier-vscode](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)                        |
|                  | [Eslint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)                                 |
|                  | [Stylelint](https://marketplace.visualstudio.com/items?itemName=stylelint.vscode-stylelint)                          |
|                  | [SonarLint](https://marketplace.visualstudio.com/items?itemName=SonarSource.sonarlint-vscode)                        |
| **Debug**        | [Console-ninja](https://marketplace.visualstudio.com/items?itemName=WallabyJs.console-ninja)                         |
|                  | [Errorlens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)                                |
| **Editor**       | [Material-icon-theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)                 |
| **Automation**   | [Auto-rename-tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)                 |
|                  | [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)                                 |
| **Others**       | [Vscode-docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)                     |
|                  | [Quokka-vscode](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode)                         |
|                  | [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced) |
|                  | [GitHub Actions](https://marketplace.visualstudio.com/items?itemName=github.vscode-github-actions)                   |
|                  | [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)                             |

```
1. Open preview to the Side: ctrl + k  v (Windows) or cmd + k  v (Mac)
2. Open preview: ctrl + shift + v (Windows) or cmd + shift + v (Mac)
```
- [Turbo Console Log](https://marketplace.visualstudio.com/items?itemName=ChakrounAnas.turbo-console-log)
```
1. Select the variable you want to debug
2. ctrl + alt + L (Windows) or ctrl + option + L (Mac)
 ```
 - [SonarLint](https://marketplace.visualstudio.com/items?itemName=SonarSource.sonarlint-vscode)
 ```
 1. Issues are highlighted in your code
 2. Issues are listed in the 'Problems' panel.
 ```

# 2. User and workspace settings

<b>User settings:</b> Apply settings globally

File location:

`$HOME/Library/Application Support/Code/User/settings.json`

Or 
- `ctrl + shift + p` -> Windows `cmd + shift + p` -> macOS
- Type `open settings`
- Select `Open Settings (JSON)`

```
{
	"editor.fontFamily": "DroidSansMono Nerd Font",
	"editor.formatOnSave": true,
	"files.trimTrailingWhitespace": true,
	"editor.fontSize": 16,
	"editor.codeActionsOnSave": null,
	"editor.defaultFormatter": "esbenp.prettier-vscode",
	"prettier.useTabs": true,
	"window.zoomLevel": 1,
	"workbench.iconTheme": "material-icon-theme"
}
```

<b>Workspace settings:</b> Apply when a workspace is opened

`MyApp/.vscode/settings.json`

```
{
	"editor.fontSize": 16
}
```

# 3. keyboard shortcuts
| Description                                      | Keyboard Shortcut - Windows                    | Keyboard Shortcut - Mac                            |
| ------------------------------------------------ | ---------------------------------------------- | -------------------------------------------------- |
| Type Reload window                               | `ctrl + shift + p`                             | `cmd + shift + p`                                  |
| Open recent folders and workspaces               | `ctrl + r`                                     |                                                    |
| Quickly open files                               | `ctrl + p`                                     | `cmd + p`                                          |
| Zen modes                                        | `ctrl + k z`                                   |                                                    |
| Toggle Panel                                     | `ctrl + j`                                     |                                                    |
| Toggle sidebar                                   | `ctrl + b`                                     |                                                    |
| Side by side editing                             | `ctrl + \`                                     |                                                    |
| Switch between editors                           | `ctrl + 1`, `ctrl + 2`                         |                                                    |
| Multi cursor selection                           | `alt + click`                                  | `option + click`                                   |
| Set cursors above or below the current position  | `ctrl + alt + up` or `ctrl + alt + down`       | `cmd + option + up` or `cmd + option + down`       |
| Select all occurrences of the current selection  | `ctrl + shift + l`                             | `cmd + shift + l`                                  |
| Select next occurrences of the current selection | `ctrl + d`                                     | `cmd + d`                                          |
| Undo ext occurrences of the current selection    | `ctrl + u`                                     | `cmd + u`                                          |
| Select blocks of text                            | `shift + alt`                                  | `shift + option`                                   |
| Move cursor by words                             | `ctrl + left` or `ctrl + right`                | `option + left` or `option + right`                |
| Select words                                     | `ctrl + shift + left` or `ctrl + shift + right`| `option + shift + left` or `option + shift + right`|
| Move line up and down                            | `alt + up` or `alt + down`                     |                                                    |
| Copy line up and down                            | `shift + alt + up` or `shift + alt + down`     |                                                    |
| Split Editor                                     | `ctrl + \`                                     |                                                    |
| Close Editor                                     | `ctrl + w`                                     |                                                    |
| Save All                                         | `ctrl + k s`                                   |                                                    |
| Editor focus                                     | `ctrl + 1`                                     | `cmd + 1`                                          |
| Sidebar focus                                    | `ctrl + 0`                                     | `cmd + 0`                                          |


# Snippets

Select User Snippets under `File > Preferences` on Windows and `Code > Preferences` on macOS.

![image](https://user-images.githubusercontent.com/1612112/186821015-15f96630-7b2f-49d7-9d56-8db9fba13931.png)


# 4. Resources
- https://code.visualstudio.com/docs/getstarted/settings
- https://code.visualstudio.com/docs/getstarted/tips-and-tricks
- https://code.visualstudio.com/docs/editor/userdefinedsnippets
- https://code.visualstudio.com/docs/getstarted/keybindings
