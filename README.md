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

| Model | Category | BootGuard | Manufactoring mode | ME version | Firmware version | coreboot support |
|:------|:--------:|:---------:|:------------------:|:----------:|:----------------:|:----------------:|
| MacbookAir7,2 | Notebook | No | Yes | 10.x | macOS 10.13.6 | No |

## ASUS

| Model | Category | BootGuard | Manufactoring mode | ME version | Firmware version | coreboot support |
|:------|:--------:|:---------:|:------------------:|:----------:|:----------------:|:----------------:|
| STRIX X99 Gaming | Desktop | No | No | 9.x | Unknown | No |
| Z170-A | Desktop | Yes | No | 11.x | Unknown | No |
| PRIME Z370-A | Desktop | Yes | No | Unknown | Unknown | No |
| Z170I PRO GAMING | Desktop | Yes | No | Unknown | Unknown | No |

## ASRock

| Model | Category | BootGuard | Manufactoring mode | ME version | Firmware version | coreboot support |
|:------|:--------:|:---------:|:------------------:|:----------:|:----------------:|:----------------:|
| Z370 Taichi | Desktop | Yes | No | Unknown | Unknown | No |
| H110M-DVS | Desktop | No | No | 11.8 | Unknown | Yes |

## Gigabyte

| Model | Category | BootGuard | Manufactoring mode | ME version | Firmware version | coreboot support |
|:------|:--------:|:---------:|:------------------:|:----------:|:----------------:|:----------------:|
| GA-Z97MX-Gaming 5 | Desktop | Yes | Yes | 9.1 | F4 (05/2014) | No |
| GA-Z170X-Gaming 7 | Desktop | Yes | Yes | Unknown | F8 | No |
| GA-Z170N-WIFI | Desktop | Yes | Yes | 11.0 | F6 (10/2015) | No |

## GPD

| Model | Category | BootGuard | Manufactoring mode | ME version | Firmware version | coreboot support |
|:------|:--------:|:---------:|:------------------:|:----------:|:----------------:|:----------------:|
| Pocket 2 | Notebook | Yes | Yes | 11.8 | 2.18.1263 | No |

## Dell

| Model | Category | BootGuard | Manufactoring mode | ME version | Firmware version | coreboot support |
|:------|:--------:|:---------:|:------------------:|:----------:|:----------------:|:----------------:|
| XPS 15 9560 | Notebook | Yes | No | 11.8 | 1.12.1 | No |

## Lenovo

| Model | Category | BootGuard | Manufactoring mode | ME version | Firmware version | coreboot support |
|:------|:--------:|:---------:|:------------------:|:----------:|:----------------:|:----------------:|
| T470p | Noteboook | Yes | No | 12.x | Unknown | No |
