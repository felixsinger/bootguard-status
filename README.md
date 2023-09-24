# BootGuard status
## What is this?
TBD.

## Okay. How can I check BootGuard status?
1. Boot with `iomem=relaxed`.
2. `sudo modprobe msr`
3. `git clone https://review.coreboot.org/coreboot`
4. `cd coreboot/util/intelmetool && make`
5. `sudo ./intelmetool -b`

<input type="text" id="search" onkeyup="search()" style="width: 100%; font-size: 16px; padding: 6px 0px; border: 1px solid #ddd;" placeholder="Search for mainboards..">

## Apple

| Model         | Category | BootGuard | Manufactoring mode | Firmware version | coreboot support |
|:--------------|:--------:|:---------:|:------------------:|:----------------:|:----------------:|
| MacbookAir7,2 | Notebook | No        | Yes                | macOS 10.13.6    | No               |

## ASRock

| Model       | Category | BootGuard | Manufactoring mode | Firmware version | coreboot support |
|:------------|:--------:|:---------:|:------------------:|:----------------:|:----------------:|
| H110M-DVS   | Desktop  | No        | No                 | Unknown          | Yes              |
| Z370 Taichi | Desktop  | Yes       | No                 | Unknown          | No               |

## ASUS

| Model            | Category | BootGuard | Manufactoring mode | Firmware version | coreboot support |
|:-----------------|:--------:|:---------:|:------------------:|:----------------:|:----------------:|
| STRIX X99 Gaming | Desktop  | No        | No                 | Unknown          | No               |
| Z170-A           | Desktop  | No        | No                 | Unknown          | No               |
| Z170I PRO GAMING | Desktop  | Yes       | No                 | Unknown          | No               |
| PRIME Z370-A     | Desktop  | Yes       | No                 | Unknown          | No               |

## Clevo

| Model                       | Category | BootGuard | Manufactoring mode | Firmware version | coreboot support |
|:----------------------------|:--------:|:---------:|:------------------:|:----------------:|:----------------:|
| N850EZ (Tuxedo Book BC1507) | Notebook | No(?)     | No                 | 1.07.08          | No               |

## Dell

| Model           | Category | BootGuard | Manufactoring mode | Firmware version | coreboot support |
|:----------------|:--------:|:---------:|:------------------:|:----------------:|:----------------:|
| XPS 13 9350     | Notebook | Yes       | No                 | 1.2.3            | No               |
| XPS 15 9560     | Notebook | Yes       | No                 | 1.12.1           | No               |
| Latitude 5490   | Notebook | Yes       | No                 | 1.4.2            | No               |
| Precision M6800 | Notebook | No        | Yes                | A26              | No               |

## Gigabyte

| Model             | Category           | BootGuard | Manufactoring mode | Firmware version | coreboot support |
|:------------------|:------------------:|:---------:|:------------------:|:----------------:|:----------------:|
| GA-Z97MX-Gaming 5 | Desktop            | Yes       | Yes                | F4 (05/2014)     | No               |
| GA-Z170N-WIFI     | Desktop            | Yes       | Yes                | F6 (10/2015)     | No               |
| GA-Z170X-Gaming 7 | Desktop            | Yes       | Yes                | F8               | No               |
| GA-SBCAP3450      | Desktop (Embedded) | Yes       | Yes                | F1 (06/2018)     | No               |

## GPD

| Model    | Category | BootGuard | Manufactoring mode | Firmware version | coreboot support |
|:---------|:--------:|:---------:|:------------------:|:----------------:|:----------------:|
| Pocket 2 | Notebook | Yes       | Yes                | 2.18.1263        | No               |

## Lenovo

| Model           | Category  | BootGuard | Manufactoring mode | Firmware version     | coreboot support |
|:----------------|:---------:|:---------:|:------------------:|:--------------------:|:----------------:|
| M900            | Desktop   | No        | No                 | FWKTBFA (2022/06/23) | In progress      |
| T470            | Noteboook | Yes       | No                 | Unknown              | No               |
| T470p           | Noteboook | Yes       | No                 | Unknown              | No               |
| X1 Carbon Gen 4 | Noteboook | Yes       | No                 | Unknown              | No               |

## MSI

| Model                  | Category | BootGuard | Manufactoring mode | Firmware version | coreboot support |
|:-----------------------|:--------:|:---------:|:------------------:|:----------------:|:----------------:|
| PRO Z690-A DDR4 (WIFI) | Desktop  | No        | Yes                | Any              | Yes              |

## Protectli

| Model | Category | BootGuard | Manufactoring mode | Firmware version | coreboot support |
|:------|:--------:|:---------:|:------------------:|:----------------:|:----------------:|
| FW6   | SBC      | No        | Yes                | Any              | Yes              |


## Supermicro

| Model         | Category | BootGuard | Manufactoring mode | Firmware version | coreboot support |
|:--------------|:--------:|:---------:|:------------------:|:----------------:|:----------------:|
| X11SAE        | Server   | No        | Unknown            | Unknown          | No               |
| X11SAE-F      | Server   | No        | Unknown            | Unknown          | No               |
| X11SAE-M      | Server   | No        | Unknown            | Unknown          | No               |
| X11SAT        | Server   | No        | Unknown            | Unknown          | No               |
| X11SAT-F      | Server   | No        | Unknown            | Unknown          | No               |
| X11SPA-T      | Server   | No        | Unknown            | Unknown          | No               |
| X11SRA        | Server   | No        | Unknown            | Unknown          | No               |
| X11SRA-F      | Server   | No        | Unknown            | Unknown          | No               |
| X11SRA-RF     | Server   | No        | Unknown            | Unknown          | No               |
| X11SRi-IF     | Server   | No        | Unknown            | Unknown          | No               |
| X11SRL-F      | Server   | No        | Unknown            | Unknown          | No               |
| X11SRM-F      | Server   | No        | Unknown            | Unknown          | No               |
| X11SRM-VF     | Server   | No        | Unknown            | Unknown          | No               |
| X11SSM-F      | Server   | No        | Unknown            | Unknown          | Yes              |
| X11SSN-E      | Server   | No        | Unknown            | Unknown          | No               |
| X11SSN-E-001  | Server   | No        | Unknown            | Unknown          | No               |
| X11SSN-E-VDC  | Server   | No        | Unknown            | Unknown          | No               |
| X11SSN-E-WOHS | Server   | No        | Unknown            | Unknown          | No               |
| X11SSN-H      | Server   | No        | Unknown            | Unknown          | No               |
| X11SSN-H-001  | Server   | No        | Unknown            | Unknown          | No               |
| X11SSN-H-VDC  | Server   | No        | Unknown            | Unknown          | No               |
| X11SSN-H-WOHS | Server   | No        | Unknown            | Unknown          | No               |
| X11SSN-L      | Server   | No        | Unknown            | Unknown          | No               |
| X11SSN-L-001  | Server   | No        | Unknown            | Unknown          | No               |
| X11SSN-L-VDC  | Server   | No        | Unknown            | Unknown          | No               |
| X11SSN-L-WOHS | Server   | No        | Unknown            | Unknown          | No               |
| X11SSQ        | Server   | No        | Unknown            | Unknown          | No               |
| X11SSQ-L      | Server   | No        | Unknown            | Unknown          | No               |
| X11SSV-LVDS   | Server   | No        | Unknown            | Unknown          | No               |
| X11SSV-M4     | Server   | No        | Unknown            | Unknown          | No               |
| X11SSV-Q      | Server   | No        | Unknown            | Unknown          | No               |
| X11SSZ-F      | Server   | No        | Unknown            | Unknown          | No               |
| X11SSZ-QF     | Server   | No        | Unknown            | Unknown          | No               |
| X11SSZ-TLN4F  | Server   | No        | Unknown            | Unknown          | No               |
