```
alias showhf="defaults write com.apple.finder AppleShowAllFiles YES && killAll Finder"
alias hidehf="defaults write com.apple.finder AppleShowAllFiles NO && killAll Finder"
alias myip="curl ipecho.net/plain ; echo"

alias pushallmaster="git add . && git commit -m "commit" && git push -u origin master"

alias rmnodemodules="find . -name 'node_modules' -type d -prune -exec rm -rf '{}' +"
```
