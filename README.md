<p align="center"><img src="logo.png" width="72" alt="openv6"></p>
<h1 align="center">openv6</h1>
<p align="center"><b>Static IPv6 proxies (HTTP + SOCKS5) from your own network, with one web dashboard.</b></p>
<p align="center"><a href="https://thephuc.xyz/openv6/">Website</a> · <a href="https://github.com/thephux/openv6-releases/releases/latest"><b>Download the latest version</b></a></p>

This repository hosts the installers and updates of openv6.

| System | Download |
|---|---|
| **Windows 10/11** | the command below, or [`openv6-setup-windows-amd64.exe`](https://github.com/thephux/openv6-releases/releases/latest/download/openv6-setup-windows-amd64.exe) |
| **macOS** (Intel and Apple silicon) | the command below, or [`openv6-macos.pkg`](https://github.com/thephux/openv6-releases/releases/latest/download/openv6-macos.pkg) |
| **Ubuntu / Debian / Zorin** | the command below, or the `.deb` files on the [releases page](https://github.com/thephux/openv6-releases/releases/latest) |

**Windows** (PowerShell):

```powershell
irm https://raw.githubusercontent.com/thephux/openv6-releases/main/install.ps1 | iex
```

**macOS / Linux** (Terminal):

```bash
curl -fsSL https://raw.githubusercontent.com/thephux/openv6-releases/main/install.sh | sudo bash
```

After installing, open the dashboard from the tray icon (or `http://<machine-LAN-IP>:8080`), create the admin account, then **Proxies → Create proxies**.

Free: 3 proxies on 1 machine. Pro (one-time payment): unlimited proxies, many machines, relay/UPnP/Tailscale sharing, API, customer accounts. See [pricing](https://thephuc.xyz/openv6/#pricing).

Every release ships a `SHA256SUMS` file; signed releases also ship `SHA256SUMS.sig`, which openv6 verifies before installing an update.
