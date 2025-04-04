![welcome](img/welcome.png)


## Files
The theme is split into two files:
1. [schemes.jsonc](schemes.jsonc): 📄text colorization
2. [themes.jsonc](themes.jsonc): 🪟window and tab colorization

## Installation
### Automatic Installation (Recommended)
> Attention! this method only works for color schemes, Windows Terminal doesn't support downloading theme fragments for now.\
See [#14002](https://github.com/microsoft/terminal/issues/14002) and [#16063](https://github.com/microsoft/terminal/issues/16063) for more information
- ✅[schemes.jsonc](schemes.jsonc): Supported
- ❌[themes.jsonc](themes.jsonc): Currently not supported
1. Open Powershell and run the following:
```powershell
Invoke-Webrequest -uri 'https://raw.githubusercontent.com/huacat-pink/windows-terminal/main/schemes.jsonc' -OutFile ( New-Item -Path "$($env:LOCALAPPDATA)\Microsoft\Windows Terminal\Fragments\Huacat Pink Theme\schemes.json" -Force )
```
> This will download the scheme and the theme automatically to your disk
2. **Restart Windows Terminal** to activate the theme

### Manual Installation


## Screenshots
![light colortest](img/light_coltest.png)
![dark colortest](img/dark_coltest.png)

## References

- [catppuccin/windows-terminal](https://github.com/catppuccin/windows-terminal)
- [Serendipity-Theme/windows-terminal](https://github.com/Serendipity-Theme/windows-terminal)
