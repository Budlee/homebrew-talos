# Talos Homebrew Tap

- 🔥 Easy installation of [talosctl](https://github.com/siderolabs/talos), the reference CLI to use Talos OS
- ⭐ Works on macOS (Intel/ARM) and Linux (amd64/arm64/armv7)
## How do I install talosctl?

Installing talosctl is simple:
```
brew install siderolabs/talos/talosctl
```

You can also only add the tap which makes formulae within it available in search results (`brew search` output):

```
brew tap siderolabs/talos
brew install talosctl
```

Note: since the `v1.4.4` release the `talosctl` Cask is deprecated in favor of a more universal `talosctl` formula. If you have the Cask installed, you need to uninstall it first: `brew uninstall --cask talosctl`.

## Updates

Currently, updates of this repository are manual
(see [siderolabs/talos#2148](https://github.com/siderolabs/talos/issues/2148)) and may be delayed.
If you rely on this tap, please send pull requests.

## Resources

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
