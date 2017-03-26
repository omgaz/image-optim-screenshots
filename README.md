# image-optim-screenshots

Optimise your screenshots on Mac using Automator and ImageOptim.

The workflow watches a custom screenshot directory for changes and passes the files to ImageOptim.
On completion a notification toast will appear.

### Instructions

  - Download and install ImageOptim [https://imageoptim.com/mac](https://imageoptim.com/mac)

  - Set your default screenshot directory to something other than your desktop

```
mkdir ~/Documents/Screenshots && defaults write com.apple.screencapture location $_ && killall SystemUIServer
```

  - Download, extract, and import the 'Optimise Screenshots.zip' workflow into Automator [https://github.com/omgaz/image-optim-screenshots/blob/master/Optimise Screenshots.zip](https://github.com/omgaz/image-optim-screenshots/blob/master/Optimise%20Screenshots.zip)

![screen shot 2017-03-27 at 10 45 01](https://cloud.githubusercontent.com/assets/908155/24336426/debf9564-12da-11e7-8589-a841af2934b2.png)
