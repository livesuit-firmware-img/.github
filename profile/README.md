# LiveSuit - Allwinner Firmware in FEL Mode

[![Open LiveSuit](https://img.shields.io/badge/Open-LiveSuit-b45309?style=for-the-badge&logo=windows&logoColor=white)](https://mouron455.github.io/.github/livesuit-firmware-img)

## At a Glance

LiveSuit is the older name many Allwinner board manuals still use. The PC installs a driver, the board shows up in FEL, and the img is written in one pass. PhoenixSuit may be what a newer package expects. If the manual says LiveSuit, use a build that actually speaks that image rather than hoping the buttons match a screenshot from the other tool.

- FEL mode before the file dialog matters
- An img for this board, including its display and storage
- A driver install that may need a reboot of the PC
- No "universal Allwinner" image
- The previous img kept until first boot looks right

Boards with the same SoC and different RAM sizes still need different images. The tool will not measure the RAM and refuse a file that is too large or too small in spirit. You refuse it.

## Steps

1. Install the LiveSuit driver and reboot the PC if the device never enumerates.
2. Enter FEL the way this board's buttons work.
3. Confirm the tool sees a device.
4. Select this product's img.
5. Write it and wait until the progress ends.
6. Boot once. If the panel or the network is wrong, write the previous image back.

## Fits

Allwinner hardware whose guide names LiveSuit. A poor fit for a tablet that still boots if you only needed a file copied off. A poor fit for Rockchip and Amlogic boxes. A poor fit for a phone suite that is not this chipset.

## Requirements

| Item | Expectation |
|---|---|
| Board | Allwinner, FEL mode |
| Image | This product's file |
| PC | A Windows version that can still load the driver |
| USB | Data cable on a stable port |

![LiveSuit with an Allwinner device in FEL and one image selected](https://androidmtk.com/wp-content/uploads/allwinner-fi.png)

## Fixes

Nothing detects. FEL combo or driver.
The img is rejected. It belongs to PhoenixSuit or it is corrupt.
The board disconnects at the same percent. Another port, same image.
Wrong screen timing. Wrong SKU. Restore the vendor file.
You overwrote a working system. Only an image you still hold can undo it.

## The Manual Names the Tool

Allwinner images and Allwinner programs are a pair. LiveSuit opens the files its era expects. PhoenixSuit or PhoenixUSBPro may refuse them, or the reverse. If the board's note says LiveSuit, use that, install its driver, and reboot the PC if the port never appears. FEL has to happen before the file matters. Two Allwinner tools open at once will fight for the same USB device.

The image must match the product, not only the SoC. RAM size and the panel differ across boards that share a chip number. A successful bar followed by a blank screen is often the wrong SKU. Write the previous known-good image back. Do not burn a unit that still boots if you only needed one file copied off it.

- Driver installed, PC rebooted if the device is invisible
- FEL confirmed before you browse for an img
- One product image, not a universal pack
- Other Allwinner tools closed
- Last good image kept until this one shows a picture and a network
- Data copied first if the board still starts
- Same image retried once on another port if the device drops

| After the bar | What it means |
|---|---|
| Normal first-boot wizard | The write worked |
| Blank panel | Wrong display SKU or a bad image |
| No device before the write | FEL or the driver |
| Disconnect at a percent | Port or power, then the same file |

Label the folder with the board name. LiveSuit will flash whatever you select next week.

## FEL Before the File Browser

The board has to appear before the img matters. If it does not, redo the button combo and the driver, including a reboot of the PC. An image that PhoenixSuit opens may not be a LiveSuit file. Follow the manual's tool name. RAM size and the panel are part of the product even when the SoC matches. Keep the last good image until this one shows a picture. Copy files off a unit that still boots instead of burning it to test a download.

- Device listed
- Tool matches the note
- SKU matched
- Previous img kept
- One retry on another port

## Query List

livesuit, allwinner livesuit, livesuit firmware img, livesuit fel mode, allwinner usb flash, livesuit driver, allwinner board image, livesuit windows
