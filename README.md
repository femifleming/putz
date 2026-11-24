# putz

A cleaner for your Mac, in the faltung look: system, browser and developer caches, app and
plug-in leftovers, crash dumps, duplicates, orphaned files, startup items and a disk map. Every
delete goes through a safety check first.

macOS 14 or later, Apple Silicon.

## Install

putz is installed with Homebrew only:

```sh
brew tap femifleming/tap
brew install --cask femifleming/tap/putz
```

Update with `brew upgrade --cask putz`, remove with `brew uninstall --cask putz`.

The app is ad-hoc signed, not notarised; the cask clears the download quarantine so it opens.
This repository holds only the releases that the cask installs.
