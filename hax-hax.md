### Add spacer to OS X dock
```
defaults write com.apple.dock persistent-apps -array-add '{tile-data={}; tile-type="spacer-tile";}'
killall Dock
```
Source: http://lifehacker.com/5993307/easily-add-spacers-to-your-macs-dock
