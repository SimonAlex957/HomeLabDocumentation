# Hardware

Hardware inventory, specifications, and physical layout.

## Contents

- Host inventory and system identity
- CPU, memory, graphics, and motherboard details
- Storage layout and network interfaces

## Host Inventory

- Hostname: simonserver
- Operating system: Ubuntu 24.04.3 LTS
- Kernel: 6.8.0-101-generic
- Uptime at scan time: 45 days
- Hardware platform: TOSHIBA SATELLITE C50-B (PSCLUE-060077EN)

## Core Specifications

- CPU: Intel Core i3-4005U @ 1.70 GHz
- Cores/threads: 2 cores / 4 threads
- Virtualization: Intel VT-x supported
- RAM: 3.7 GiB total
- Swap: 3.7 GiB configured
- GPU: Intel Haswell-ULT integrated graphics

## Motherboard and BIOS

- System vendor: TOSHIBA
- Board: TOSHIBA ZSWAA (version 1.00)
- BIOS vendor: TOSHIBA
- BIOS version: 1.40
- BIOS date: 2014-11-27

## Storage Inventory

- Primary disk: /dev/sda (SanDisk, 465.8G)
	- /dev/sda2: 2G ext4 mounted at /boot
	- /dev/sda3: LVM PV hosting ubuntu-vg/ubuntu-lv (463.8G ext4 mounted at /)
- Secondary disk: /dev/sdb (Tech, 1.8T ext4 mounted at /mnt/heather_drive)
- Optical drive: /dev/sr0

## Network Hardware

- Wired NIC: Realtek RTL810xE PCIe Fast Ethernet (enp3s0)
- Wireless NIC: Qualcomm Atheros QCA9565/AR9565 (wlp4s0)
- Active primary LAN interface: enp3s0 (192.168.0.136/24)
- Additional virtual/tunnel interfaces present: wg0, tailscale0, docker bridges

