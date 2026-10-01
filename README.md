# Sloth Client

Sloth Client is a Windows Minecraft launcher and in-game client with original pink sloth artwork.

## Download

**[Download Sloth Client 0.0.5 for Windows](https://github.com/iMurrz/sloth-client-releases/releases/download/v0.0.5/Sloth-Client-Setup-0.0.5.exe)**

[Release notes and integrity signatures](https://github.com/iMurrz/sloth-client-releases/releases/tag/v0.0.5)

**Unsigned development release:** trusted Windows publisher signing is postponed. Windows may display an unknown-publisher or SmartScreen warning. Separate Ed25519 integrity signatures do not replace Windows publisher trust. Install this version manually once to replace older builds with failing update checks. This development build checks for newer releases, downloads and verifies the signed Sloth update feed and installer, then offers Install and restart inside the client. Installation requires explicit confirmation and Minecraft must be closed. Production updates still require trusted Windows publisher signing.

Close Minecraft and the client, and back up important instances before installation. Current releases use the full Sloth identity: native mod/package identifiers, application ID, resource namespace and profile folders. Other computers require manual migration of previous profiles. Installation may appear as a separate entry because the application ID has changed. Preserve backups before removing previous installations.

## Features

- Sloth Client launcher and native menus, editable HUDs and utility settings. Home banner uses the original pink Sloth logo and Sloth wording.
- Mod and instance management, resource-pack support, launch history and recovery tools.
- ViaFabricPlus is included and on by default for supported server versions; select a protocol in Multiplayer.
- Local saved friends, favorites and current-server activity.
- Optional Minecraft Services friends lookup; real-account operation remains unverified.
- CurseForge website browsing and pack ZIP inspection. API downloads require an approved API key and compatible pack versions.

Minecraft is pinned to1.21.11/Fabric. The default server address is localhost; configure your server address as needed. Custom prison HUD integration requires a server bridge using sloth:hud. Third-party mod combinations, live gameplay, installation and authenticated service flows have not all been verified.

## Integrity and status

Source checks, native compilation, package/source comparison, resource-pack/native-JAR equality, detached Ed25519 signatures and full inventory verification are checked locally. This does not guarantee the absence of unknown vulnerabilities. Public-trust signing, own Microsoft application registration, distribution/privacy reviews and managed runtime maintenance remain work in progress.

This repository distributes compiled artifacts and documentation. Private development source, account data and private signing keys are not uploaded.

Sloth Client is not an official Minecraft product and is not approved by or associated with Mojang, Microsoft or CurseForge.
