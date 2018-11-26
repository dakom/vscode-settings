# VSCode Settings

My personal Visual Studio Code settings.

## Syncing Instructions (copied from [here](https://github.com/alefragnani/vscode-settings)) 

### Windows

#### Stable
```
cd %HOMEPATH%/Documents/GitHub/vscode-settings/
mklink /H %HOMEPATH%\AppData\Roaming\Code\User\settings.json settings.json
mklink /H %HOMEPATH%\AppData\Roaming\Code\User\keybindings.json keybindings.json
mklink /J %HOMEPATH%\AppData\Roaming\Code\User\snippets snippets
```

#### Insiders
```
cd %HOMEPATH%/Documents/GitHub/vscode-settings/
mklink /H "%HOMEPATH%\AppData\Roaming\Code - Insiders\User\settings.json" settings.json
mklink /H "%HOMEPATH%\AppData\Roaming\Code - Insiders\User\keybindings.json" keybindings.json
mklink /J "%HOMEPATH%\AppData\Roaming\Code - Insiders\User\snippets" snippets
```

### MacOS

#### Stable
```
cd ~/Documents/GitHub/vscode-settings/
ln -h settings.json ~/Library/Application\ Support/Code/User/settings.json
ln -h keybindings.json ~/Library/Application\ Support/Code/User/keybindings.json
ln -s ~/Documents/GitHub/vscode-settings/snippets ~/Library/Application\ Support/Code/User/snippets
```

#### Insiders
```
cd ~/Documents/GitHub/vscode-settings/
ln -h settings.json ~/Library/Application\ Support/Code\ -\ Insiders/User/settings.json
ln -h keybindings.json ~/Library/Application\ Support/Code\ -\ Insiders/User/keybindings.json
ln -s ~/Documents/GitHub/vscode-settings/snippets ~/Library/Application\ Support/Code\ -\ Insiders/User/snippets
```