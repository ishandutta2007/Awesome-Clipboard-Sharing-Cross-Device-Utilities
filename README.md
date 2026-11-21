# Awesome-Clipboard-Sharing-Cross-Device-Utilities

# Top Clipboard Sharing & Cross-Device Utilities Ecosystem

**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on Cross-Device Clipboard Sync, Local Clipboard Managers, Encrypted Snippet Sharing & LAN/P2P Device Continuity*  
**Last updated: November 2026**

This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Clipboard Sharing & Cross-Device Utilities**. These tools synchronize, store, encrypt, search, and transfer copied text, images, files, and snippets across macOS, Windows, Linux, iOS, and Android devices using end-to-end encrypted cloud relays, peer-to-peer local network protocols, and searchable clipboard history managers.

**Examples** include Paste, ClipDo, 1Password, Bitwarden, CopyQ, Ditto, ClipboardFusion, Apple Universal Clipboard, Pushbullet, AirDroid, and baiyuze/pasteferry (the category leaders and popular runtimes). 

**Open-source emphasis**: This section is heavily expanded with every major active project for cross-device LAN/E2EE clipboard sync (`baiyuze/pasteferry`, `KDE Connect`, `SyncClipboard`, `ClipCascade`), desktop clipboard history managers (`CopyQ`, `Ditto`, `Maccy`, `Cliphist`, `GPaste`), and encrypted cross-device vaults (`Bitwarden`) — ideal for multi-device developers, power users, privacy advocates, and Linux/macOS/Windows workflow enthusiasts.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Support & Share](#support--share)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Paste (Paste App)](https://pasteapp.io)**  
  Polished visual clipboard manager and iCloud-synced history organizer for macOS, iPadOS, and iOS featuring searchable pinboards and instant link previews.

- **[Apple Universal Clipboard (Continuity)](https://apple.com)**  
  Built-in Apple ecosystem feature enabling seamless copy-and-paste of text, images, photos, and files across nearby Macs, iPhones, and iPads over encrypted Bluetooth and Wi-Fi.

- **[1Password](https://1password.com)**  
  Enterprise and personal password manager offering secure cross-device item sharing, ephemeral encrypted links (`Psst!`), and auto-clearing clipboard protection.

- **[Pushbullet](https://pushbullet.com)**  
  Cloud device-bridging service for pushing links, text snippets, files, and notifications between desktop browsers, Windows, and Android devices.

- **[AirDroid](https://airdroid.com)**  
  Cross-platform mobile-to-desktop management suite supporting remote clipboard sync, wireless file transfers, screen mirroring, and SMS management.

- **[ClipboardFusion (Binary Fortress)](https://clipboardfusion.com)**  
  Windows and cross-platform clipboard manager featuring cloud-synced clipboard history, C# macro text scrubbing, and hotkeys.

- **[ClipDo](https://clipdo.app)**  
  Cloud-enabled clipboard productivity and cross-device snippet syncing utility built for rapid text reuse and multi-device access.

- **[Raycast (Cloud Sync Clipboard History)](https://raycast.com)**  
  Keyboard-driven launcher for macOS and Windows featuring rich searchable clipboard history with end-to-end encrypted cloud synchronization across devices.


## Open-Source GitHub Projects

- **[baiyuze/pasteferry](https://github.com)**  
  Open-source cross-device clipboard sharing and synchronization utility designed for fast, lightweight text and snippet transfer across desktop and mobile environments.

- **[KDE Connect (`KDE/kdeconnect-kde`)](https://github.com)**  
  Flagship open-source multi-platform continuity suite connecting Linux, Windows, macOS, Android, and iOS devices over local Wi-Fi for instant shared clipboard, file transfer, and remote input.

- **[CopyQ (`hluk/CopyQ`)](https://github.com)**  
  Advanced cross-platform open-source clipboard manager for Windows, macOS, and Linux featuring searchable/editable history, custom tabs, scripting, and encrypted storage.

- **[Ditto (`sabrogden/Ditto`)](https://github.com)**  
  Popular open-source Windows clipboard extension saving copied text, images, and HTML with network clipboard sharing across multiple PCs on the same LAN.

- **[Maccy (`p0deje/Maccy`)](https://github.com)**  
  Lightweight, native open-source clipboard manager for macOS engineered for speed, keyboard-first fuzzy filtering, and zero network bloat.

- **[Bitwarden (`bitwarden/clients` & `bitwarden/server`)](https://github.com)**  
  Leading open-source, self-hostable end-to-end encrypted vault and `Bitwarden Send` platform for securely syncing sensitive passwords, notes, and files across every OS and browser.

- **[SyncClipboard (`Jeric-X/SyncClipboard`)](https://github.com)**  
  Cross-platform open-source clipboard synchronization tool supporting text, images, and files across Windows, macOS, Linux, and Android via self-hosted WebDAV or built-in server.

- **[ClipCascade (`Sathvik-Rao/ClipCascade`)](https://github.com)**  
  Lightweight, self-hostable open-source real-time clipboard syncing application using WebSockets and end-to-end encryption across Windows, macOS, Linux, and Android.

- **[LocalSend (`localsend/localsend`)](https://github.com)**  
  Cross-platform open-source AirDrop alternative built in Flutter for securely sharing text snippets, clipboard contents, and files over local Wi-Fi with zero internet dependency.

- **[Cliphist (`sentriz/cliphist`)](https://github.com)**  
  Fast, Wayland-native open-source clipboard history manager for Linux written in Go that pipes cleanly into `rofi`, `wofi`, or `fzf`.

- **[GPaste (`Keruspe/GPaste`)](https://github.com)**  
  Robust open-source clipboard management daemon and GNOME/GTK client for Linux supporting image history, password-manager exclusion, and CLI automation.

### Additional Strong Open-Source Options

- **[Lan-mouse (`feschber/lan-mouse`)](https://github.com)** and **[Input Leap (`input-leap/input-leap`)](https://github.com)** for open-source software KVM mouse/keyboard sharing with seamless cross-computer clipboard synchronization.
- **[SharedClipboard / Clipto-Alternatives (`gclip` / `xclip` + SSH tunnels)](https://github.com)** for lightweight Unix/Linux terminal clipboard piping (`xclip`, `xsel`, `wl-clipboard`) over SSH.
- **[SnippetsLab / MassCode (`antonreshetov/massCode`)](https://github.com)** for open-source cross-device developer code snippet management synced via Git or cloud folders.
- **[MicroBin (`szabodanika/microbin`)](https://github.com)** and **[PrivateBin (`PrivateBin/PrivateBin`)](https://github.com)** for self-hosted, zero-knowledge encrypted pastebins to share clipboard contents via ephemeral URLs.
- **[Syncthing (`syncthing/syncthing`)](https://github.com)** for continuous, decentralized peer-to-peer file and folder synchronization across all desktop and mobile platforms.

**Frameworks for building custom systems**: Combine **KDE Connect** or **LocalSend** for instant LAN clipboard/file transfer, **SyncClipboard** or **ClipCascade** for self-hosted internet-wide sync, and **CopyQ** or **Maccy** for deep local clipboard history.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Support & Share

If you find this curated list helpful, consider supporting the project:

- ⭐ **Star this repository** to help others discover it.
- 🍴 **Fork & Share** it with your team, friends, or community on X/Twitter, LinkedIn, and Reddit.
- ☕ **Buy me a coffee / Sponsor** my open-source work on [GitHub Sponsors](https://github.com) — featuring tiers for profile badges, README shoutouts, logo placements, and prioritized bug fixes/features!

[![Sponsor @ishandutta2007](https://shields.io)](https://github.com)

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Clipboard managers and cross-device sync utilities frequently capture sensitive data such as passwords, 2FA codes, and API keys; configure password-manager ignore rules (`x-kde-passwordManagerHint` / concealed types) and enable end-to-end encryption when syncing across devices.
- Self-hosted clipboard relay servers exposed over the public internet must use HTTPS/WSS transport encryption and strong authentication.

---

**Made for multi-device power users, software developers, privacy advocates, and open-source contributors.**  
Let's make clipboard sharing and cross-device continuity more open, private, and seamless.
