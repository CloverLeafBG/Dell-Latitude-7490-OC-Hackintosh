# Dell-Latitude-7490-OC-Hackintosh

OpenCore based EFI for Dell Latitude 7490 


![Dell Github](https://user-images.githubusercontent.com/93620854/212483987-b0142f06-32e7-4b35-bacb-cc1947acd4a5.png)







## Tested macOS Version

- macOS Catalina 10.15.7
- macOS BigSur 11.7.3
- macOS Monterey 12.6.3
- macOS Ventura 13.2


## System Configuration

- CPU:  Intel Core i7-8650U
- iGPU: Intel UHD Graphics 620
- RAM:  16GB DDR4 2400Mhz
- SSD:  WD Blue SN570 500GB
- WiFi: BCM94360NG
- Display: 1920*1080 FullHD IPS
- Sound Card: Realtek ALC256
- LAN: Intel I219-LM

### BIOS Version

1.30.0


### Bootloader

OpenCore 0.8.8

### SMBIOS

MacBookPro15,2


## BIOS Settings

- Boot mode: UEFI
- Fast Boot: Minimal
- SecureBoot: Disable
- SATA Mode: AHCI 
- Intel SGX: Software Controlled


## What's working

 
 - [x] CPU Speedstep

 - [x] iGPU acceleration

 - [x] Battery Management
 
 - [x] Sleep/Wake
 
 - [x] Internal Speakers
 
 - [x] Internal Microphone
 
 - [x] WiFi (2.4Ghz + 5Ghz)
 
 - [x] Bluetooth

 - [x] Ethernet

 - [x] HDMI + audio over HDMI

 - [x] Touchpad with Gestures + Trackpad + Buttons

 - [x] Web Camera

 - [x] USB 3.0

 - [x] MicroSD card reader 

 - [x] Native hotkeys support with Fn keys (Volume Fn+F2/F3 and Screen Brightness Fn + F11/F12)
 
 - [x] USB-C charging

 - [x] USB-C DP-alt Mode
  
 - [x] USB-C Data transfer
 
 - [x] Thunderbolt (needs to plug a device before boot)
 
 - [x] Handoff, Airdrop & Sidecar

 - [x] FileVault 2
 


## What's not working

- [ ] Fingerprint sensor
- [ ] Smart card reader

## What's not tested yet

- WWAN card

## Additional Notes

Don't forget to generate your own SMBIOS with https://github.com/corpnewt/GenSMBIOS. 

- ENJOY!
