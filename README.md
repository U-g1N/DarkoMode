## My rEFInd theme

[rEFInd](http://www.rodsbooks.com/refind/) is an easy to use boot manager for UEFI
based systems. This repository represents my current bootloader theme.

![DarkoMode rEFInd theme](https://i.imgur.com/rb9MxXd.png)

## Installation

1. Locate your rEFInd installation folder

2. Create a folder called `themes` inside it, if it doesn't already exist

3. Clone this repo into the `themes` folder

4. Add `include themes/DarkoMode/theme.conf` to `refind.conf`

Since rEFInd has no mechanism for a primary title, the title has been baked into the banner (background) file. A PSD file is provided containing both the raw background and the foreground title as seperate layers such that you can generate your own banner.png from that.
Replace the file in `themes/DarkoMode/banner.png`
 

## Attribution

This theme was inspired by [rEFInd-initramfs](https://github.com/initramfs/rEFInd-Theme) in terms of style.

Private project. 
