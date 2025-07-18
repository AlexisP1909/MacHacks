https://youtu.be/3jeeFc2Vo1U?si=GhwB2W-m4xSCP80j
look into the finder options
## Organise Windows
Keep mouse on the expand button (you can have multiple windows of the same app displayed thanks to this). 

See top left of this screenshot
![Screenshot 2025-04-08 at 16.10.26.png](https://github.com/AlexisP1909/MacHacks/blob/main/Screenshot%202025-04-08%20at%2016.10.26.png)
## Clipboard Manager (presse-papier) 
I personnaly use Flycut. (Please change the icon to scissors I beg)
https://formulae.brew.sh/cask/flycut

## Navigating Quickly

cmd + tab to go back to last focused app
3 fingers swipe to see every app

## Useful Shortcuts
cmd + q : Quit an app (every window, be careful)

## Make dock appear faster

run in terminal
```
defaults write com.apple.dock autohide-delay -float 0; killall Dock
```

```
defaults write com.apple.dock autohide-time-modifier -float 0.15; killall Dock
```
## Alt Tab like Windows
```
Brew install --cask alt-tab
```
## Terminal
Use Iterm 2 with Starship

## VSCode
Connect to enterprise Github:
- Go to your Github enterprise account
- Record your enterprise github URL
- Go to Settings > Developer Settings, create a Personal Access token & record it
- clone an enterprise repo
- open in VS Code
- Go to settings, type github, go in GHE.com & GitHub, write your enterprise URI there
- fetch all by pressing the button in VSCode

![Screenshot 2025-04-28 at 15.51.10.png](https://github.com/AlexisP1909/MacHacks/blob/main/Screenshot%202025-04-28%20at%2015.51.10.png)

- You will be prompted for your Username (eg: Alexis-Pouillieute)
- You will then be prompted for a password, use your Personal Access Token there
