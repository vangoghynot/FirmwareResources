# FirmwareResources
Firmware related resources


# Firmware and OS Specifications/Standards Maintained by TonyLo

1. [Official Sites](#Official-sites)
2. [Firmware and OS Architecture](#firmware-and-os-architecture)
3. [Specifications](#Specifications)
    <BR>-[Bus Specifications](#bus-specifications)
    <BR>-[Remote Management Specifications](#remote-management-specifications)
    <BR>-[Industry Standard and Specifications](#industry-standard-specifications)
    <BR>-[File System and Disc Format](#file-system-and-disc-format)
    <BR>-[File Format](#file-format)
4. [Tools](#tools)
5. [Compilers/ToolChains](#Compilers/ToolChains)

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
|DMTF|https://www.dmtf.org|CADF, CDM, CLOUD, CIM, CMDBf, DASH, NETMAN, OVF, PMCI, REDFISH, SMASH, SMBIOS, VMAN, WBEM, WS-MAN
|GNU|https://www.gnu.org/|GNU OS, Software, Tools, Compilers
|HDMI|https://www.hdmi.org|HDMI<BR>
|INCITS T10|https://www.t10.org|SCSI<BR>SAS
|INCITS T13|https://www.t13.org|ATA/ATAPI<BR>
|Intel|https://www.intel.com|Intel Processor/Chipsets<BR>XHCI<BR>eSPI<BR>AC97
|JEDEC|https://www.jedec.org|Microelectronics Standard<BR>eMMC<BR>UFS
|MCC|https://www.mcc-us.com/|I2C Bus Analyzer
|MIPI Alliance|https://www.mipi.org|MIPI<BR>
|Microsoft|https://www.microsoft.com|Microsoft Windows<BR>
|NIST|https://www.nist.gov|NIST Standards
|NVM Express|https://www.nvmexpress.org|NVMe<BR>
|NXP|https://www.nxp.com/|
|OpenBIOS|https://www.openbios.info/|
|OpenBMC|https://www.openbmc.org/|OpenBMC
|PCI-SIG|https://pcisig.com/|PCI<BR>PCI Express<BR>
|SATA-IO|https://sata-io.org/|Serial ATA
|SD Association |https://www.sdcard.org|SDCard<BR>MicroSD<BR>SD Express<BR>SDIO<BR>iSDIO
|Trusted Computing Group|https://trustedcomputinggroup.org/|TPM
|u-bmc|https://u-bmc.readthedocs.io/|
|U-Boot|https://www.denx.de/wiki/U-Boot|
|UEFI|https://www.uefi.org|UEFI<BR>UEFI PI<BR>UEFI SCT<BR>ACPI
|USB|https://www.usb.org|USB Specification<BR>USB Device Classes<BR>USB PD
|VESA|https://vesa.org/|VESA spec


## Firmware and OS Architecture

Firmware and OS architecture sites

|Firmware/OS Architecture|URL|Notes|
|:-----------------|:-------------------|:-----------------|
|ARM Trusted Firmware TF-A|https://developer.arm.com/tools-and-software/open-source-software/firmware/trusted-firmware/trusted-firmware-a|
|ARM Trusted Firmware TF-M|https://developer.arm.com/tools-and-software/open-source-software/firmware/trusted-firmware/trusted-firmware-m|
|CoreBoot|http://www.coreboot.org|
|Intel Slimboot|https://www.intel.com.tw/content/www/tw/zh/design/products-and-solutions/technologies/slim-bootloader/overview.html|
|Linux Boot|https://www.linuxboot.org/|
|OpenBIOS|https://www.openbios.info/|
|OpenBMC|https://www.openbmc.org/|
|Open System Firmware|https://www.opencompute.org/projects/open-system-firmware|
|SeaBIOS|https://www.seabios.org|Legacy BIOS
|SeaVGABios|https://seabios.org/SeaVGABIOS|Open Source VGA BIOS
|u-bmc|https://github.com/u-root/u-bmc|
|U-Boot|https://www.denx.de/wiki/U-Boot|
|UEFI Firmware|http://www.uefi.org|


## Specifications

### Bus Technology

|Specification|URL|Notes|
|:-----------------|:-------------------|:-----------------|
|1394/Firewire|[OHCI v1.1](http://download.microsoft.com/download/1/6/1/161ba512-40e2-4cc9-843a-923143f3456c/ohci_11.pdf)|
|AC97 Specification|[ICH7 AC97 Programmers Manual](https://www.intel.com/content/dam/doc/manual/io-controller-hub-7-hd-audio-ac97-manual.pdf)|
|Access Bus Specification|[v3.0](http://www.mcc-us.com/abspec30.zip)|
|AGP Specification|[v1.0](http://www.playtool.com/pages/agpcompat/agp10.pdf)<br>[v3.0](http://www.playtool.com/pages/agpcompat/agp30.pdf)|
|AGP Pro Specification|[v1.1a](https://web.archive.org/web/20021003222339/http://www.agpforum.org/downloads/apro_r11a.pdf)|
|ATA/ATAPI Specification|-[ACS-4 Rev.14](http://www.t13.org/Documents/UploadedDocuments/docs2016/di529r14-ATAATAPI_Command_Set_-_4.pdf)<br>-[ATA8 ACS](http://www.t13.org/documents/UploadedDocuments/docs2007/D1699r4a-ATA8-ACS.pdf)<br>[ATA8 ACS2](http://www.t13.org/Documents/UploadedDocuments/docs2009/d2015r2-ATAATAPI_Command_set_-_2_ACS-2.pdf)<br>-[ATAPI for CDROM 8020i rev2.6](http://www.bswd.com/sff8020i.pdf)<br>-ATA for Removable 8070i|
|Bluetooth|-[CS 5.2](https://www.bluetooth.org/docman/handlers/downloaddoc.ashx?doc_id=478726)<br>-[CSS 9](https://www.bluetooth.org/docman/handlers/DownloadDoc.ashx?doc_id=480305)<br>-[Bluetooth GATT Specification](https://www.bluetooth.com/specifications/gatt/)<br>-[Bluetooth Traditional Profile](https://www.bluetooth.com/specifications/profiles-overview/)<br>-[Bluetooth Protocol Specification](https://www.bluetooth.com/specifications/protocol-specifications/)|
|CAN Bus/CAN-FD|-[CAN-FD Information](http://www.bosch-semiconductors.com/ip-modules/can-ip-modules/can-fd/)<br>-[CAN-FD v1.0](https://can-newsletter.org/assets/files/ttmedia/raw/e5740b7b5781b8960f55efcc2b93edf8.pdf)|
|eMMC Specification|[v5.1a](https://www.jedec.org/standards-documents/technology-focus-areas/flash-memory-ssds-ufs-emmc/e-mmc)|
|HDAudio Specification|[v1.0a](https://www.intel.com/content/dam/www/public/us/en/documents/product-specifications/high-definition-audio-specification.pdf)|
|HDMI Specification|[v2.1](https://www.hdmi.org/spec/hdmi2_1)|
|I2C Bus Specification|[v6.0](https://www.nxp.com/docs/en/user-guide/UM10204.pdf)|
|I2S Specification|[June 5, 1996](https://www.sparkfun.com/datasheets/BreakoutBoards/I2SBUS.pdf)|
|I3C Specification]|-[MIPI I3C Basic v1.0](https://resources.mipi.org/mipi-i3c-v1-download)<br>-[MIPI I3C v1.1](https://www.mipi.org/specifications/i3c-sensor-specification)<br>-[NXP I3C Training Video](https://www.nxp.com/design/training/improved-inter-integrated-circuit-i3c-standard:TIP-I3C-STANDARD)|
|LPC Specification|[v1.1](https://www.intel.com/content/dam/www/program/design/us/en/documents/low-pin-count-interface-specification.pdf)|
|MIPI Specification|[click](https://www.mipi.org/current-specifications)|
|NVM Express(NVMe)|-[All Specifications](https://nvmexpress.org/developers/nvme-specification/)<br>-[NVMe Command Set Specifications](https://nvmexpress.org/developers/nvme-command-set-specifications/)<br>-[NVMe Transport Specificaions](https://nvmexpress.org/developers/nvme-transport-specifications/)<br>-[NVMe-MI Specifications](https://nvmexpress.org/developers/nvme-mi-specification/)<br>-[NVM Express Base Specification 2.0a](https://nvmexpress.org/wp-content/uploads/NVMe-NVM-Express-2.0a-2021.07.26-Ratified.pdf)<br>-[NVMe Management Interface v1.1a](https://nvmexpress.org/developers/nvme-mi-specification/)|
|PCI/PCIExpress|-[PCI Express Base Specification](https://pcisig.com/specifications)<br>-[Rev 4.0, ver 1.0](https://members.pcisig.com/wg/PCI-SIG/document/10912?downloadRevision=active)<br>-[Rev 4.0, Ver 0.3](http://composter.com.ua/documents/PCI_Express_Base_Specification_Revision_4.0.Ver.0.3.pdf)<br>-[PCI Local Bus Specification v3.0](https://www.xilinx.com/Attachment/PCI_SPEV_V3_0.pdf)<br>-[PCI Firmware Specification v3.2](https://members.pcisig.com/wg/PCI-SIG/document/download/8232)|
|SCSI Specification|[click](https://www.t10.org/scsi-3.htm)|
|SD/SDIO/SD Express|-[All Specifications](https://www.sdcard.org/downloads/)<br>-[Latest WhitePapers](https://www.sdcard.org/downloads/pls/latest_whitepapers/)<br>-[SDIO Simplified Specification v3.0](https://www.sdcard.org/downloads/pls/pdf?p=PartE1_SDIO_Simplified_Specification_Ver3.00.jpg&f=PartE1_SDIO_Simplified_Specification_Ver3.00.pdf&e=EN_SSE1)<br>-[SD Host Controller Specification v4.20](https://www.sdcard.org/downloads/pls/pdf?p=PartA2_SD%20Host_Controller_Simplified_Specification_Ver4.20.jpg&f=PartA2_SD%20Host_Controller_Simplified_Specification_Ver4.20.pdf&e=EN_SSA2)<br>-[iSDIO Simplified Specification v1.10](https://www.sdcard.org/downloads/pls/pdf?p=PartE7_iSDIO_Simplified_Specification_Ver1.10.jpg&f=PartE7_iSDIO_Simplified_Specification_Ver1.10.pdf&e=EN_SSE7)|
|Serial ATA|-[SATA rev3.5](https://sata-io.org/developers/purchase-specification)<br>-[AHCI v1.3.1](https://www.intel.com.tw/content/dam/www/public/us/en/documents/technical-specifications/serial-ata-ahci-spec-rev1-3-1.pdf)<br>-[AHCI v1.3](https://www.intel.com.tw/content/dam/www/public/us/en/documents/technical-specifications/serial-ata-ahci-spec-rev1_3.pdf)<br>-Port Multiplier|
|SMBus Specification|-[SMBus Specification v3.1](http://smbus.org/specs/SMBus_3_1_20180319.pdf)<br>-[SMBus BIOS Specification v1.0](http://smbus.org/specs/smbb10.pdf)|
|SPI Bus Specification||
|eSPI Bus Specification|[v1.0](https://www.intel.com/content/dam/support/us/en/documents/software/chipset-software/327432-004_espi_base_specification_rev1.0_cb.pdf)|
|UFS Specification||
|USB Bus Specifications|[All USB Specifications](https://www.usb.org/documents)<br>-[USB Bus Specifications v2.0](https://www.usb.org/sites/default/files/usb_20_20210701.zip)<br>-[USB Bus Specifications v3.2](https://www.usb.org/sites/default/files/usb_32_20210125.zip)<br>-[USB Bus Specifications v4.x](https://usb.org/sites/default/files/USB4%20Specification_5.zip)|
|USB Device Class Specifications|[click](http://www.usb.org/developers/docs/devclass_docs/)|
|USB Host Controller Specification|-UHCI<br>-[OHCI v1.0a](http://www.o3one.org/hwdocs/usb/hcir1_0a.pdf)<br>-[EHCI v1.1](https://www.intel.com/content/dam/www/public/us/en/documents/technical-specifications/ehci-specification-for-usb.pdf)<br>-[XHCI rev1.2](https://www.intel.com/content/dam/www/public/us/en/documents/technical-specifications/extensible-host-controler-interface-usb-xhci.pdf)|
|WiFi Specification|[click](https://www.wi-fi.org/discover-wi-fi/specifications)|
|Zigbee|[click](https://zigbeealliance.org/developer_resources/)|


### Remote Management Specifications

|Specification|URL|Notes|
|:-----------------|:-------------------|:-----------------|
|DASH Specification (DMTF)|-[Information](https://www.dmtf.org/standards/dash)<br>-[DASH Implementation Requirements 1.2.1](https://www.dmtf.org/sites/default/files/standards/documents/DSP0232_1.2.1.pdf)<br>-[WS-Management CIM Binding Specification 1.2.0](https://www.dmtf.org/sites/default/files/standards/documents/DSP0227_1.2.0.pdf)<br>-[Systems Management Architecture for Mobile and Desktop Hardware White Paper 1.1.0](https://www.dmtf.org/sites/default/files/standards/documents/DSP2014_1.1.0.pdf)<br>-[DASH Delivers Multi-Vendor Management for Desktop and Mobile Systems 1.0.0](https://www.dmtf.org/sites/default/files/standards/documents/DASHTechNote.pdf)|
|Intel AMT|[Information](https://www.intel.com/content/www/us/en/architecture-and-technology/intel-active-management-technology.html)|
|IPMI Specification|-[Information](https://www.intel.com.tw/content/www/tw/zh/servers/ipmi/ipmi-technical-resources.html?wapkw=ipmi)<br>-[IPMI v2.0 rev. 1.1](https://www.intel.com/content/dam/www/public/us/en/documents/product-briefs/ipmi-second-gen-interface-spec-v2-rev1-1.pdf)|
|Redfish Specification (DMTF)|-[Information](https://www.dmtf.org/standards/redfish)<br>-[Redfish Specification 1.11.1](https://www.dmtf.org/sites/default/files/standards/documents/DSP0266_1.11.1.pdf)<br>-[Redfish Host Interface Specification 1.3.0](https://www.dmtf.org/sites/default/files/standards/documents/DSP0270_1.3.0.pdf)<br>-[Redfish Interoperability Profiles Specification 1.3.0](https://www.dmtf.org/sites/default/files/standards/documents/DSP0272_1.3.0.pdf)<br>-[Redfish Schema Supplement 2020.3](https://www.dmtf.org/sites/default/files/standards/documents/DSP0268_2020.3.pdf)|
|Swordfish Specification (SNIA)|-[Information](https://www.snia.org/forums/smi/swordfish)<br>-[click](https://www.snia.org/tech_activities/publicreview#swordfish)|
|RDP||
|VNC||


### Industry Standard Specifications

|Specification|URL|Notes|
|:-----------------|:-------------------|:-----------------|
|ACPI|-[v6.4 PDF](https://uefi.org/sites/default/files/resources/ACPI_Spec_6_4_Jan22.pdf)<br>-[v6.4 HTML](https://uefi.org/specifications/ACPI/6.4/)|acpi spec, acpi tables|
|Bluetooth||core spec, profiles|
|EDK2 Specifications|https://github.com/tianocore-docs/Docs|
|UEFI|-[UEFI Specification v2.9](https://uefi.org/sites/default/files/resources/UEFI_Spec_2_9_2021_03_18.pdf)<br>-[UEFI Shell Specification v2.2](http://www.uefi.org/sites/default/files/resources/UEFI_Shell_2_2.pdf)<br>-[UEFI PI v1.7 Errata A](https://uefi.org/sites/default/files/resources/PI_Spec_1_7_A_final_May1.pdf)<br>|uefi spec, PI spec, UEFI shell, UEFI SCT|


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
|MPEG3|.mp3||
|MPEG4|.mp4||
|Microsoft PE/COFF Specification|.dll<br>.exe<br>.sys<br>.obj<br>.efi|-[8.0](http://www.microsoft.com/whdc/system/platform/firmware/PECOFF.mspx)<br>-[Latest web](https://docs.microsoft.com/en-us/windows/win32/debug/pe-format)<br>-[Latest pdf](https://docs.microsoft.com/en-us/windows/win32/opbuildpdf/debug/toc.pdf?branch=live)|
|WAVE Audio Format|.wav|[click](https://docs.fileformat.com/audio/wav/)|

## Tools

|Tool|Version|OS|Notes|
|:-----------------|:-------------------|:-----------------|:-----------------|
|[ PL](http://ubios.blogspot.com/)|1.5.0.10|DOS|PL Provides:<br>**1.	PCI Bus/Device Information(PCI register read/write)<br>** **2.	USB host controller information<br>** **3.	System memory read/write<br>** **4.	I/O address read/write<br>** **5.	Index IO read/write<br>** **6.	HD-Audio Controller Information (Include immediate VERB command, save codec cmd sequence as c file)<br>** **7.	AC97 Controller<br>** **8.	ACPI Table<br>** **9.	Disk read/write<br>** **10.	Int15h E820 maps advanced browsing<br>** **11.	Multi Processor(MP) Table dump.<br>** **12. Advanced Browsing experience. <br>** &nbsp;&nbsp;&nbsp; - Goto alternative view (Alt+G) Example: PCI<>IO or Memory, ACPI<>Memory<br>&nbsp;&nbsp;&nbsp; - Go back previous view(Alt+B)<br> **13. Save View data to file (Save as TXT, HTML, Binary)<br>** (http://ubios.blogspot.com)|
|[ PLC](http://ubios.blogspot.com/)|1.0.1.2|Windows|**1. UEFI/BIOS Smart Debug Information<br>**  - Error/Checkpoint/Guid Message clarification and color highlight<br> - User defined message filter and color highight (Support two uder defined sets)<br> - Quick message search and locate debug message<br> - Save debug message on the fly (save to file)<br> - Load debug message and analysis<br>**2. Addon Debug Message Functions<br>** - Calculate the timeing between two marked debug messages, can be used to measure and tune the BIOS POST time.<br> (Click the 'Time' button on tool bar to open the 'Time' Windows, then use 'SPACE' key to mark the message.<br> - GUID and Meaniningful name translation <br> * Lookup the BIOS source code at startup. Once the GUID is displayed in the dbeug message, convert the GUID to the driver/protocol name of the GUID.<br>* (Need to set the 'GUID File Path' in the "Config" window to point to the UEFI/BIOS source code)<br>* (Click the 'Decode Messages' button in the tool bar to enable/disable the trsnslation.<br>**3. USB<br>**  - USB topology map<br> - Save the USB topology map to TXT or ASL file<br>* - Compare the USB topology map. Can be utilize to check if any USB device loss cross system boots. (support command line mode)<br> - ACPI ASL _UPC and _PLD generation for USB devices.<br>**4. Disk<br>**  - Need to launch the application in Administrator right.<br> - View GPT/MBR information<br> - Check disk boot capability.<br>**5. Console Redirection<br>**  - Click 'Terminal' button in the tool bar to open the console window.<br> - Support ANSI/VT100 (Similar to Putty/Teraterm)<br> - Capture screen to file.<br>**6. SUT Control (Control M/B)<br>**  - Need specific hardware<br> - Support Web http/https request or windows exe/bat to control the M/B - Support 'Level' or Pulse control<br> - Capable to control the M/B AC power or Power Button<br>**7. UEFI Variable READ<br>**  - Need Administrator Right<br> - Read UEFI Variable in Windows <br>(http://ubios.blogspot.com)|
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