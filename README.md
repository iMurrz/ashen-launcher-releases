# Ashen Launcher

Windows Minecraft launcher with an original Ashen client interface and the full Murful resource pack.

## Install or update

Download the installer from [the latest release](https://github.com/iMurrz/ashen-launcher-releases/releases/latest). Launchers connected to this repository can use **Update Launcher** to check, download and restart into a verified update. Older builds without the configured feed need a manual installer update once.

## Current features

- CurseForge Modpacks: official website browsing, optional approved API-key search/downloads, ZIP requirement previews and separate Minecraft 1.21.11 Fabric pack instances. Unsupported loaders/versions need another launcher.
- Mod Manager: local Fabric imports, search, filters, reversible personal mod toggles, file fingerprints and common compatibility notices.
- Launch History: the last 100 launches, including session length and exit status when the launcher remains open.
- Setup Studio: performance presets, storage checks and support-report export.
- Separate instances, favourites, testing copies and verified recovery snapshots.
- Modrinth browsing for mods, resource packs and shaders; Ctrl+K quick actions.
- Original Ashen menus, HUD and utility modules; full Murful fonts and item, armor and tool textures.
- All custom cosmetics removed.

Minecraft is pinned to 1.21.11 with Fabric. Compatibility notices do not guarantee every third-party mod combination.

## Release integrity

Each release includes an installer, blockmap, update feed and Ashen Ed25519 signature. The launcher verifies the update download hash and signature before offering installation. This signature is separate from Windows publisher certificates. This repository distributes releases only; it does not contain account data, launcher source or private signing keys.

Long-term support requires continued maintenance as Minecraft, Java, Electron, Windows and Microsoft sign-in evolve.

Unofficial community software, not affiliated with Mojang or Microsoft.

CurseForge in-app features require an approved developer API key saved locally in the Modpacks section. Website browsing and ZIP review work without a key. Live authenticated CurseForge requests have not been verified without a supplied key. Ashen is not affiliated with CurseForge.
