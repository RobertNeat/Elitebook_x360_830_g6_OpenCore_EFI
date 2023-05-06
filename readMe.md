# Elitebook x360 830 G6
[created 07.05.2023]

Hackintosh EFI files for first boot (minimal_EFI) and for final usage (full_EFI). The development of those files are consistent with OpenCore project [https://dortania.github.io/OpenCore-Install-Guide/].

## To update files:
Follow instructions on project website:
[https://dortania.github.io/OpenCore-Post-Install/universal/update.html#updating-opencore]

## Files:
- minimal_EFI - files needed to boot into system and stock install on that hardware platform
- full_EFI - files that include:
    - cpu power management (it is implemented by default),
    - battery readouts (battery precentage icon and charging status),
    - built in audiocard kexts (alcid=18),
    - excluded logs during boot,
    - added "DisableRtcChecksum" - to calm RTC clock from screaming during boot
- HpSetup.txt - exported bios settings through "HP Replicated Setup"

## Hardware specs:
- CPU: i5-8265U 1.6GHz 1.80GHz
- GPU: Intel UHD Graphics 620
- Disc: 256GB M.2 2280 PCIe NVMe (MZ-VLW2560)
- Laptop model: HP EliteBook x360 830 G6
- Wifi Chipset: WCSAX200
	(http://en.techinfodepot.shoutwiki.com/wiki/Intel_Wi-Fi_6_AX200_(AX200NGW))
  

## What works partially:
- trackpad - works hardly

## What works perfectly:
- wifi - connects and transmit
- bluetooth - not tested with bluetooth devices