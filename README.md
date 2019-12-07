# Customized Oh-my-zsh theme 
## How to use this customization ? 
1. Download **Fira Nerd Fonts** ( https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/FiraMono/Regular/complete )
2. Change default font of your terminal from its settings and set it to **FiraMono Nerd Font Mono Regular** (Required to support icons)
3. Install powerlevel10k theme ( https://github.com/romkatv/powerlevel10k )
4. Overwrite your **~/.zshrc** and **~/.p10k.zsh** with above given files
5. Done !!

It shows below listed segments in the terminal 
- current node version of your project. 
- Battery Status 
- OS Icon
- Directory icon including path (If path is too long then it will show short path)
- Git Status (stash, tracked, untracked, modified, updated, added etc)

## Required dependencies (plugins) to work smoothly 
- git
- zsh-autosuggestions ( https://github.com/zsh-users/zsh-autosuggestions )
- sudo
- zsh-256color ( https://github.com/chrissicool/zsh-256color )
- alias-tips ( https://github.com/djui/alias-tips )
- z
### ZSH Auto Suggestion 
![screenshots](/images/ss1.png)

### Single Header after every command 
![screenshots](/images/ss2.png)

### Loading state when fetching git status of current folder
![screenshots](/images/ss3.png)

### Current Git status (Node version, battery status on right side)
![screenshots](/images/ss4.png)