# Mac TCI DX Cluster · by GW3JVB

A native macOS DX cluster app for receiving spots from Telnet clusters and connecting to external TCI radio servers.

## Download

**[Download the latest Mac installer](https://github.com/reflectingme/Mac-TCI-DX-Cluster/releases/latest)** · [Release notes and all downloads](https://github.com/reflectingme/Mac-TCI-DX-Cluster/releases)

Version 0.1.3 requires **macOS 14 or later** and includes **Apple Silicon and Intel** builds. The DMG is **Developer ID-signed and notarised by Apple**. Early-user feedback is welcome; Intel and macOS 14 runtime testing remain to be confirmed.

1. Open the downloaded DMG.
2. Drag **Mac TCI DX Cluster** into **Applications**.
3. Launch it and allow **Local Network** access when prompted.

Use the `.dmg` asset. GitHub's automatically generated “Source code” ZIP/TAR files contain this downloads repository, not the installer or private application code.

## Features

- Multiple saved Telnet cluster profiles and simultaneous connections, with merged or separate spot lists.
- Band, mode and continent filters shared by the displayed list and automatic forwarding.
- Three independent outgoing TCI connections, with selectable spot-forwarding and click-to-tune targets. Hide unused connection cards in either layout.
- Optional mode selection from explicit reports or UK / Region 1 frequency estimates.
- Consolidated reports, source details, country/flag columns and saved column arrangements.
- Cluster history retrieval, manual spot posting and an optional current-VFO frequency/mode snapshot.
- Top or collapsible sidebar controls, light/dark appearance, searchable in-app Help and GitHub update checks.
- Saved table text size with Smaller/Default/Larger controls and Command + / Command − / Command 0 shortcuts, suggested by Andy (M7SBC).

- Read-only local RUMlogNG integration with callsign, DXCC and continent worked/needed checks across band and mode, combined using Match any or Match all.
- Configurable row highlights, an exact-callsign watchlist and automatic explanations of needed spots.
- Optional sound and macOS notifications with alert-band choices and repeat suppression.
- Formatted release notes in the update window, with headings, emphasis and clickable links.

The app connects to TCI servers supplied by radio-control software. It does not host a TCI server or provide direct USB/CAT radio control. Server-specific behaviour is described in the in-app Help.

RUMlogNG checks use the selected local `.rlog` file and never modify it. Needed means absent from that log, not confirmed award credit. Other loggers and internal iCloud databases are not supported in this version.

## Help and support

Use **Help → In-app Help** or visit **[Discord support](https://discord.gg/jUZR3x9R4M)** for setup help, feedback and feature requests.

Created by **GW3JVB**. Testing by **Andy · [M7SBC](https://www.qrz.com/db/M7SBC)**.

Free to use, with optional PayPal and Buy Me a Coffee donation links in the app. This public repository contains downloads, release notes and documentation. Application source code is maintained privately.
