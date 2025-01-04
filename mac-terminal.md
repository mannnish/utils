```bash
# mac install brew
brew install lsd
brew install font-hack-nerd-font
# add alias lsd=ls in .zshrc
# Profile > Change font to Hack nerd font

# changing terminal theme?
# Terminal (Activity Bar) > Settings > Profiles > Import Profile

# cd ~ && touch .zshrc
clear
cat ~/.zshrc
source /opt/homebrew/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh
source $(brew --prefix)/share/zsh-autosuggestions/zsh-autosuggestions.zsh
alias ls=lsd

# for java
export PATH="$PATH:$HOME/.rvm/bin"
```