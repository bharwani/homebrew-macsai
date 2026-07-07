# homebrew-macsai

> [!WARNING]
> **This tap is deprecated and will be retired soon.**
> Mac Sai is now in the official Homebrew cask repository, so you no longer need this tap. Install with:
> ```bash
> brew install --cask mac-sai
> ```
> If you installed through this tap, you can remove it: `brew untap iliyami/macsai` (your installed app and future `brew upgrade` are unaffected).

Homebrew tap for [Mac Sai](https://github.com/iliyami/MacSai), the open-source Mac cleaner, optimizer, and malware scanner.

## Install (deprecated, prefer the official cask above)

```bash
brew tap iliyami/macsai
brew install --cask mac-sai
```

This tap is updated automatically when new versions of Mac Sai are released, and is kept working during the transition to the official cask.

> Previously distributed as `mac-clean` from `iliyami/macclean`. If you installed the old cask, run `brew uninstall --cask mac-clean && brew untap iliyami/macclean` before tapping the new name.
