1. Install `flatpak builder`
```bash
$ flatpak install flathub org.flatpak.Builder
```

2. Clone repository
```bash
git clone https://github.com/chaddy314/us.zoom.Zoom
```

3. Install Electron (or other missing dependencies) via flatpak
```bash
$ flatpak install org.electronjs.Electron2.BaseApp
```

4. Build and install
```bash
$  flatpak run org.flatpak.Builder --force-clean --install build us.zoom.Zoom.json
```
