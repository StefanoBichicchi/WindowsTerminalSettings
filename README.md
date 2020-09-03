# WindowsTerminalSettings
A backup repository I created to be able to share my windows-terminal setup across machines while keeping track of any changes I made.

## Installation
### Dependencies

#### Icons
All icons are in icons directory

#### Font
- [FiraCode](https://github.com/tonsky/FiraCode)

### Installation instruction

```cmd
cd
git clone https://github.com/StefanoBichicchi/WindowsTerminalSettings.git
cd WindowsTerminalSettings
copy C:\Users\<USER_NAME>\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json C:\Users\<USER_NAME>\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json.bak
rmdir C:\Users\<USER_NAME>\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json
mklink /H C:\Users\<USER_NAME>\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json settings.json
```
