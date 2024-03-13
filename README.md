## Install Apps

```PowerShell
winget upgrade --all && winget install --id=Mozilla.Firefox -e  && winget install --id=Mozilla.Firefox.DeveloperEdition -e  && winget install --id=Microsoft.VisualStudioCode -e  && winget install --id=Google.Chrome -e  && winget install --id=Discord.Discord -e  && winget install --id=Valve.Steam -e && winget install --id=Microsoft.WindowsTerminal  -e && winget install --id=KDE.KDEConnect  -e && winget install --id=7zip.7zip  -e && winget install --id=OO-Software.ShutUp10  -e && winget install --id=Mozilla.Thunderbird  -e && winget install --id=Wox.Wox  -e && winget install -e --id=voidtools.Everything
```

### General Usage

- Firefox
- Google Chrome
- Discord
- Steam
- KDE Connect
- 7zip
- Thunderbird
- Wox/Everyting
- O&O ShutUp10++
  ```PowerShell
    shutup10
  ```
  
### Development

- Visual Studio Code
- [Windows Terminal](https://apps.microsoft.com/detail/9n0dx20hk701)
- Wsl
  ```PowerShell
  wsl --install
  ```
- [Ubuntu](https://apps.microsoft.com/detail/9pdxgncfsczv)
  ```PowerShell
  wsl --install -d Ubuntu
  ```

## Set Development Preferences

### Terminal

- Install [Oh My Zsh](https://ohmyz.sh)
  ```PowerShell
  # Set Zsh as the default shell
  chsh -s $(which zsh)
  ```
- Install [Vimrc](https://github.com/amix/vimrc)
- Install [Node](https://nodejs.org/en/)
- Install [Yarn](https://yarnpkg.com/en/docs/install)
- Install [Zsh Autosuggestions](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md)
- Install [Zsh Syntax Highlighting](https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md)
- Install [Powerlevel10k](https://github.com/romkatv/powerlevel10k)
- Install [Emoji Plugin](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/emoji)
- Set .gitconfig:
  ```
  [user]
     email = demha082@gmail.com
     name = hamzademirr
  ```

- Set GitHub SSH Key

  ```bash
  mkdir ~/.ssh && cd ~/.ssh
  ```

  ```bash
  ssh-keygen -t ed25519 -C "demha082@gmail.com"
  ```
  
  ```bash
  eval "$(ssh-agent -s)"
  ```
