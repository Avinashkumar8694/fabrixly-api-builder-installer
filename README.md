<h1 align="center">Loom Studio</h1>

<p align="center"><b>Design APIs on a canvas, on your own computer.</b><br>
The desktop app of Loom, the API builder: build, test and run services locally, publish them to the cloud when you are ready.<br>
<sub>Windows · macOS · Linux</sub></p>

<p align="center"><a href="#download"><b>Download</b></a> · <a href="https://fabloom.fabrixly.com">Website</a> · <a href="https://market.fabrixly.com/?product=loom">Marketplace</a></p>

---

## Download

**Loom Studio 0.3.0.** This repository only gives away the apps; the files are attached to the [**v0.3.0 release**](https://github.com/Avinashkumar8694/fabrixly-api-builder-installer/releases/tag/v0.3.0). Press a link and the download starts. Every file's SHA-256 is in [`SHA256SUMS`](https://github.com/Avinashkumar8694/fabrixly-api-builder-installer/releases/download/v0.3.0/SHA256SUMS) and in [`manifest.json`](manifest.json).

#### macOS

| For | What | Download | Size | SHA-256 |
|---|---|---|---|---|
| **Apple silicon (M1 and newer)** | Disk image | [LoomStudio-0.3.0-mac-arm64.dmg](https://github.com/Avinashkumar8694/fabrixly-api-builder-installer/releases/download/v0.3.0/LoomStudio-0.3.0-mac-arm64.dmg) | 186 MB | `60f4afda671c1957…` |
| Apple silicon (M1 and newer) | Zip archive | [LoomStudio-0.3.0-mac-arm64.zip](https://github.com/Avinashkumar8694/fabrixly-api-builder-installer/releases/download/v0.3.0/LoomStudio-0.3.0-mac-arm64.zip) | 182 MB | `8ea07266346d185b…` |
| Intel | Disk image | [LoomStudio-0.3.0-mac-x64.dmg](https://github.com/Avinashkumar8694/fabrixly-api-builder-installer/releases/download/v0.3.0/LoomStudio-0.3.0-mac-x64.dmg) | 191 MB | `35973073fdca4e1f…` |
| Intel | Zip archive | [LoomStudio-0.3.0-mac-x64.zip](https://github.com/Avinashkumar8694/fabrixly-api-builder-installer/releases/download/v0.3.0/LoomStudio-0.3.0-mac-x64.zip) | 188 MB | `b925eace2e4c5ca1…` |

#### Windows

| For | What | Download | Size | SHA-256 |
|---|---|---|---|---|
| **64-bit Intel / AMD (most PCs)** | Installer | [LoomStudio-Setup-0.3.0-x64.exe](https://github.com/Avinashkumar8694/fabrixly-api-builder-installer/releases/download/v0.3.0/LoomStudio-Setup-0.3.0-x64.exe) | 151 MB | `2002147a49d7da22…` |

#### Linux

| For | What | Download | Size | SHA-256 |
|---|---|---|---|---|
| **64-bit Intel / AMD** | AppImage | [LoomStudio-0.3.0-linux-x64.AppImage](https://github.com/Avinashkumar8694/fabrixly-api-builder-installer/releases/download/v0.3.0/LoomStudio-0.3.0-linux-x64.AppImage) | 156 MB | `8ca9c6a5713a9f1e…` |
| 64-bit Intel / AMD | Debian package | [LoomStudio-0.3.0-linux-x64.deb](https://github.com/Avinashkumar8694/fabrixly-api-builder-installer/releases/download/v0.3.0/LoomStudio-0.3.0-linux-x64.deb) | 124 MB | `843d541d767f35a1…` |

### Check what you downloaded

```bash
# macOS / Linux
shasum -a 256 LoomStudio-0.3.0-mac-arm64.dmg      # compare with SHA256SUMS
```
```powershell
# Windows
Get-FileHash LoomStudio-Setup-0.3.0-x64.exe -Algorithm SHA256
```

### First start

The apps are **not signed yet**, so the system asks you to confirm once: on macOS open the app with right-click → Open (or System Settings → Privacy & Security → Open Anyway); on Windows choose **More info → Run anyway** in SmartScreen. On Linux make the AppImage executable (`chmod +x LoomStudio-*.AppImage`) or install the `.deb` with `sudo apt install ./LoomStudio-*.deb`.

Sign in with your Fabrixly account. The first start prepares a local database and takes a little while.
