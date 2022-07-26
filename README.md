# 1. Extensions

- [Prettier-vscode](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Material-icon-theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
- [Vscode-docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
- [Quokka-vscode](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode)
- [Auto-rename-tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
- [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)

# 2. User and workspace settings

<b>User settings:</b> Apply settings globally

`$HOME/Library/Application Support/Code/User/settings.json`

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

|Description | Keyboard Shortut |
| -----------|------------------|
| Type Reload window                              | `cmd + shift + p`                                    |
| Open recent folders and workspaces              | `ctrl + r`                                           |
| Quickly open files                              | `ctrl + p`                                           |
| Zen modes                                       | `ctrl + k z`                                         |
| Toggle Panel                                    | `ctrl + j`                                           |
| Toggle sidebar                                  | `ctrl + b`                                           |
| Side by side editing                            | `ctrl + \`                                           |
| Switch between editors                          | `ctrl + 1`, `ctrl + 2`                               |
| Multi cursor selection                          | `alt + click` -> Windows, `option + click` -> macOS  |
| Set cursors above or below the current position | `ctrl + alt + up` or `ctrl + alt + down`             |
| Select all occurrences of the current selection | `ctrl + shift + l`                                   |
| Select next occurrences of the current selection| `ctrl + d`                                           |
| Select blocks of text                           | `shift + alt` -> Windows, `shift + option` -> macOS  |
| Move line up and down                           | `alt + up` or `alt + down`                           |
| Copy line up and down                           | `shift + alt + up` or `shift + alt + down`           |

# 4. Resources
- https://code.visualstudio.com/docs/getstarted/settings
- https://code.visualstudio.com/docs/getstarted/tips-and-tricks
