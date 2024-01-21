# Installing chromium on mac

1. Install homebrew on system

`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

2. Install chromium via homebrew

`brew install --cask chromium`

3. If there is a message like "Chromium app is damaged and it can't be opened. You should move it to the bin" then ...

`xattr -d com.apple.quarantine /Applications/Chromium.app`
