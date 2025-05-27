# FirmwareResources
This document list all firmware related resources.

# Firmware and OS Specifications/Standards/Shows/Events Maintained by TonyLo

- [FirmwareResources](#firmwareresources)
- [Firmware and OS Specifications/Standards/Shows/Events Maintained by TonyLo](#firmware-and-os-specificationsstandardsshowsevents-maintained-by-tonylo)
  - [Shows/Events](#showsevents)
  - [Official Sites](#official-sites)
  - [Firmware AI](#firmware-ai)
  - [Firmware and OS Architecture](#firmware-and-os-architecture)
  - [Specifications](#specifications)
    - [Bus Technology](#bus-technology)
    - [Remote Management Specifications](#remote-management-specifications)
    - [Industry Standard Specifications](#industry-standard-specifications)
    - [File System and Disc Format](#file-system-and-disc-format)
    - [File Format](#file-format)
  - [Tools](#tools)
  - [Compilers/ToolChains](#compilerstoolchains)
## Shows/Events
List of firmware related shows/events.

|Name|Organizer|Location|Target Segment|Notes|
|:-----|:-----|:-------|:-------|:------|
|[CES](https://www.ces.tech/)|CTA|Las Vegas, US||Consumer Electronics Show<br>Jan 7-10, 2025<br>Jan 6-9, 2026|
|[Computex](https://www.computextaipei.com.tw/)|[TAITRA](https://en.taitra.org.tw/)|Taipei,Taiwan||May 20-23, 2025<br>June 2-5, 2026|
|[Embedded World](https://www.embedded-world.de/)||Nuremburg,Germany||Mar 10-12, 2026|
|[MWC](https://www.mwcbarcelona.com/)|GSMA|Barcelona, Spain||Mobile World Congress<br>Mar 6-9, 2025<br>Mar 2-5, 2026|
|[Apple (WWDC)](https://developer.apple.com/wwdc)|Apple|||Worldwide Developers Conference<br> June 9-13, 2025|
|[Google I/O](https://io.google)|Google||||
|[nVidia GTC](https://www.nvidia.com/gtc/)|nVidia|||May 21-22, 2025, Taipei<br>|
|[OCP Global Summit/Regional Summit](https://www.opencompute.org/)|OCP|||Open Compute Project<br>OCP APAC Summit Aug 5-6,2025, Taipei<br>OCP Global Summit Oct 13-16,2025, SanJose|

## Official Sites

List of Organizations, Company, Govermant sites which are firmware and OS related.

|Name|URL|Specifications|
|:-----------------|:-------------------|:----------------------------------|
|AMD|https://www.amd.com|
|AMPERE Computing|https://amperecomputing.com/|
|AMI|https://www.ami.com|Legacy BIOS<BR>UEFI<BR>BMC<BR>OpenBMC
|ARM|https://www.arm.com|ARM Architecture<BR>ARM TrustZone
|Bluetooth|https://www.bluetooth.com|Bluetooth Specifications<BR>Bluetooth Profiles
|Connectivity Standard Alliance|https://csa-iot.org/|Zigbee
|CoreBoot|http://www.coreboot.org|
|CXL|https://www.computeexpresslink.org/|Compute Express Link
|DMTF|https://www.dmtf.org|-[CADF](https://www.dmtf.org/standards/cadf)<br>-[CDM](https://www.dmtf.org/standards/cdm)<br>-[CLOUD](https://www.dmtf.org/standards/cloud)<br>-[CIM](https://www.dmtf.org/standards/cim)<br>-[CMDBf](https://www.dmtf.org/standards/cmdbf)<br>-[DASH](https://www.dmtf.org/standards/dash)<br>-[NETMAN](https://www.dmtf.org/standards/netman)<br>-[OVF](https://www.dmtf.org/standards/ovf)<br>-[PMCI](https://www.dmtf.org/standards/pmci)<br>-[REDFISH](https://www.dmtf.org/standards/redfish)<br>-[SMASH](https://www.dmtf.org/standards/smash)<br>-[SMBIOS](https://www.dmtf.org/standards/smbios)<br>-[VMAN](https://www.dmtf.org/standards/vman)<br>-[WBEM](https://www.dmtf.org/standards/wbem)<br>-[WS-MAN](https://www.dmtf.org/standards/ws-man)
|FIDO Alliance|https://fidoalliance.org/|User Authentication
|FiRa|https://www.firaconsortium.org/|FiRa Consortium, UWB promoter group
|IETF - Internet Exchange Task Force|https://www.ietf.org/|[WG list](https://datatracker.ietf.org/wg/)
|GNU|https://www.gnu.org/|GNU OS, Software, Tools, Compilers
|HDMI|https://www.hdmi.org|HDMI<BR>
|INCITS T10|https://www.t10.org|SCSI<BR>SAS
|INCITS T13|https://www.t13.org|ATA/ATAPI<BR>
|Intel|https://www.intel.com|Intel Processor/Chipsets<BR>XHCI<BR>eSPI<BR>AC97
|ITE|https://www.ite.com.tw/en|EC, SensorHub
|JEDEC|https://www.jedec.org|Microelectronics Standard<BR>eMMC<BR>UFS
|Linaro|https://www.linaro.org/|ARM and open source projects
|MCC|https://www.mcc-us.com/|I2C Bus Analyzer
|Microchip|https://www.microchip.com/|EC, AI
|MIPI Alliance|https://www.mipi.org|MIPI<BR>
|Microsoft|https://www.microsoft.com|Microsoft Windows<BR>
|NIST|https://www.nist.gov|NIST Standards
|NVM Express|https://www.nvmexpress.org|NVMe<BR>
|Nuvoton|https://www.nuvoton.com/|EC, AI
|NXP|https://www.nxp.com/|
|OCP|https://www.opencompute.org/|Open Compute Project<br>Datacenter, 5G, Telco, DC-MHS<br>
|OpenBIOS|https://www.openbios.info/|
|OpenBMC|https://www.openbmc.org/|OpenBMC
|Open Network|https://opennetworking.org/|
|Open RAN|https://telecominfraproject.com/openran/|
|Open RAN Policy Coalition||
|O-RAN Alliance|https://www.o-ran.org/|
|PCI-SIG|https://pcisig.com/|PCI<BR>PCI Express<BR>
|RISC-V|https://riscv.org/|RISC_V architecture
|SATA-IO|https://sata-io.org/|Serial ATA
|SD Association |https://www.sdcard.org|SDCard<BR>MicroSD<BR>SD Express<BR>SDIO<BR>iSDIO
|SOAFFE|https://www.soafee.io/|
|Trusted Computing Group|https://trustedcomputinggroup.org/|TPM
|u-bmc|https://u-bmc.readthedocs.io/|
|U-Boot|https://www.denx.de/wiki/U-Boot|
|UALink Consortium|https://ualinkconsortium.org/|AI Accelerators interconnect bus
|UEFI|https://www.uefi.org|UEFI<BR>UEFI PI<BR>UEFI SCT<BR>ACPI
|USB|https://www.usb.org|USB Specification<BR>USB Device Classes<BR>USB PD
|VESA|https://vesa.org/|VESA spec


## Firmware AI

|Sites|URL|Notes|
|:-----------------|:-------------------|:-----------------|
|LiteRT/Tensorflow Lite|https://ai.google.dev/edge/litert||
|tinyML|https://www.tinyml.org/|Tiny ML for MCUs|
|Pytorch|https://pytorch.org/executorch-overview|ExecuTorch|
|Rasberry Pi AI|https://www.raspberrypi.org/courses/ai-and-machine-learning||
|Microchip AI|https://www.microchip.com/en-us/solutions/technologies/machine-learning|||
|Nuvoton AI|https://www.nuvoton.com/ai/|||

## Firmware and OS Architecture

Firmware and OS architecture sites

|Firmware/OS Architecture|URL|Status|Notes|
|:-----------------|:-------------------|:-----------------|:-----------------|
|ACRN Hypervisor|https://projectacrn.org/||ACRN Hypervisor
|ARM Trusted Firmware|https://www.trustedfirmware.org/||TF-A, TF-M, OP-TEE, TF-RMM, Hafnium
|Caliptra|https://github.com/chipsalliance/Caliptra||RoT
|CoreBoot|http://www.coreboot.org|
|Global Platform|https://globalplatform.org/||TEE
|Intel Slimboot|https://www.intel.com.tw/content/www/tw/zh/design/products-and-solutions/technologies/slim-bootloader/overview.html||
|Linux Boot|https://www.linuxboot.org/|
|OpenBIOS|https://www.openbios.info/|
|OpenBMC|https://www.openbmc.org/|
|Open System Firmware|https://www.opencompute.org/projects/open-system-firmware|
|Project Mu|https://microsoft.github.io/mu/||Microsoft Open Source Firmware|
|RISC-V|https://riscv.org/||RISC_V architecture|
|SeaBIOS|https://www.seabios.org|Inactive|Legacy BIOS
|SeaVGABios|https://seabios.org/SeaVGABIOS|Inactive|Open Source VGA BIOS
|u-bmc|https://github.com/u-root/u-bmc|
|U-Boot|https://www.denx.de/wiki/U-Boot|
|USF|https://www.intel.com/content/www/us/en/developer/articles/technical/universal-scalable-firmware.html/||Universal Scalable Firmware|
|UEFI Firmware|http://www.uefi.org|
|UWB Alliance|https://uwballiance.org/|
|WiMedia Alliance|https://www.wimedia.org|
|Zephyr|https://zephyrproject.org/||Zephyr RTOS


## Specifications

### Bus Technology

|Specification|URL|Status|Notes|
|:-----------------|:-------------------|:-----------------|:-----------------|
|1394/Firewire|[OHCI v1.1](http://download.microsoft.com/download/1/6/1/161ba512-40e2-4cc9-843a-923143f3456c/ohci_11.pdf)|Inactive|
|AC97 Specification|[ICH7 AC97 Programmers Manual](https://www.intel.com/content/dam/doc/manual/io-controller-hub-7-hd-audio-ac97-manual.pdf)|Inactive|
|Access Bus Specification|[v3.0](http://www.mcc-us.com/abspec30.zip)|
|AGP Specification|[v1.0](http://www.playtool.com/pages/agpcompat/agp10.pdf)<br>[v3.0](http://www.playtool.com/pages/agpcompat/agp30.pdf)|Inactive|
|AGP Pro Specification|[v1.1a](https://web.archive.org/web/20021003222339/http://www.agpforum.org/downloads/apro_r11a.pdf)|Inactive|
|ATA/ATAPI Specification|-[ACS-4 Rev.14](http://www.t13.org/Documents/UploadedDocuments/docs2016/di529r14-ATAATAPI_Command_Set_-_4.pdf)<br>-[ATA8 ACS](http://www.t13.org/documents/UploadedDocuments/docs2007/D1699r4a-ATA8-ACS.pdf)<br>[ATA8 ACS2](http://www.t13.org/Documents/UploadedDocuments/docs2009/d2015r2-ATAATAPI_Command_set_-_2_ACS-2.pdf)<br>-[ATAPI for CDROM 8020i rev2.6](http://www.bswd.com/sff8020i.pdf)<br>-ATA for Removable 8070i|
|Bluetooth|-[Bluetooth Specifications List](https://www.bluetooth.com/specifications)<br>-[Core Specification 6.1](https://www.bluetooth.com/specifications/specs/core-specification-6-1/)<br>-[Core Specification 6.0](https://www.bluetooth.com/specifications/specs/core-specification-6-0/)<br>-[Core Specification 5.4](https://www.bluetooth.com/specifications/specs/core-specification-5-4/)<br>-[Core Specification 5.3](https://www.bluetooth.com/specifications/specs/core-specification-5-3/)<br>-[Core Specification 5.2](https://www.bluetooth.org/docman/handlers/downloaddoc.ashx?doc_id=478726)<br>-[CSS 9](https://www.bluetooth.org/docman/handlers/DownloadDoc.ashx?doc_id=480305)<br>|
|CAN Bus/CAN XL/CAN-FD|-[CAN-FD Information](https://www.bosch-semiconductors.com/media/ip_modules/pdf_2/papers/icc14_2013_paper_mutter_1.pdf)<br>-[CAN XL](https://www.bosch-semiconductors.com/products/ip-modules/can-ip-modules/xl-can/)<br>-[CAN v2.0](http://esd.cs.ucr.edu/webres/can20.pdf)<br>-[CAN-FD v1.0](https://can-newsletter.org/assets/files/ttmedia/raw/e5740b7b5781b8960f55efcc2b93edf8.pdf)|
|CXL|https://www.computeexpresslink.org/||Compute Express Link
|eMMC Specification|[v5.1a](https://www.jedec.org/standards-documents/technology-focus-areas/flash-memory-ssds-ufs-emmc/e-mmc)|
|HDAudio Specification|[v1.0a](https://www.intel.com/content/dam/www/public/us/en/documents/product-specifications/high-definition-audio-specification.pdf)|
|HDMI Specification|-[v2.2](https://hdmiforum.org/wp-content/uploads/2025/01/CES-2025-HDMI-Forum-New-Spec-Release-20250106-EN.pdf?x70541&x34563)<br>-[v2.1b](https://www.hdmi.org/spec/hdmi2_1)|
|I2C Bus Specification|[v6.0](https://www.nxp.com/docs/en/user-guide/UM10204.pdf)|
|I2S Specification|[June 5, 1996](https://www.sparkfun.com/datasheets/BreakoutBoards/I2SBUS.pdf)|
|I3C Specification]|-[MIPI I3C Basic v1.0](https://resources.mipi.org/mipi-i3c-v1-download)<br>-[MIPI I3C v1.1](https://www.mipi.org/specifications/i3c-sensor-specification)<br>-[NXP I3C Training Video](https://www.nxp.com/design/training/improved-inter-integrated-circuit-i3c-standard:TIP-I3C-STANDARD)|
|LPC Specification|[v1.1](https://www.intel.com/content/dam/www/program/design/us/en/documents/low-pin-count-interface-specification.pdf)|
|MIPI Specification|[click](https://www.mipi.org/current-specifications)|
|NVLink|[Click](https://en.wikipedia.org/wiki/NVLink)||nVidia<br>NVLink Fusion|
|NVM Express(NVMe)|-[All Specifications](https://nvmexpress.org/developers/nvme-specification/)<br>-[NVMe Boot Specification v1.2 (Mar.11, 2025)](https://nvmexpress.org/wp-content/uploads/NVM-Express-Boot-Specification-Revision-1.2-2025.03.11-Ratified.pdf)<br>-[NVMe Command Set Specifications](https://nvmexpress.org/developers/nvme-command-set-specifications/)<br>-[NVMe Transport Specificaions](https://nvmexpress.org/developers/nvme-transport-specifications/)<br>-[NVMe-MI Specifications](https://nvmexpress.org/developers/nvme-mi-specification/)<br>-[NVM Express Base Specification v2.2 (Mar.11, 2025)](https://nvmexpress.org/wp-content/uploads/NVM-Express-Base-Specification-Revision-2.2-2025.03.11-Ratified.pdf)<br>-[NVM Express Base Specification 2.0a](https://nvmexpress.org/wp-content/uploads/NVMe-NVM-Express-2.0a-2021.07.26-Ratified.pdf)<br>-[NVMe Management Interface v1.1a](https://nvmexpress.org/developers/nvme-mi-specification/)|
|PCI/PCIExpress|-[Specification List](https://pcisig.com/specifications)<br>-PCI Express Base Specification Revision 7.0<br>-PCI Express Base Specification Revision 6.3<br>-[PCI Express Base Specification Revision 6.2](https://members.pcisig.com/wg/PCI-SIG/document/20590)<br>-[PCI Express M.2 Specification  Revision 5.1](https://members.pcisig.com/wg/PCI-SIG/document/20926?uploaded=1)<br>-[PCI Express U.2 Specification Revision 5.0](https://members.pcisig.com/wg/PCI-SIG/document/20654?uploaded=1)<br>-PCI Firmware Specification Revision 3.3<br>-[PCI Code and ID Assignment Revision 1.18](https://members.pcisig.com/wg/PCI-SIG/document/22141)|
|SCSI Specification|[click](https://www.t10.org/scsi-3.htm)|
|SD/SDIO/SD Express|-[All Specifications](https://www.sdcard.org/downloads/)<br>-[Latest WhitePapers](https://www.sdcard.org/downloads/pls/latest_whitepapers/)<br>-[SDIO Simplified Specification v3.0](https://www.sdcard.org/downloads/pls/pdf?p=PartE1_SDIO_Simplified_Specification_Ver3.00.jpg&f=PartE1_SDIO_Simplified_Specification_Ver3.00.pdf&e=EN_SSE1)<br>-[SD Host Controller Specification v4.20](https://www.sdcard.org/downloads/pls/pdf?p=PartA2_SD%20Host_Controller_Simplified_Specification_Ver4.20.jpg&f=PartA2_SD%20Host_Controller_Simplified_Specification_Ver4.20.pdf&e=EN_SSA2)<br>-[iSDIO Simplified Specification v1.10](https://www.sdcard.org/downloads/pls/pdf?p=PartE7_iSDIO_Simplified_Specification_Ver1.10.jpg&f=PartE7_iSDIO_Simplified_Specification_Ver1.10.pdf&e=EN_SSE7)|
|Serial ATA|-[SATA rev3.5a](https://sata-io.org/developers/purchase-specification)<br>-[AHCI v1.3.1](https://www.intel.com.tw/content/dam/www/public/us/en/documents/technical-specifications/serial-ata-ahci-spec-rev1-3-1.pdf)<br>-[AHCI v1.3](https://www.intel.com.tw/content/dam/www/public/us/en/documents/technical-specifications/serial-ata-ahci-spec-rev1_3.pdf)<br>-Port Multiplier|
|SMBus Specification|-[SMBUS Specification v3.3.1](https://smbus.org/specs/SMBus_3_3_1_20241020.pdf)<br>-[SMBUS Specification v3.3](https://smbus.org/specs/SMBus_3_3_20240512.pdf)<br>-[SMBus Specification v3.2](https://smbus.org/specs/SMBus_3_2_20220112.pdf)<br>-[SMBus Specification v3.1](http://smbus.org/specs/SMBus_3_1_20180319.pdf)<br>-[SMBus BIOS Specification v1.0](http://smbus.org/specs/smbb10.pdf)|
|SPI Bus Specification|[click](https://ww1.microchip.com/downloads/en/devicedoc/spi.pdf)|
|Thunderbolt|[click](https://www.intel.com/content/www/us/en/architecture-and-technology/thunderbolt/overview.html)|
|eSPI Bus Specification|[v1.6](https://www.intel.com/content/dam/support/us/en/documents/software/chipset-software/327432-004_espi_base_specification_rev1.0_cb.pdf)|
|UALink|-[Specification List](https://ualinkconsortium.org/specification/)<br>-[UALink_200 Rev 1.0]()||UALink Consortium|
|UFS Specification|[click](https://www.jedec.org/standards-documents/focus/flash/universal-flash-storage-ufs)|
|USB Bus Specifications|-[USB Specifications List](https://www.usb.org/documents)<br>-[USB4 Bus Specifications v2.0](https://www.usb.org/sites/default/files/USB4%20Specification%20Sep%202024_1.zip)<br>-[USB Bus Specifications v4.x](https://usb.org/sites/default/files/USB4%20Specification_5.zip)<br>-[USB Bus Specifications v3.2](https://www.usb.org/sites/default/files/usb_32_20210125.zip)<br>-[USB Bus Specifications v2.0](https://www.usb.org/sites/default/files/usb_20_20210701.zip)<br>-[eUSB v2.0](https://www.usb.org/sites/default/files/eUSB2_0_20240927.zip)|
|USB Device Class Specifications|[click](http://www.usb.org/developers/docs/devclass_docs/)|
|USB Host Controller Specification|-UHCI<br>-[OHCI v1.0a](http://www.o3one.org/hwdocs/usb/hcir1_0a.pdf)<br>-[EHCI v1.1](https://www.intel.com/content/dam/www/public/us/en/documents/technical-specifications/ehci-specification-for-usb.pdf)<br>-[XHCI rev1.2b](https://cdrdv2.intel.com/v1/dl/getContent/625472?fileName=625472_xHCI_Rev1_2b.pdf)|
|UWB|[UWB Wiki](https://en.wikipedia.org/wiki/Ultra-wideband)<br>[UWB Standards and Organizations](https://arxiv.org/pdf/2202.02190.pdf)
|WiFi Specification|[click](https://www.wi-fi.org/discover-wi-fi/specifications)|
|Zigbee|[click](https://zigbeealliance.org/developer_resources/)|


### Remote Management Specifications

|Specification|URL|Notes|
|:-----------------|:-------------------|:-----------------|
|DASH Specification (DMTF)|-[Information](https://www.dmtf.org/standards/dash)<br>-[DASH Implementation Requirements 1.4.0](https://www.dmtf.org/sites/default/files/standards/documents/DSP0232_1.4.0.pdf)<br>-[WS-Management CIM Binding Specification 1.2.0](https://www.dmtf.org/sites/default/files/standards/documents/DSP0227_1.2.0.pdf)<br>-[Systems Management Architecture for Mobile and Desktop Hardware White Paper 1.1.0](https://www.dmtf.org/sites/default/files/standards/documents/DSP2014_1.1.0.pdf)<br>-[DASH Delivers Multi-Vendor Management for Desktop and Mobile Systems 1.0.0](https://www.dmtf.org/sites/default/files/standards/documents/DASHTechNote.pdf)|
|Intel vPro|[Information](https://www.intel.com/content/www/us/en/architecture-and-technology/intel-active-management-technology.html)|
|IPMI Specification|-[Information](https://www.intel.com.tw/content/www/tw/zh/servers/ipmi/ipmi-technical-resources.html?wapkw=ipmi)<br>-[IPMI v2.0 rev. 1.1](https://www.intel.com/content/dam/www/public/us/en/documents/product-briefs/ipmi-second-gen-interface-spec-v2-rev1-1.pdf)|
|Redfish Specification (DMTF)|-[Information](https://www.dmtf.org/standards/redfish)<br>-[Redfish Release 2025.1 Overview](https://www.dmtf.org/sites/default/files/Redfish_Release_2025.1_Overview.pdf)<br>-[Redfish Release 2024.3 Overview](https://www.dmtf.org/sites/default/files/Redfish%20Release%202024.3%20Overview.pdf)<br>-[Redfish Release 2024.2 Overview](https://www.dmtf.org/sites/default/files/Redfish%20Release%202024.2%20Overview.pdf)<br>-[Redfish Release 2024.1 Overview](https://www.dmtf.org/sites/default/files/Redfish%20Release%202024.1%20Overview.pdf)<br><br><br>--------Other Redfish Specifications-----------------<br>-[Redfish Specification 1.22.0](https://www.dmtf.org/sites/default/files/standards/documents/DSP0266_1.22.0.pdf)<br>-[Redfish Specification 1.21.0](https://www.dmtf.org/sites/default/files/standards/documents/DSP0266_1.21.0.pdf)<br>-[Redfish Host Interface Specification 1.3.1](https://www.dmtf.org/sites/default/files/standards/documents/DSP0270_1.3.1.pdf)<br>|
|Swordfish Specification (SNIA)|-[Information](https://www.snia.org/forums/smi/swordfish)<br>-[click](https://www.snia.org/tech_activities/publicreview#swordfish)|



|Remote Desktop/Connection Protocol |URL|Notes|
|:-----------------|:-------------------|:-----------------|
|ANSI/VT100|[click](https://www2.ccs.neu.edu/research/gpc/VonaUtils/vona/terminal/vtansi.htm)|
|SSH|[click](https://datatracker.ietf.org/doc/html/rfc4253)|
|RDP|[click](https://learn.microsoft.com/en-us/openspecs/windows_protocols/ms-rdpbcgr/5073f4ed-1e93-45e1-b039-6e30c385867c)|
|VNC/RFB|-[IETF RFB Protocol](https://datatracker.ietf.org/doc/html/rfc6143)<br>-[RFB Protocol - Github](https://github.com/rfbproto/rfbproto/blob/master/rfbproto.rst)<br>|


### Industry Standard Specifications

|Specification|URL|Status|Notes|
|:-----------------|:-------------------|:-----------------|:-----------------|
|ACPI|-[ACPI Specification List](https://uefi.org/specifications)<br>-[v6.5a PDF](https://uefi.org/sites/default/files/resources/ACPI_Spec_6.5a_Final.pdf)<br>-[(v6.5 PDF)](https://uefi.org/sites/default/files/resources/ACPI_Spec_6_5_Aug29.pdf)-[(v6.5 HTML)](https://uefi.org/specifications/ACPI/6.5/)<br>-[(v6.4 Errata A PDF)](https://uefi.org/sites/default/files/resources/ACPI_Spec_6_4_A_final_Aug29.pdf)-[(v6.4 Errata A HTML)](https://uefi.org/specifications/ACPI/6.4_A/)<br>-[v6.4 PDF - January 2021](https://uefi.org/sites/default/files/resources/ACPI_Spec_6_4_Jan22.pdf)<br>||acpi specifications, acpi tables|
|APM (Advanced Power Management)|[v1.2 - Feb 1996](https://download.microsoft.com/download/1/6/1/161ba512-40e2-4cc9-843a-923143f3456c/apmv12.rtf)||
|ASF (Alert Standard Format)(DMTF)|-[ASF v2.0 - 23/Apr/2003](https://www.dmtf.org/sites/default/files/standards/documents/DSP0136.pdf)||
|BBS (Bios Boot Specification)|[v1.01 - 11 Jan 1996](https://www.scs.stanford.edu/nyu/04fa/lab/specsbbs101.pdf)||
|EDD (Enhanced Disk Drive)|-[EDD v4.0](https://t13.org/system/files/Documents/2014/f14138r2-Draft%20Amendment%201%20for%20EDD-4_1.pdf)||
|EDK2 Specifications|https://github.com/tianocore-docs/Docs|
|FIDO Alliance|-[Specification List](https://fidoalliance.org/specifications-overview/)<br>-[User Authentication](https://fidoalliance.org/specifications/)<br>-[User Authentication Spec Download](https://fidoalliance.org/specifications/download/)<br>|
|PMM (Post Memory Manager)|[v1.01](https://archive.org/details/specs-pmm101)||
|PXE|[Tianocore Wiki](https://github.com/tianocore/tianocore.github.io/wiki/PXE)||
|SMBIOS|-[SMBIOS Spec Info](https://www.dmtf.org/standards/smbios)<br>-[SMBIOS Specification List](https://www.dmtf.org/dsp/DSP0134)<br>-[SMBIOS v3.8.0 - 5 Aug 2024](https://www.dmtf.org/sites/default/files/standards/documents/DSP0134_3.8.0.pdf)<br>-[SMBIOS v3.7.1 - 24 May 2024](https://www.dmtf.org/sites/default/files/standards/documents/DSP0134_3.7.1.pdf)<br>-[SMBIOS v3.7.0 - 21 Jul 2023](https://www.dmtf.org/sites/default/files/standards/documents/DSP0134_3.7.0.pdf)<br>-[SMBIOS v3.6.0 - 20 Jun 2022](https://www.dmtf.org/sites/default/files/standards/documents/DSP0134_3.6.0.pdf)<br>-[SMBIOS v3.5.0 - 21/Sep/2021](https://www.dmtf.org/sites/default/files/standards/documents/DSP0134_3.5.0.pdf)<br>-[SMBIOS v3.4.0 - 17/Jul/2020](https://www.dmtf.org/sites/default/files/standards/documents/DSP0134_3.4.0.pdf)||
|TCG|[Specification List](https://trustedcomputinggroup.org/resources/?)||Trusted Computing Group|
|UEFI|UEFI Specification<br>-[UEFI Specification List](https://uefi.org/specifications)<br>-[UEFI Specification v2.11](https://uefi.org/sites/default/files/resources/UEFI_Spec_Final_2.11.pdf)<br>-[UEFI Specification v2.10 Errata A - PDF](https://uefi.org/sites/default/files/resources/UEFI_Spec_2_10_A_Aug8.pdf)-[HTML](https://uefi.org/specs/UEFI/2.10_A/)<br>-[UEFI Specification v2.10 - PDF](https://uefi.org/sites/default/files/resources/UEFI_Spec_2_10_Aug29.pdf)-[HTML](https://uefi.org/specs/UEFI/2.10/)<br>-[UEFI Specification v2.9 Errata A - PDF](https://uefi.org/sites/default/files/resources/UEFI_Spec_2_9_A_final_Aug29.pdf)-[HTML](https://uefi.org/specs/UEFI/2.9_A/)<br>-[UEFI Specification v2.9](https://uefi.org/sites/default/files/resources/UEFI_Spec_2_9_2021_03_18.pdf)<br><br>UEFI Shell Specification<br>-[UEFI Shell Specification v2.2](http://www.uefi.org/sites/default/files/resources/UEFI_Shell_2_2.pdf)<br><br>PI Specification<br>-[UEFI PI v1.9](https://uefi.org/sites/default/files/resources/UEFI_PI_Spec_Final_Draft_1.9.pdf)<br>-[UEFI PI v1.8 Errata A](https://uefi.org/sites/default/files/resources/PI_Spec_1_8_A_final_2024.03.05.pdf)<br>-[UEFI PI v1.8](https://uefi.org/sites/default/files/resources/UEFI_PI_Spec_1_8_March3.pdf)<br>-[UEFI PI v1.7 Errata B](https://uefi.org/sites/default/files/resources/UEFI_Platform%20Initialization%20Spec%20Version%201.7%20errata%20B_May%202023.pdf)<br>-[UEFI PI v1.7 Errata A](https://uefi.org/sites/default/files/resources/PI_Spec_1_7_A_final_May1.pdf)<br>||uefi spec, PI spec, UEFI shell, UEFI SCT|


### File System and Disc Format

|File System Type|Specification URL|Notes|
|:-----------------|:-------------------|:-----------------|
|Microsoft FAT32|[1.03](https://download.microsoft.com/download/1/6/1/161ba512-40e2-4cc9-843a-923143f3456c/fatgen103.doc)|
|Microsoft exFAT|-[Latest web version](https://docs.microsoft.com/en-us/windows/win32/fileio/exfat-specification)<br>-[Latest pdf](https://docs.microsoft.com/en-us/windows/win32/opbuildpdf/fileio/toc.pdf?branch=live)|
|NTFS|[wiki](https://en.wikipedia.org/wiki/NTFS)|
|El Torito Boot|[1.0](https://pdos.csail.mit.edu/6.828/2014/readings/boot-cdrom.pdf)|
|UDF|[2.60](http://www.osta.org/specs/pdf/udf260.pdf)|
|ISO 9660|-[1998(en)](https://www.iso.org/obp/ui/#iso:std:iso:9660:ed-1:v1:en)<br>-[1988/Amd.1:2013(en)](https://www.iso.org/obp/ui/#iso:std:iso:9660:ed-1:v1:amd:1:v1:en)|
|Joliet Filesystem|[Extensions for Unicode Version 1](http://pismotec.com/cfs/jolspec.html)|
|ext4|[web](https://ext4.wiki.kernel.org/index.php/Ext4_Disk_Layout)|
|HFS Plus|[web](https://developer.apple.com/library/archive/technotes/tn/tn1150.html#//apple_ref/doc/uid/DTS10002989)|

### File Format

|Specification|Extension|URL|Notes|
|:-----------------|:-----|:-------------------|:-----------------|
|Executable and Linking Format (ELF)||-[v1.2](https://refspecs.linuxfoundation.org/elf/elf.pdf)<br>-[v1.1](https://refspecs.linuxfoundation.org/elf/TIS1.1.pdf)|
|FLV|.flv||
|JPG|.jpg, .jpeg|[Standards](https://jpeg.org/jpeg/)|
|MPEG|.mp3, mp4, .aac, .avc|[Standards](https://www.mpeg.org/standards/)|
|Microsoft PE/COFF Specification|.dll<br>.exe<br>.sys<br>.obj<br>.efi|-[8.0](http://www.microsoft.com/whdc/system/platform/firmware/PECOFF.mspx)<br>-[Latest web](https://docs.microsoft.com/en-us/windows/win32/debug/pe-format)<br>-[Latest pdf](https://docs.microsoft.com/en-us/windows/win32/opbuildpdf/debug/toc.pdf?branch=live)|
|PNG|.png|[Specification](https://www.w3.org/TR/2003/REC-PNG-20031110/)|
|WAVE Audio Format|.wav|[click](https://docs.fileformat.com/audio/wav/)|

## Tools

|Tool|Version|OS|Notes|
|:-----------------|:-------------------|:-----------------|:-----------------|
|[ PLe](https://github.com/vangoghynot/UefiResources/tree/master/Tools)|0.9.1|UEFI|PLe Provides:<br>**1.	PCI/PCI Express<br>** **2.	System memory<br>** **3.	ACPI<br>** **4.	SMBIOS**|
|[ PL](https://github.com/vangoghynot/UefiResources/tree/master/Tools)|1.5.0.10|DOS|PL Provides:<br>**1.	PCI Bus/Device Information(PCI register read/write)<br>** **2.	USB host controller information<br>** **3.	System memory read/write<br>** **4.	I/O address read/write<br>** **5.	Index IO read/write<br>** **6.	HD-Audio Controller Information (Include immediate VERB command, save codec cmd sequence as c file)<br>** **7.	AC97 Controller<br>** **8.	ACPI Table<br>** **9.	Disk read/write<br>** **10.	Int15h E820 maps advanced browsing<br>** **11.	Multi Processor(MP) Table dump.<br>** **12. Advanced Browsing experience. <br>** &nbsp;&nbsp;&nbsp; - Goto alternative view (Alt+G) Example: PCI<>IO or Memory, ACPI<>Memory<br>&nbsp;&nbsp;&nbsp; - Go back previous view(Alt+B)<br> **13. Save View data to file (Save as TXT, HTML, Binary)<br>** (https://github.com/vangoghynot/UefiResources/tree/master/Tools)|
|[ PLC](https://github.com/vangoghynot/UefiResources/tree/master/Tools/)|1.0.1.4|Windows|**1. UEFI/BIOS Smart Debug Information<br>**  - Error/Checkpoint/Guid Message clarification and color highlight<br> - User defined message filter and color highight (Support two uder defined sets)<br> - Quick message search and locate debug message<br> - Save debug message on the fly (save to file)<br> - Load debug message and analysis<br>**2. Addon Debug Message Functions<br>** - Calculate the timeing between two marked debug messages, can be used to measure and tune the BIOS POST time.<br> (Click the 'Time' button on tool bar to open the 'Time' Windows, then use 'SPACE' key to mark the message.<br> - GUID and Meaniningful name translation <br> * Lookup the BIOS source code at startup. Once the GUID is displayed in the dbeug message, convert the GUID to the driver/protocol name of the GUID.<br>* (Need to set the 'GUID File Path' in the "Config" window to point to the UEFI/BIOS source code)<br>* (Click the 'Decode Messages' button in the tool bar to enable/disable the trsnslation.<br>**3. USB<br>**  - USB topology map<br> - Save the USB topology map to TXT or ASL file<br>* - Compare the USB topology map. Can be utilize to check if any USB device loss cross system boots. (support command line mode)<br> - ACPI ASL _UPC and _PLD generation for USB devices.<br>**4. Disk<br>**  - Need to launch the application in Administrator right.<br> - View GPT/MBR information<br> - Check disk boot capability.<br>**5. Console Redirection<br>**  - Click 'Terminal' button in the tool bar to open the console window.<br> - Support ANSI/VT100 (Similar to Putty/Teraterm)<br> - Capture screen to file.<br>**6. SUT Control (Control M/B)<br>**  - Need specific hardware<br> - Support Web http/https request or windows exe/bat to control the M/B - Support 'Level' or Pulse control<br> - Capable to control the M/B AC power or Power Button<br>**7. UEFI Variable READ<br>**  - Need Administrator Right<br> - Read UEFI Variable in Windows <br>(https://github.com/vangoghynot/UefiResources/tree/master/Tools)|
|IPMI Tools|-[Information](https://www.intel.com.tw/content/www/tw/zh/servers/ipmi/ipmi-technical-resources.html?wapkw=ipmi)-[IPMI, V2.0, Conformance Test Suite (ICTS) Prototype, V6.02](https://www.intel.com.tw/content/dam/www/public/us/en/documents/product-briefs/icts_v602.zip)<br>-[IPMI, V2.0, V1.5, and V1.0, Reference Drivers](https://www.intel.com.tw/content/dam/www/public/us/en/documents/product-briefs/drvjan13_2005.zip)<br>-[IPMI, V2.0, Command Test Tool](https://www.intel.com.tw/content/dam/www/public/us/en/documents/product-briefs/ipmitool_01-13-05.zip)|
|Redfish Tools (DMTF Github)|[Redfish Test Framework](https://github.com/DMTF/Redfish-Test-Framework)|


## Compilers/ToolChains

List all compilers and firmware build tools

|Compiler/ToolChains|Version|OS|Notes|
|:--------------------|:-----------------------|:-----------------|:-----------------|
|Gnu GCC|-[All Versions](https://gcc.gnu.org/)<br>-[Gnu GCC v11](https://gcc.gnu.org/gcc-11/)|Linux<br>Windows<br>|Support Various Architectures
|ARM Gnu ToolChain|-[All Versions](https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain)|Linux<br>Windows<br>|GCC, GDB, BinTools, and libraries for ARM32 and Aarch64
|Linaro GCC|[All Versions](https://snapshots.linaro.org/gnu-toolchain/)|Linux<br>Windows<br>|Linaro Monthly Build Gnu ToolChains for ARM32 and Aarch64
|Linaro LLVM|-[All Versions](https://github.com/llvm/llvm-project/releases/)<br>-[v13.0.0.rc2](https://github.com/llvm/llvm-project/releases/tag/llvmorg-13.0.0-rc2)|Linux<br>Windows<br>|
|LLVM|-[Information](https://llvm.org/)<br>-[v12.0.1](https://releases.llvm.org/download.html#12.0.1)|Linux<br>Windows<br>|
|Microsoft Visual Studio|[Download](https://visualstudio.microsoft.com/en-us/downloads/)|Windows|
|Microsoft Build Tools|-[2015](https://www.microsoft.com/en-us/download/details.aspx?id=48159)<br>-[Build Tools for Visual Studio2019](https://visualstudio.microsoft.com/en-us/thank-you-downloading-visual-studio/?sku=BuildTools&rel=16)<br>-[Build Tools Component](https://docs.microsoft.com/en-us/visualstudio/install/workload-component-id-vs-build-tools?view=vs-2019)|Windows|
|Microsoft EWDK|-[Windows 11 EWDK](https://docs.microsoft.com/en-us/legal/windows/hardware/enterprise-wdk-license-2019-New)<br>-[EWDK for Windows Server 2022](https://docs.microsoft.com/en-us/legal/windows/hardware/enterprise-wdk-license-2019)<br>-[EWDK for Windows 10 v2004](https://docs.microsoft.com/en-us/legal/windows/hardware/enterprise-wdk-license-2019)<br>-[EWDK for Windows 10 v1903](https://docs.microsoft.com/en-us/legal/windows/hardware/enterprise-wdk-license-2019)<br>-[EWDK for Windows 10 v1809](https://docs.microsoft.com/en-us/legal/windows/hardware/enterprise-wdk-license-2017)<br>-[EWDK for Windows 10 v1803](https://docs.microsoft.com/en-us/legal/windows/hardware/enterprise-wdk-license-2017)<br>-[EWDK for Windows 10 v1709](https://docs.microsoft.com/en-us/legal/windows/hardware/enterprise-wdk-license-2017)|Windows|
|ACPICA|-[Information](https://www.acpica.org/)<br>-[Downloads](https://www.acpica.org/downloads)<br>-[v2021_0730](https://www.acpica.org/node/195)|Linux<br>Windows|ACPI ASL Language Compiler
|NASM(Netwide Assembler)|-[Information](https://www.nasm.us/)<br>-[Downloads](https://www.nasm.us/pub/nasm/releasebuilds/?C=M;O=D)<br>-[v2.15.05](https://www.nasm.us/pub/nasm/releasebuilds/2.15.05/)|Linux<br>macOS<br>Windows|
|Python|-[Downloads](https://www.python.org/downloads/)|Linux<br>macOS<br>Windows|
