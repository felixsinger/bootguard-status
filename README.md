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

| Model | Category | Generation | BootGuard | Manufactoring mode | ME version | Firmware version | coreboot support |
|:------|:--------:|:----------:|:---------:|:------------------:|:----------:|:----------------:|:----------------:|
| MacbookAir7,2 | Notebook | Broadwell | No | Yes | 10.x | macOS 10.13.6 | No |

## ASRock

| Model | Category | Generation | BootGuard | Manufactoring mode | ME version | Firmware version | coreboot support |
|:------|:--------:|:----------:|:---------:|:------------------:|:----------:|:----------------:|:----------------:|
| H110M-DVS | Desktop | Skylake  | No | No | 11.8 | Unknown | Yes |
| Z370 Taichi | Desktop | Whiskey Lake | Yes | No | Unknown | Unknown | No |

## ASUS

| Model | Category | Generation | BootGuard | Manufactoring mode | ME version | Firmware version | coreboot support |
|:------|:--------:|:----------:|:---------:|:------------------:|:----------:|:----------------:|:----------------:|
| STRIX X99 Gaming | Desktop | Haswell/Broadwell | No | No | 9.x | Unknown | No |
| Z170-A | Desktop | Skylake | Yes | No | 11.x | Unknown | No |
| Z170I PRO GAMING | Desktop | Skylake | Yes | No | Unknown | Unknown | No |
| PRIME Z370-A | Desktop | Whiskey Lake | Yes | No | Unknown | Unknown | No |

## Clevo

| Model | Category | Generation | BootGuard | Manufactoring mode | ME version | Firmware version | coreboot support |
|:------|:--------:|:---------:|:------------------:|:----------:|:----------------:|:----------------:|
| N850EZ (Tuxedo Book BC1507) | Notebook | Coffee Lake | No(?) | No | 12.0.6 | 1.07.08 | No |

## Dell

| Model | Category | Generation | BootGuard | Manufactoring mode | ME version | Firmware version | coreboot support |
|:------|:--------:|:---------:|:------------------:|:----------:|:----------------:|:----------------:|
| XPS 13 9350 | Notebook | Skylake | Yes | No | 11.0 | 1.2.3 | No |
| XPS 15 9560 | Notebook | Skylake |Yes | No | 11.8 | 1.12.1 | No |
| Latitude 5490 | Notebook | Kaby Lake R | Yes | No | 11.8 | 1.4.2 | No |

## Gigabyte

| Model | Category | Generation | BootGuard | Manufactoring mode | ME version | Firmware version | coreboot support |
|:------|:--------:|:---------:|:------------------:|:----------:|:----------------:|:----------------:|
| GA-Z97MX-Gaming 5 | Desktop | Haswell  | Yes | Yes | 9.1 | F4 (05/2014) | No |
| GA-Z170N-WIFI | Desktop | Skylake  | Yes | Yes | 11.0 | F6 (10/2015) | No |
| GA-Z170X-Gaming 7 | Desktop | Skylake  | Yes | Yes | Unknown | F8 | No |
| GA-SBCAP3450 | Desktop (Embedded) | Apollo Lake  | Yes | Yes | TXE 3.0.10.1129 | F1 (06/2018) | No |

## GPD

| Model | Category | Generation | BootGuard | Manufactoring mode | ME version | Firmware version | coreboot support |
|:------|:--------:|:----------:|:---------:|:------------------:|:----------:|:----------------:|:----------------:|
| Pocket 2 | Notebook | Amber Lake Y | Yes | Yes | 11.8 | 2.18.1263 | No |

## Lenovo

| Model | Category | Generation | BootGuard | Manufactoring mode | ME version | Firmware version | coreboot support |
|:------|:--------:|:----------:|:---------:|:------------------:|:----------:|:----------------:|:----------------:|
| T470p | Noteboook | Kaby Lake  | Yes | No | 12.x | Unknown | No |
