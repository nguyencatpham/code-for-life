# dev note (ubuntu 18.04)
It's time to stop using the mouse and become a real senior!

## Tools

### Chrome
1. Vimnium - The hacker's browser
```
Navigate Tab: 
    Quick Switch : Ctrl + Tab, Ctrl + Shift + Tab, Ctr + 1, Ctrl +9
    Open/Close   : Ctrl + T, Ctrl + W
    Google Search: O
    Using command: /
    Fullscreen   : f11
    Quick Link   : f
    More help    : ?
```
2. Redux devtool - for reactjs developer
3. Google Translate - Translate selected text
4. Octotree - github tree viewer on browser
5. Google Search Keyboard Shortcuts - 
6. Night mode Pro - Turn Chrome to Dark theme
7. Multi-clock

### Command Promt
1. zsh
```
sudo apt install zsh
chsh -s $(which zsh)
# logout 
gnome-session-quit
```

2. ohmyzsh
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

3. vim
```
sudo add-apt-repository ppa:jonathonf/vim
sudo apt update
sudo apt install vim
sudo apt install vim-gtk3 vim-nox
```
4. neovim
```
sudo apt-get install ninja-build gettext libtool libtool-bin autoconf automake cmake g++ pkg-config unzip
git clone https://github.com/neovim/neovim.git
cd neovim
git checkout v0.4.4
make CMAKE_BUILD_TYPE=RelWithDebInfo
sudo make install
```
5. thinkvim 
```
https://github.com/hardcoreplayers/ThinkVim
```
or quick install
```
git clone --depth=1 https://github.com/hardcoreplayers/ThinkVim.git ~/.config/nvim
cd ~/.config/nvim
bash scripts/install.sh
```
6. tmux
```
https://github.com/gpakosz/.tmux
```
or quick install
```
sudo apt-get update
sudo apt-get install tmux
cd ~
git clone https://github.com/gpakosz/.tmux.git
ln -s -f .tmux/.tmux.conf
cp .tmux/.tmux.conf.local .
```
add plugin
```
set -g @plugin 'thewtex/tmux-mem-cpu-load'
```

### Coding style
1. GO 
```
https://github.com/uber-go/guide
```

2. Javascript 
```
https://github.com/airbnb/javascript
```
## Shortcuts

### Bash
https://ss64.com/bash/syntax-keyboard.html
