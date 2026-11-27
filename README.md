# IPA-Decrypt tap

Homebrew tap for [IPA-Decrypt](https://github.com/Re13orn/IPA-Decrypt) — a GUI downloader for App Store / TestFlight IPAs that decrypts them offline (FairPlay) on the Mac, keeping the original bundle.

```sh
brew install --cask re13orn/tap/ipa-decrypt
```

Requires macOS 15+ on Apple Silicon. The build is ad-hoc signed and not notarized yet, so the first launch goes through Apple's "Open Anyway" flow.

Cask is submitted upstream to [Homebrew/homebrew-cask#306327](https://github.com/Homebrew/homebrew-cask/pull/306327); this tap exists so it can be installed before that lands.

```sh
brew uninstall --cask ipa-decrypt
brew untap re13orn/tap
```
