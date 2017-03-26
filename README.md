# image-optim-screenshots

Optimise your screenshots on Mac using Automator and ImageOptim

### Instructions

  - Download and install ImageOptim [https://imageoptim.com/mac](https://imageoptim.com/mac)

  - Set your default screenshot directory to something other than your desktop

```
mkdir ~/Documents/Screenshots && defaults write com.apple.screencapture location $_ && killall SystemUIServer
```

  - Download, extract, and import the 'Optimise Screenshots.zip' workflow into Automator [https://github.com/omgaz/image-optim-screenshots/blob/master/Optimise Screenshots.zip](https://github.com/omgaz/image-optim-screenshots/blob/master/Optimise%20Screenshots.zip)

