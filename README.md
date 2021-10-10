# Hackintosh-R5-3600-MSI-B450-Tomahawk-Max
### Hackintosh with BigSur 11.6 (20G165) 
### Opencore: 0.7.4

## Hardware:
    - Motherboard: MSI B450 Tomahawk Max
    - CPU: Ryzen R5 3600 @4.0 GHz
    - RAM: 32GB(4x8GB) @3000MHz combine Hyperx and Crucial
    - GPU: HIS RX 460 iCooler OC 2GB (vram elpida) -> flash bios to Sapphire (vram elpida also)
    - SSD1: Samsung 850 evo 250GB SATA for macOS
    - SSD2: Samsung PM981a 250GB M.2 2 PCIE for Win 10 
    - LAN Chipset: Realtek® RTL8111H Gigabit LAN
    - WiFI + BT Chipset: Intel AX200 802.11ax Wi-Fi 6, Bluetooth 5.0 in PCIe-1x
    - Audio Chipset: Realtek® ALC892 Codec
    - Audio USB sound card: ASUS Xonar-U7-MKII

## BIOS setings:
### Disabled:
    - Re-size Bar support
    - Above 4G Decoding (because it will of when set re-size bar off in this motherboard)
    - SR-IOV support
    - Data Link Feature (new in this bios, disable for ensure)
    - Serial(COM) Port
    - Wake up By ethernet
    - Viturlization: SVM Mode
    - NX Mode
    - Secure Boot
    - Chassis Instruction
### Enabled:
    - AHCI Mode
    - UEFI Only
    - USB XHCI Hand-off
    - Legacy USB support
    - Hyper threading
    - TPM (set on and it is still working)

### Bios Photos
![Advanced](/bios-config/advance-setting-1.jpeg)
![Advanced](/bios-config/advance-setting-2.jpeg)
![Advanced](/bios-config/advance-setting-3.jpeg)
![Advanced](/bios-config/advance-setting-4.jpeg)
![Advanced](/bios-config/advance-setting-5.jpeg)
![Advanced](/bios-config/advance-setting-6.jpeg)
![CPU-Advanced](/bios-config/oc-advance-cpu.jpeg)
![Security](/bios-config/security-1.jpeg)
![Security](/bios-config/security-2.jpeg)
![Security](/bios-config/security-3.jpeg)

### Overclock If you like
#### Overclock Profile use for import in BIOS
[OC-Profile](/bios-config/profiles/oc-profiles.ocb)


## What's Working?
- [x] Tested with macOS Big Sur 11.6, should work with lower version
- [x] QE/CI Graphics Of Sapphire Radeon RX 580
- [x] Restart and Shutdown. 
- [x] Rear Jack (Green) + Front Speaker Jack (Headphone)
- [x] HDMI Audio
- [x] HDMI Output
- [x] Display Port Audio
- [x] Display Port output
- [x] USB ports
- [x] ...

## What's not Working?
- [ ] iServices
- [ ] Jack mic (common problem with AMD Hackintosh using AppleALC kext)
- [ ] SideCar due to the lack of an iGPU
- [ ] ...
