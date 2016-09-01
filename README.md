# dev-env-setup

### Terminal Setup
1. Download solarized `git clone git@github.com:tomislav/osx-terminal.app-colors-solarized.git`
2. Install via Preferences in Terminal

### Config Setup
1. Install git if not already
2.  `sh -c "$(curl -fsSL https://raw.githubusercontent.com/styliii/dev-env-setup/master/.cfg-install.sh)"`
3. search and replace `Li` in .zshrc file to whatever your user name is
4. `config br -b [whatever-branch-name-you-want]`
5. `config add .zshrc`
6. `config -m 'adds .zshrc for this computer'`

### Setting up Macvim
1. `brew install macvim`
3. `config submodule init`
4. `config submodule update`
3. `git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim`
5. In Macvim `:BundleInstall`

### Setting up oh-my-zshell
```
git clone git://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh
chsh -s /bin/zsh
```

### FZF
```
brew reinstall --HEAD fzf
/usr/local/opt/fzf/install
```
## TODO
- [] move this stuff into the script
