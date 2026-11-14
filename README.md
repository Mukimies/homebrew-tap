# Mukimies Homebrew tap

Homebrew casks for software published by Mukimies.

## EQ Ape

[EQ Ape](https://github.com/Mukimies/eq-ape) is a system-wide equalizer for macOS (14.2 or later, Apple Silicon) that reads Equalizer APO-style config files.

Install the current pre-release (not notarized, so macOS will ask you to allow it under System Settings > Privacy & Security on first launch):

```sh
brew tap Mukimies/tap
brew trust Mukimies/tap
brew install --cask eq-ape
```

Homebrew 7 only installs casks from a tap that has been tapped and trusted explicitly. On older Homebrew versions without `brew trust`, skip that line.

Update with `brew upgrade --cask eq-ape`, remove with `brew uninstall --cask eq-ape`.
