> NUC11BTMi7-hackintosh
## For NUC11th generation -NUC11BTMi7/i9,Support installation MacOS ventura


## Computer Configuration

- processor：Intel® Core™ i7-11700B Processor (24M Cache, up to 4.80 GHz)
- network：Intel® Ethernet Controller i225-LM
- Wireless network/Bluetooth：Intel® Wi-Fi 6E AX210
- Audio：USB Audio
- graphics card：HP 6600 XT
- Thunderbolt：2x Thunderbolt™ 4
- Memory：Corsair DDR4 16G 3200MHz*2
- harddisk1：HP EX950 2T
  
## Change log

- 6-4-2024
  - first submission
  - renew `OpenCore` `v1.0.0`
  - support `Ventura` Install and use
  
## bios settings

- BIOS Version：`DBTGL579.0070`
- Restore BIOS settings：`F9 - Optimal Defaults`

### Configuration

- Advanced
  - Advanced > `PCIE Resizable BAR Support: Disabled（Very important）`
  - Advanced > Video > `Primary Display: PEG Slot`
- Security
  - Security Features > `Intel VT for Directed I/O(VT-d)：Disabled`
- Boot
  - Secure Boot > `Secure Boot: Disabled`
  - boot Priority > `Fast Boot: Unchecked`

## hardware

- ❌  GPU acceleration：`Intel UHD Graphics`Unable to drive⚠️
- ✅ GPU acceleration：（`HP RX 6600 XT/Other driver-free graphics cards`Ready out of the box）
- ✅ Ethernet
- ✅ USB Audio
- ✅ USB A port
- ✅ NVMe SSD
- ✅ wireless network
- ✅ Bluetooth
software

## software

- ✅ Installers, app stores, app updates
- ✅ Updating MacOS directly from Apple （Incremental package upgrade requires setting the following two options，Otherwise you will not be able to receive the new version，Wait for the update to complete before restoring settings）⚠️

      `not selected：Config > Kernel - BlueToolFixup.kext / IntelBluetoothFirmware.kext / IntelBTPatcher.kext`

      `Add：Config > NVRAM-7C436110-AB2A-4BBB-A880-FE41995C9F82 > boot-args - revpatch=sbvmm`
- ✅ APFS, SSD pruning
- ✅ iMessage, iCloud, Siri, iTunes, other services
- ✅ Metal, GPU accelerated applications：**HP RX 6600 XT**
- ✅ time Machine
- ✅ sleep mode
- ✅ Shut down/sleep/wake up

## Hardware not tested⚠️

- SD card slot
- Thunderbolt 4 port

## Display of results

![61FADA55BAC270C04100F9FBEF7504C6](https://github.com/zpyangchina/NUC11BTMi7-hackintosh/assets/42115887/5fb87b03-180c-4282-9a94-9becb5e2d37b)

![B4CD1F2B3E4BFFF1240FF5109B366665](https://github.com/zpyangchina/NUC11BTMi7-hackintosh/assets/42115887/e54ca566-122b-400f-bf82-d69cd2ede8c6)

![697F2FC60C44D5846F2BFF4A4899F355](https://github.com/zpyangchina/NUC11BTMi7-hackintosh/assets/42115887/17566f32-6ef0-46df-aa46-cc69ab9e141c)

![C7B577EF0FF9EB0376FDB5B032252CC9](https://github.com/zpyangchina/NUC11BTMi7-hackintosh/assets/42115887/76eb1bfd-f41d-41ab-ad7d-246379f57b2a)

![9A7CB91E98497699A56F359EF6360F6B](https://github.com/zpyangchina/NUC11BTMi7-hackintosh/assets/42115887/ef93e0e8-4563-429f-ac7e-67735053fc40)



