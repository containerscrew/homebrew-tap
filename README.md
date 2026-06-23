# containerscrew homebrew tap

Homebrew tap for `containerscrew` CLI tools.

## Available formulae

- [`rsecure`](https://github.com/containerscrew/rsecure) — Secure file encryption using pure Rust and AES-256-GCM.

## Usage

Add the tap once:

```bash
brew tap containerscrew/tap
```

Then install any formula by name:

```bash
brew install rsecure
```

Or install directly without tapping first:

```bash
brew install containerscrew/tap/rsecure
```

> [!NOTE]
> If you previously installed `rsecure` via the old cask (`brew install --cask rsecure`), uninstall it first with `brew uninstall --cask rsecure`. The cask has been replaced by a formula, which avoids the macOS Gatekeeper quarantine and no longer requires `xattr -d com.apple.quarantine`.

## License

Each tool is licensed individually — see the linked repositories.
