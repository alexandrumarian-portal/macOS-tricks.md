Override more system preferences from the terminal:
```
# take screenshots as jpg (usually smaller size) and not png
defaults write com.apple.screencapture type jpg

# show Library folder
chflags nohidden ~/Library

# show hidden files
defaults write com.apple.finder AppleShowAllFiles YES

# show path bar
defaults write com.apple.finder ShowPathbar -bool true

# show status bar
defaults write com.apple.finder ShowStatusBar -bool true

killall Finder;
```
