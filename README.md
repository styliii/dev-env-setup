# dev-env-setup

### Terminal Setup
1. Download solarized `git clone git@github.com:tomislav/osx-terminal.app-colors-solarized.git`
2. Install via Preferences in Terminal
3. Install Homebrew `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

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
6. `brew install the_silver_searcher`

### Setting up oh-my-zshell
```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### FZF
```
brew reinstall fzf
/opt/homebrew/opt/fzf/install
```
### Key Bindings
http://www.economyofeffort.com/2014/08/11/beyond-ctrl-remap-make-that-caps-lock-key-useful/
Download karabiner https://karabiner-elements.pqrs.org/

## TODO
- [ ] move this stuff into the script
- [ ] git should be installed first
- [ ] instructions for installing brew
