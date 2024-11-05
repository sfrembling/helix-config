This repo is just my Helix config so I can clone my setup on new machines.

Link: [Helix-Editor](https://helix-editor.com/)

Linux:
```sh
curl https://raw.githubusercontent.com/sfrembling/helix-config/refs/heads/main/config.toml >> ~/.config/helix/config.toml
```

Windows:
```powershell
Invoke-RestMethod -Uri https://raw.githubusercontent.com/sfrembling/helix-config/refs/heads/main/config.toml -OutFile $(Join-Path $env:APPDATA -ChildPath "helix\config.toml")
```
