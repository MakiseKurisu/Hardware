# Model

[Dell XPS 8500 Special Edition](https://www.dell.com/support/home/us/en/19/product-support/product/xps-8500/docs)

# Operating System

[Microsoft Windows Pro Semi-Annual Channel 64-bit](https://docs.microsoft.com/en-us/windows/deployment/update/waas-overview#semi-annual-channel)

# Role(s)

* Main destkop
* Client PC
* [Plex Media Server](https://www.plex.tv/media-server-downloads/) server
* Offsite backup client

# CPU

[Intel Core i7-3770 Processor](https://ark.intel.com/content/www/us/en/ark/products/65719/intel-core-i7-3770-processor-8m-cache-up-to-3-90-ghz.html)

# RAM

32 GB (2 x [Crucial 16GB Kit (2 x 8GB) DDR3L-1600 UDIMM](https://www.crucial.com/usa/en/ct2k102464bd160b))

# Storage

## Boot/OS

[Samsung 860 EVO mSATA 1 TB SSD](https://www.samsung.com/us/computing/memory-storage/solid-state-drives/ssd-860-evo-msata-1tb-mz-m6e1t0bw/) (SATA 3.0, NTFS)

## User [Known Folders](https://docs.microsoft.com/en-us/windows/win32/shell/known-folders)

[Western Digital Gold WD101KRYZ 10 TB HDD](https://www.wd.com/content/dam/wdc/website/downloadable_assets/eng/spec_data_sheet/2879-800074.pdf) (SATA 3.0, NTFS)

## [StableBit DrivePool](https://stablebit.com/DrivePool)

* [HGST Travelstar 7K1000 0J22423 1 TB HDD](https://documents.westerndigital.com/content/dam/doc-library/en_us/assets/public/western-digital/product/hgst/travelstar-7k-series/data-sheet-travelstar-7k1000.pdf) (SATA 3.0, NTFS)
* [Toshiba MQ01ABF050 500 GB HDD](https://toshiba.semicon-storage.com/content/dam/toshiba-ss/asia-pacific/docs/product/storage/product-manual/cHDD-MQ01ABFxxx-Product-Overview.pdf) (SATA 2.0, NTFS)
* [Seagate Barracuda 7200.12 ST3500418AS 500 GB HDD](https://www.seagate.com/staticfiles/support/disc/manuals/desktop/Barracuda%207200.12/100529369b.pdf) (SATA 2.0, NTFS)

# Expansion Cards

## Graphics

[AMD Radeon 7870 HD GHz Edition](https://www.techpowerup.com/gpu-specs/radeon-hd-7870-ghz-edition.c339) (AMD apparently no longer has a product page for this model)

# Network Interface Cards

## Wired

RealTek Semiconductor RTL8168/8111 PCI-E Gigabit Ethernet NIC

## Wireless

[Intel Dual Band Wireless-AC 7260 AC 2x2 HMC WiFi Adapter](https://www.intel.com/content/dam/www/public/us/en/documents/product-briefs/dual-band-wireless-ac-7260-bluetooth-brief.pdf) (Shipped with [Atheros AR5B225](https://www.amazon.com/Atheros-AR5B225-Wireless-Bluetooth-Better/dp/B00BTWI81G))

# Optical Disc Drive

[Philips/Lite-on PLDS BD-RE DH-8B2SH15B](https://www.dell.com/support/home/us/en/04/drivers/driversdetails?driverid=wjcwm) (SATA 3.0) - Installed in [Vantec NexStar DX](https://github.com/jdrch/Hardware/blob/master/Dell%20XPS%208500%20Special%20Edition.md#enclosures)

# Backup

## Device Backup Target Application

[Veeam Backup & Replication Community Edition](https://www.veeam.com/virtual-machine-backup-solution-free.html) running on [Dell Inspiron 560](https://github.com/jdrch/Hardware/blob/master/Dell%20Inspiron%20560.md)

## Device Backup Source Application

[Veeam Agent for Microsoft Windows FREE](https://www.veeam.com/windows-endpoint-server-backup-free.html)

## Filesystem Versioning

* [Volume Shadow Copy](https://docs.microsoft.com/en-us/windows/win32/vss/volume-shadow-copy-service-overview)
* [ShadowExplorer](https://www.shadowexplorer.com/)

## OS Versioning

[System Restore](https://docs.microsoft.com/en-us/windows/win32/sr/system-restore-reference)

## Offsite Files Backup

[Duplicati](https://www.duplicati.com/) to OneDrive for [Office 365 Home](https://www.microsoft.com/en-us/p/office-365-home/cfq7ttc0k5dm). Since files are synced among clients using [Resilio Sync Home Pro](https://github.com/jdrch/Hardware/blob/master/Dell%20XPS%208500%20Special%20Edition.md#real-time-p2p-file-sync), only 1 offsite backup client PC is needed

## Real-time P2P File Sync

[Resilio Sync Home Pro](https://www.resilio.com/individuals/)

# 24/7/52 Applications

* [TeamViewer for Windows](https://www.teamviewer.com/en-us/download/windows/)
* [CyberPower PowerPanel Personal Windows](https://www.cyberpowersystems.com/product/software/powerpanel-personal-windows/)
* Plex Media Server
* Resilio Sync Home Pro
* Veeam Agent for Windows FREE
* [CrystalDiskInfo Standard Edition](https://crystalmark.info/en/software/crystaldiskinfo/)
* [PowerToys](https://github.com/microsoft/PowerToys)
* Duplicati
* StableBit DrivePool
* [qBittorrent](https://www.qbittorrent.org)
* [Pushbullet](https://www.pushbullet.com/)
* [AMD Catalyst Control Center](https://www.amd.com/en/support/graphics/amd-radeon-hd/amd-radeon-hd-7000-series/amd-radeon-hd-7870-ghz-edition)
* [Avira Antivirus Pro](https://www.avira.com/en/antivirus-pro)
* [No-IP Dynamic DNS Update Client (DUC) for Windows](https://www.noip.com/download?page=win)
* OneDrive
* Bluetooth Devices
* Windows Security
* Skype

# Peripherals

## Mouse & Keyboard

[Logitech MK850 Performance](https://www.logitech.com/en-us/product/mk850-wireless-keyboard-mouse-combo). Shared with [Dell OptiPlex 390](https://github.com/jdrch/Hardware/blob/master/Dell%20OptiPlex%20390-1%20SFF.md) and Samsung Galaxy Note9

## Enclosures

[Vantec NexStar DX](http://www.vantecusa.com/products_detail.php?p_id=51&p_name=Vantec) (USB 3.1 Gen 1) - Contains [Philips/Lite-on PLDS BD-RE DH-8B2SH15B](https://github.com/jdrch/Hardware/blob/master/Dell%20XPS%208500%20Special%20Edition.md#optical-disc-drive)

## UPS

[CyberPower CP1500PFCLCD](https://github.com/jdrch/Hardware/blob/master/UPS.md#battery-backed-up-devices)

## Printers

[HP Deskjet 5650](https://support.hp.com/us-en/product/hp-deskjet-5650-printer-series/304441)

## Scanners

[Epson WorkForce GT-1500](https://epson.com/Support/Scanners/WorkForce-Series/Epson-WorkForce-GT-1500/s/SPT_B11B190011)

## Webcam

[Logitech C922 Pro Stream HD](https://www.logitech.com/en-us/product/c922-pro-stream-webcam)

## Fingerprint Reader

[Kensington VeriMark Fingerprint Key](https://www.kensington.com/p/products/security/biometric/verimark-fingerprint-key-fido-u2f-for-universal-2nd-factor-authentication-windows-hello/)

## Speakers

[Logitech Z-2300 2.1 Speaker System](https://support.logi.com/hc/en-us/articles/360024328433)

## Headphones

[Sony MDR-7506](https://pro.sony/ue_US/products/headphones/mdr-7506)
External Monitors

# External Monitors

* [Dell UltraSharp U2713HM](https://github.com/jdrch/Hardware/blob/master/Monitors.md#connected-devices-3)
* [NEC EA275UHD-BK](https://github.com/jdrch/Hardware/blob/master/Monitors.md#connected-devices-2)
* [ASUS ProArt PA248Q](https://github.com/jdrch/Hardware/blob/master/Monitors.md#connected-devices-4)
