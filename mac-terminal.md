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

### tools
- pearcleaner for better application management
- alttab for a better alttab
  - open its setting and change it from option-tab to command-tab
  - you can also change the switching preview
  - `brew install --cask alt-tab` 


### Settings
- Finder default view
  - To set a default sorting method in macOS Finder, navigate to a folder, choose your preferred view (Icon, List, Column, or Gallery), then use "View > Show View Options" to select your desired sort order and grouping, and click "Use as Defaults". 
