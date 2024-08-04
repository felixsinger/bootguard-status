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

| Model         | Category | BootGuard | Manufactoring mode | coreboot support |
|:--------------|:--------:|:---------:|:------------------:|:----------------:|
| MacbookAir7,2 | Notebook | No        | Yes                | No               |

## ASRock

| Model           | Category | BootGuard | Manufactoring mode | coreboot support |
|:----------------|:--------:|:---------:|:------------------:|:----------------:|
| H97 Anniversary | Desktop  | No        | No                 | No               |
| H110M-DVS       | Desktop  | No        | No                 | Yes              |
| Z370 Taichi     | Desktop  | Yes       | No                 | No               |

## ASUS

| Model                  | Category | BootGuard | Manufactoring mode | coreboot support |
|:-----------------------|:--------:|:---------:|:------------------:|:----------------:|
| STRIX X99 Gaming       | Desktop  | No        | No                 | No               |
| Z170-A                 | Desktop  | No        | No                 | No               |
| Z170I PRO GAMING       | Desktop  | No        | No                 | No               |
| PRIME Z370-A           | Desktop  | Yes       | No                 | No               |
| SABERTOOTH Z170 MARK 1 | Desktop  | No        | Unknown            | No               |
| SABERTOOTH Z170 S      | Desktop  | No        | Unknown            | No               |
| Z170 PRO GAMING        | Desktop  | No        | Unknown            | No               |
| Z170 PRO GAMING/AURA   | Desktop  | No        | Unknown            | No               |
| Z170-AR                | Desktop  | No        | Unknown            | No               |
| Z170-DELUXE            | Desktop  | No        | Unknown            | No               |
| Z170-E                 | Desktop  | No        | Unknown            | No               |
| Z170-K                 | Desktop  | No        | Unknown            | No               |
| Z170M-E D3             | Desktop  | No        | Unknown            | No               |
| Z170M-PLUS             | Desktop  | No        | Unknown            | No               |
| Z170M-PLUS/BR          | Desktop  | No        | Unknown            | No               |
| Z170-P D3              | Desktop  | No        | Unknown            | No               |
| Z170-PREMIUM           | Desktop  | No        | Unknown            | No               |
| Z170-PRO               | Desktop  | No        | Unknown            | No               |
| Z170-WS                | Desktop  | No        | Unknown            | No               |

## Clevo

| Model                       | Category | BootGuard | Manufactoring mode | coreboot support |
|:----------------------------|:--------:|:---------:|:------------------:|:----------------:|
| N850EZ (Tuxedo Book BC1507) | Notebook | No(?)     | No                 | No               |

## Dell

| Model           | Category | BootGuard | Manufactoring mode | coreboot support |
|:----------------|:--------:|:---------:|:------------------:|:----------------:|
| XPS 13 9350     | Notebook | Yes       | No                 | No               |
| XPS 15 9560     | Notebook | Yes       | No                 | No               |
| Latitude 5490   | Notebook | Yes       | No                 | No               |
| Precision M6800 | Notebook | No        | Yes                | No               |

## Gigabyte

| Model             | Category           | BootGuard | Manufactoring mode | coreboot support |
|:------------------|:------------------:|:---------:|:------------------:|:----------------:|
| GA-Z97MX-Gaming 5 | Desktop            | Yes       | Yes                | No               |
| GA-Z170N-WIFI     | Desktop            | Yes       | Yes                | No               |
| GA-Z170X-Gaming 7 | Desktop            | Yes       | Yes                | No               |
| GA-SBCAP3450      | Desktop (Embedded) | Yes       | Yes                | No               |
| GA-B250M-DS3H     | Desktop            | No        | Yes                | No               |

## GPD

| Model    | Category | BootGuard | Manufactoring mode | coreboot support |
|:---------|:--------:|:---------:|:------------------:|:----------------:|
| Pocket 2 | Notebook | Yes       | Yes                | No               |

## HP (Hewlett-Packard)

| Model                | Category | BootGuard | Manufactoring mode | coreboot support |
|:---------------------|:--------:|:---------:|:------------------:|:----------------:|
| Elitedesk 800 G2 SFF | Desktop  | No        | Unknown            | No               |

## Lenovo

| Model           | Category  | BootGuard | Manufactoring mode | coreboot support |
|:----------------|:---------:|:---------:|:------------------:|:----------------:|
| M700            | Desktop   | No        | No                 | In progress      |
| M900            | Desktop   | No        | No                 | In progress      |
| T460s           | Noteboook | Yes       | No                 | No               |
| T470            | Noteboook | Yes       | No                 | No               |
| T470p           | Noteboook | Yes       | No                 | No               |
| X1 Carbon Gen 4 | Noteboook | Yes       | No                 | No               |
| P14s Gen 1      | Notebook  | Yes       | No                 | No               |

## MSI

| Model                  | Category | BootGuard | Manufactoring mode | coreboot support |
|:-----------------------|:--------:|:---------:|:------------------:|:----------------:|
| PRO Z690-A DDR4 (WIFI) | Desktop  | No        | Yes                | Yes              |

## Protectli

| Model | Category | BootGuard | Manufactoring mode | coreboot support |
|:------|:--------:|:---------:|:------------------:|:----------------:|
| FW6   | SBC      | No        | Yes                | Yes              |

## Sophos (Caswell)

| Model                  | Category                   | BootGuard | Manufactoring mode | coreboot support |
|:-----------------------|:--------------------------:|:---------:|:------------------:|:----------------:|
| XG330r2 (AIA-5276-EK)  | Network appliance / Server | No        | Yes                | No               |

## Supermicro

| Model         | Category | BootGuard | Manufactoring mode | coreboot support |
|:--------------|:--------:|:---------:|:------------------:|:----------------:|
| X11SAE        | Server   | No        | Unknown            | No               |
| X11SAE-F      | Server   | No        | Unknown            | No               |
| X11SAE-M      | Server   | No        | Unknown            | No               |
| X11SAT        | Server   | No        | Unknown            | No               |
| X11SAT-F      | Server   | No        | Unknown            | No               |
| X11SPA-T      | Server   | No        | Unknown            | No               |
| X11SRA        | Server   | No        | Unknown            | No               |
| X11SRA-F      | Server   | No        | Unknown            | No               |
| X11SRA-RF     | Server   | No        | Unknown            | No               |
| X11SRi-IF     | Server   | No        | Unknown            | No               |
| X11SRL-F      | Server   | No        | Unknown            | No               |
| X11SRM-F      | Server   | No        | Unknown            | No               |
| X11SRM-VF     | Server   | No        | Unknown            | No               |
| X11SSM-F      | Server   | No        | Unknown            | Yes              |
| X11SSN-E      | Server   | No        | Unknown            | No               |
| X11SSN-E-001  | Server   | No        | Unknown            | No               |
| X11SSN-E-VDC  | Server   | No        | Unknown            | No               |
| X11SSN-E-WOHS | Server   | No        | Unknown            | No               |
| X11SSN-H      | Server   | No        | Unknown            | No               |
| X11SSN-H-001  | Server   | No        | Unknown            | No               |
| X11SSN-H-VDC  | Server   | No        | Unknown            | No               |
| X11SSN-H-WOHS | Server   | No        | Unknown            | No               |
| X11SSN-L      | Server   | No        | Unknown            | No               |
| X11SSN-L-001  | Server   | No        | Unknown            | No               |
| X11SSN-L-VDC  | Server   | No        | Unknown            | No               |
| X11SSN-L-WOHS | Server   | No        | Unknown            | No               |
| X11SSQ        | Server   | No        | Unknown            | No               |
| X11SSQ-L      | Server   | No        | Unknown            | No               |
| X11SSV-LVDS   | Server   | No        | Unknown            | No               |
| X11SSV-M4     | Server   | No        | Unknown            | No               |
| X11SSV-Q      | Server   | No        | Unknown            | No               |
| X11SSZ-F      | Server   | No        | Unknown            | No               |
| X11SSZ-QF     | Server   | No        | Unknown            | No               |
| X11SSZ-TLN4F  | Server   | No        | Unknown            | No               |
