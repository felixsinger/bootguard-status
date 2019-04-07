# BootGuard status
## What is this?
TBD. I don't know.

## Okay. How can I check BootGuard status?
1. Boot with `iomem=relaxed`.
2. `sudo modprobe msr`
3. `git clone https://review.coreboot.org/coreboot`
4. `cd coreboot/util/intelmetool && make`
5. `sudo ./intelmetool -b`

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

## Gigabyte
| Model | Category | BootGuard | Manufactoring mode | ME version | Firmware version | coreboot support |
|:------|:--------:|:---------:|:------------------:|:----------:|:----------------:|:----------------:|
| GA-Z97MX-Gaming 5 | Desktop | Yes | Yes | 9.1 | F4 (05/2014) | No |
| GA-Z170X-Gaming 7 | Desktop | Yes | Yes | Unknown | F8 | No |

## Dell
| Model | Category | BootGuard | Manufactoring mode | ME version | Firmware version | coreboot support |
|:------|:--------:|:---------:|:------------------:|:----------:|:----------------:|:----------------:|
| XPS 15 9560 | Notebook | Yes | No | 11.8 | 1.12.1 | No |
