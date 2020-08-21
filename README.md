# dev note 

> dev-note is very begining note for dev. At the moment, it just support for ubuntu 18.04. I need a help to improve dev-note become a note for every developer on every platform.

It's time to stop using the mouse!

## Tools

### Chrome

- Vimnium - The hacker's browser

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
- Redux devtool - for reactjs developer
- Google Translate - Translate selected text
- Octotree - github tree viewer on browser
- Google Search Keyboard Shortcuts - 
- Dark mode - Turn Chrome to Dark theme
- Multi-clock
- Grammarly

### Terminal 
#### zsh
```
sudo apt install zsh
chsh -s $(which zsh)
# logout 
gnome-session-quit
```

#### ohmyzsh
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
#### tmux
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
# write this at the beginning of ~/.zshrc
if [ "$TMUX" = "" ]; then tmux; fi
```
```
xterm -e tmux
set -g @plugin 'thewtex/tmux-mem-cpu-load'
git clone https://github.com/zsh-users/zsh-autosuggestions ~/.oh-my-zsh/custom/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ~/.oh-my-zsh/custom/plugins/zsh-syntax-highlighting
```
#### Terminal Preferences
- Download fonts
https://fontlibrary.org/en/font/consolamono
> install this font, then apply for terminal
```
sudo apt install font-manager
```
- Setup terminal Preferences
  + Theme : Dark
  + Uncheck show menu bar
  + Custom font: Consola Mono Book
  + Run command as login shell
  + Colors:
    - Background: #1C1C1C
    - Text: #CFBFAD
    - Bold text: #D33682
    - Build in schema: Tango

### Code IDE/editor
#### vim8
```
sudo add-apt-repository ppa:jonathonf/vim
sudo apt update
sudo apt install vim
sudo apt install vim-gtk3 vim-nox
```
* native package
- https://github.com/sheerun/vim-polyglot
- https://github.com/sickill/vim-monokai

### Other suggestion
1. neovim 
```
sudo apt-get install ninja-build gettext libtool libtool-bin autoconf automake cmake g++ pkg-config unzip
git clone https://github.com/neovim/neovim.git
cd neovim
git checkout v0.4.4
make CMAKE_BUILD_TYPE=RelWithDebInfo
sudo make install

sudo npm install -g neovim

sudo apt update
sudo apt install ruby-full
sudo gem install neovim

sudo apt-get install python-pip
sudo apt-get install python3-pip
pip install neovim
pip3 install neovim
```
- Customize config
```
vi ~/.thinkvim.d/init.vim
```
then add this code
```
let g:spaceline_seperate_style= 'arrow'
```
2. thinkvim 
```
https://github.com/hardcoreplayers/ThinkVim
```
or quick install
```
git clone --depth=1 https://github.com/hardcoreplayers/ThinkVim.git ~/.config/nvim
cd ~/.config/nvim
bash scripts/install.sh
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

### Todos
 - Write MORE notes
### Issues
 - Nvim Theme is not good (pain my eyes)
 - Tabnine load too more ram
 - Does not support standardjs
 - Explorer still slowly
License
----

MIT


**Free Software, Hell Yeah!**
