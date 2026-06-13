# Archmox — Open Source Virtualization Stack for Arch Linux

**Sponsored and maintained by the [AcreetionOS Project](https://acreetionos.org)**

Archmox ports the proven Proxmox VE, Backup Server, and Mail Gateway stack to the Arch Linux ecosystem — all built with PKGBUILDs, all on `pacman`. No .deb dependencies, no Debian paths — pure Arch.

## The Fleet

| Service | Domain | Description |
|---|---|---|
| **Main Site** | [archmox.acreetionos.org](https://archmox.acreetionos.org) | Project landing page |
| **PVE** | [pve.archmox.acreetionos.org](https://pve.archmox.acreetionos.org) | Virtual Environment |
| **PBS** | [pbs.archmox.acreetionos.org](https://pbs.archmox.acreetionos.org) | Backup Server |
| **PMG** | [pmg.archmox.acreetionos.org](https://pmg.archmox.acreetionos.org) | Mail Gateway |
| **Docs** | [docs.archmox.acreetionos.org](https://docs.archmox.acreetionos.org) | Documentation |
| **CDN** | [cdn.archmox.acreetionos.org](https://cdn.archmox.acreetionos.org) | ISOs & Packages |

## Components

- **Proxmox VE** — KVM + LXC virtualization with web management
- **Proxmox Backup Server** — Content-addressable, deduplicated backup (Rust)
- **Proxmox Mail Gateway** — SMTP proxy with spam filtering
- **Software-Defined Storage** — ZFS, Ceph, LVM
- **HA Clustering** — Corosync + resource management
- **All on pacman** — PKGBUILDs, systemd, Arch-native paths

## Get Involved

- **Discord**: [discord.acreetionos.org](https://discord.acreetionos.org)
- **Matrix**: [#archmox:matrix.org](https://matrix.to/#/#archmox:matrix.org)
- **Mailing List**: [archmox-dev@lists.archmox.acreetionos.org](mailto:archmox-dev@lists.archmox.acreetionos.org)
- **Security**: [security@archmox.acreetionos.org](mailto:security@archmox.acreetionos.org)

## License

Archmox is 100% Open Source under the GNU Affero General Public License v3 or similar FOSS licenses. Archmox&reg; is a pending trademark of the Archmox project.

Proxmox&reg; is a registered trademark of Proxmox Server Solutions GmbH. Archmox is an independent community project and is not endorsed by or affiliated with Proxmox Server Solutions GmbH.
