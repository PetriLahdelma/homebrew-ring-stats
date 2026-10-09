# Homebrew tap for Ring Stats

[Ring Stats](https://github.com/PetriLahdelma/ring-stats) shows your Oura
scores in the Mac menu bar. This tap carries its Homebrew cask until the
project meets homebrew-cask's acceptance thresholds.

```bash
brew install --cask PetriLahdelma/ring-stats/ring-stats
```

The cask downloads the Developer ID-signed, notarized DMG from the
project's GitHub release and checks its SHA-256. It is updated with each
release; `brew upgrade` picks up new versions.

Ring Stats keeps your Oura credentials in the macOS Keychain. Before
`brew uninstall --zap`, choose "Disconnect & Delete Local Data" in the app
to revoke the authorization and remove them; `zap` does not touch the
Keychain.

Issues go to the [main repository](https://github.com/PetriLahdelma/ring-stats/issues).
