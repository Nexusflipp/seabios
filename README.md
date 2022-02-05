# seabios-spf


<br>

<p align="center"> 
    <a href="#" target="_blank"> <img src="https://img.shields.io/tokei/lines/github/nexusflipp/seabios"/> </a>
    <a href="#" target="_blank"> <img src="https://img.shields.io/github/issues/nexusflipp/seabios"/> </a>
    <a href="#" target="_blank"> <img src="https://img.shields.io/github/languages/top/nexusflipp/seabios"/> </a> 
    <a href="#" target="_blank"> <img src="https://img.shields.io/github/languages/count/nexusflipp/seabios"/> </a> 
    <a href="#" target="_blank"> <img src="https://img.shields.io/github/last-commit/nexusflipp/seabios"/> </a> 
    <a href="#" target="_blank"> <img src="https://img.shields.io/github/repo-size/nexusflipp/seabios"/> </a> 
    <a href="#" target="_blank"> <img src="https://img.shields.io/github/languages/code-size/nexusflipp/seabios"/> </a> 
</p>

<br>

Custom/Spoofed seabios source (rel-1.15.0).
Please see build and developer information at: http://seabios.org/Developer_Documentation
SeaBIOS is built for QEMU and tested on QEMU.

<br>

## Build Instructions

First cd into the project directory, then run the following commands:

```shell
make menuconfig 
```

```shell
make
```

```shell
qemu -bios out/bios.bin
```
<br>

Or you could use my PKGBUILD file.
