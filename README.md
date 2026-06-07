# AeroSpace Config

My [AeroSpace](https://github.com/nikitabobko/AeroSpace) tiling window manager config for macOS.

## Install on a new Mac

1. **Install AeroSpace:**
   ```sh
   brew install --cask nikitabobko/tap/aerospace
   ```

2. **Install this config** (AeroSpace reads `~/.aerospace.toml`):
   ```sh
   git clone https://github.com/andreasskyt/aerospace-config.git
   cp aerospace-config/aerospace.toml ~/.aerospace.toml
   ```

3. **Launch AeroSpace** (it'll ask for Accessibility permission the first time).

That's it — same keybindings and layout as mine.

## Updating

After tweaking `~/.aerospace.toml`, copy it back and push:
```sh
cp ~/.aerospace.toml aerospace-config/aerospace.toml
cd aerospace-config && git commit -am "update config" && git push
```
