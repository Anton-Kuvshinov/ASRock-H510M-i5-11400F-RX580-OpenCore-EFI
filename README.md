# ASRock-H510M-i5-11400F-RX580-OpenCore-EFI
"Working OpenCore EFI for ASRock H510M, Intel i5-11400F and AMD RX 580 Hackintosh"

# OpenCore EFI for ASRock H510M / i5-11400F / RX 580 Hackintosh

Ready-to-use EFI folder for Hackintosh based on ASRock H510M, Intel Core i5-11400F and AMD Radeon RX 580.

## 🖥 Hardware Specifications
| Component | Model |
|-----------|-------|
| Motherboard | ASRock H510M-HDV/M.2 SE |
| CPU | Intel Core i5-11400F (Comet Lake) |
| GPU | Sapphire RX 580 8GB (natively supported) |
| RAM | 16GB DDR4 (2x8GB) |
| Storage | ARDOR GAMING NVMe 1TB |
| LAN | Realtek RTL8111 |
| Audio | Realtek ALC897 |

## ✅ What's Working
- [x] macOS Sequoia / Sonoma installation
- [x] AMD RX 580 graphics (full acceleration, no patches needed)
- [x] Ethernet (RealtekRTL8111 kext)
- [x] Onboard audio (AppleALC, layout-id automatically detected)
- [x] USB ports (mapped correctly)
- [x] Sleep / Wake
- [x] NVRAM
- [x] FileVault
- [x] iMessage / FaceTime (with proper serial number)

## ⚠️ Important Notes
- **Generate your own serial numbers** in `PlatformInfo` section of `config.plist` (use GenSMBIOS)
- **BIOS Settings:**
  - Disable Secure Boot
  - Set SATA mode to AHCI
  - Disable CSM (Compatibility Support Module)
  - Enable XMP for RAM (optional)

## 📦 OpenCore Version
- OpenCore **1.0.3** (or your version)

## 🚀 How to Use
1. Download the EFI folder
2. Replace the EFI folder on your USB installer or internal drive
3. Boot and enjoy macOS!

## 📝 Credits
- [OpenCore Team](https://github.com/acidanthera/OpenCorePkg)
- [Dortania's Guide](https://dortania.github.io/OpenCore-Install-Guide/)

## 📥 Download
Check the [Releases](link) page for the latest version.
