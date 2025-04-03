<h3 align="center">
<img src="logo.png" width=100px></img><br/>
Huacat Pink Theme for Windows Terminal
</h3>

<p align="center"> a cool pink theme for your terminal</p>

## Installation
### Automatic Installation (Recommended)
> Attention! this method only works for color schemes, Windows Terminal doesn't support downloading theme fragments for now.\
See [#14002](https://github.com/microsoft/terminal/issues/14002) and [#16063](https://github.com/microsoft/terminal/issues/16063) for more information
1. Open Powershell and run the following:
```powershell
Invoke-Webrequest -uri 'https://raw.githubusercontent.com/huacat-pink/windows-terminal/main/schemes.jsonc' -OutFile ( New-Item -Path "$($env:LOCALAPPDATA)\Microsoft\Windows Terminal\Fragments\Huacat Pink Theme\schemes.json" -Force )
```
> This will download the scheme and the theme automatically to your disk
2. **Restart Windows Terminal** to activate the theme
## Screenshots

## References

- [catppuccin/windows-terminal](https://github.com/catppuccin/windows-terminal)
- [Serendipity-Theme/windows-terminal](https://github.com/Serendipity-Theme/windows-terminal)
