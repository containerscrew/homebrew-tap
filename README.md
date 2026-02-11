# containerscrew homebrew tap

Homebrew tap for containerscrew CLI tools.

# Available brews

- `rsecure`: https://github.com/containerscrew/rsecure

# Usage

```bash
brew tap containerscrew/tap
```

# Examples

```bash
brew install --cask rsecure
```

# macOS: Gatekeeper may block the binary

<img width="251" height="260" alt="image" src="https://github.com/user-attachments/assets/f575200c-6b8e-45e2-a012-85f98d5073ac" />

Run the following command in your terminal:

```bash
xattr -d com.apple.quarantine /opt/homebrew/bin/rsecure
```
Or, go to `System Settings → Privacy & Security` and allow the applicaion not signed by the Apple ecosystem.

<img width="482" height="193" alt="image" src="https://github.com/user-attachments/assets/bbfbc6bf-d9f3-406b-8ba0-30b03dbf0719" />

# License

Each tool is licensed individually.
