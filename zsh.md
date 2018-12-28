install oh my zsh ''' sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)" '''


# edit ~/.zshrc

ZSH_THEME="ys"
alias zshconfig="vim ~/.zshrc"
alias zshconfig-go="source ~/.zshrc"
alias ohmyzsh="vim ~/.oh-my-zsh"


# speed up
可以使用git config --global oh-my-zsh.hide-status 1
关闭对status的检查，然后
disable auto upgrade To disable automatic upgrades, 
set the following in your ~/.zshrc:
DISABLE_AUTO_UPDATE=true

