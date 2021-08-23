# 1. Extensions

- https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode
- https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme
- https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker
- https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode
- https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag

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

# 3. Resources
- https://code.visualstudio.com/docs/getstarted/settings
