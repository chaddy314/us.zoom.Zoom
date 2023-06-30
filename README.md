1. Install `flatpak-builder`

- Suse:
```bash
$ sudo zypper in flatpak-builder
```


- Debian/Ubuntu:
```bash
$ sudo apt in flatpak-builder
```

- Arch
```bash
$ sudo pacman -S flatpak-builder
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
$  sudo flatpak-builder --force-clean --install  build us.zoom.Zoom.json
```
