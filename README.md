# Codestead – downloads

Installers for **Codestead**, a family of learning tools where you learn by doing. Every tool and the
hub have their own releases here; their names start with the tool's id.

**New here? Install the Codestead hub.** It installs, starts and updates the tools for you.

## Codestead hub

Install and update the Codestead learning tools. Latest version: **0.1.1** · [release notes](https://github.com/JesperE98/codestead-releases/releases/tag/codestead-hub-v0.1.1) · [all versions](https://github.com/JesperE98/codestead-releases/releases?q=codestead-hub-v&expanded=true)

| System | Download | How to install |
|---|---|---|
| **Windows 10/11 (x64)** | [codestead-hub-win-x64-Setup.exe](https://github.com/JesperE98/codestead-releases/releases/download/codestead-hub-latest/codestead-hub-win-x64-Setup.exe) | Run the file. It installs for your user and updates itself. |
| **Ubuntu / Debian** | [codestead-hub_amd64.deb](https://github.com/JesperE98/codestead-releases/releases/download/codestead-hub-latest/codestead-hub_amd64.deb) | `sudo apt install ./codestead-hub_amd64.deb` |
| **Fedora** | [codestead-hub.x86_64.rpm](https://github.com/JesperE98/codestead-releases/releases/download/codestead-hub-latest/codestead-hub.x86_64.rpm) | `sudo dnf install ./codestead-hub.x86_64.rpm` |
| **Arch Linux / CachyOS** | [codestead-hub-x86_64.pkg.tar.zst](https://github.com/JesperE98/codestead-releases/releases/download/codestead-hub-latest/codestead-hub-x86_64.pkg.tar.zst) | `sudo pacman -U codestead-hub-x86_64.pkg.tar.zst` |
| **Any Linux (AppImage)** | [codestead-hub-linux-x86_64.AppImage](https://github.com/JesperE98/codestead-releases/releases/download/codestead-hub-latest/codestead-hub-linux-x86_64.AppImage) | `chmod +x` the file and start it. It updates itself. |

## Codestead Linux

Learn the Linux shell by doing. Latest version: **0.5.2** · [release notes](https://github.com/JesperE98/codestead-releases/releases/tag/codestead-linux-v0.5.2) · [all versions](https://github.com/JesperE98/codestead-releases/releases?q=codestead-linux-v&expanded=true)

| System | Download | How to install |
|---|---|---|
| **Windows 10/11 (x64)** | [codestead-linux-win-x64-Setup.exe](https://github.com/JesperE98/codestead-releases/releases/download/codestead-linux-latest/codestead-linux-win-x64-Setup.exe) | Run the file. It installs for your user and updates itself. |
| **Ubuntu / Debian** | [codestead-linux_amd64.deb](https://github.com/JesperE98/codestead-releases/releases/download/codestead-linux-latest/codestead-linux_amd64.deb) | `sudo apt install ./codestead-linux_amd64.deb` |
| **Fedora** | [codestead-linux.x86_64.rpm](https://github.com/JesperE98/codestead-releases/releases/download/codestead-linux-latest/codestead-linux.x86_64.rpm) | `sudo dnf install ./codestead-linux.x86_64.rpm` |
| **Arch Linux / CachyOS** | [codestead-linux-x86_64.pkg.tar.zst](https://github.com/JesperE98/codestead-releases/releases/download/codestead-linux-latest/codestead-linux-x86_64.pkg.tar.zst) | `sudo pacman -U codestead-linux-x86_64.pkg.tar.zst` |
| **Any Linux (AppImage)** | [codestead-linux-linux-x86_64.AppImage](https://github.com/JesperE98/codestead-releases/releases/download/codestead-linux-latest/codestead-linux-linux-x86_64.AppImage) | `chmod +x` the file and start it. It updates itself. |

## What the releases are

| Release | Contents |
|---|---|
| `<id>-v<version>`, e.g. `codestead-linux-v0.5.1` | Every file of that version and `SHA256SUMS.txt` with their checksums |
| `<id>-latest` | The latest version under fixed names (the links above), and the update feed that installed copies check |
| `catalog` | `catalog.json`, the signed list of tools the hub reads (`catalog.json.sig` is its signature) |

The apps are not yet signed with a developer certificate. On Windows, SmartScreen may say
"Windows protected your PC": choose **More info** → **Run anyway**.

This page is updated automatically when a new version is published.
