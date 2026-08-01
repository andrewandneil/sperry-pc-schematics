# Sperry 3070 Motherboard Schematics
I obatined a Sperry 3070 IBM PC clone that was dead. It had several issues, the first being a faulty clock. I started to trace the signals out and laying out the schematics, and started going further as more issues cropped up. As of me writing this, it's still not alive unfortunately, but I'm getting there.

The board was made my Mitsubishi and has a model DC080041B. I doubt this was a unique board to my specific Sperry PC, so if you have the same board you should be able to use this.

Please excuse how messy the schematic is! It was never intended to be easy to read, I am merely adding stuff as I find it.

Due to the chips having no unique identifiers I have had to create some, see the image in the root of the repo for the chip markings.

I'd say I'm about 90% done. Most of the logic is there, it just needs tidying, making easier to read, and finishing laying out the bus paths.

The Motherboard has markings:
- WESYIC
- DC080041B

# DC280182B Floppy Drive Controller
I've also started to reverse engineer the floppy drive controller the machine came with. You'll find them in the folder DC280182B_FDC. Same principle with the chip markings apply; it doesn't have any so I've had to make some, check the root directory for an image with all the markings on it.

The Floppy Drive Controller has markings:
- WEFD10
- DC280182B
- "Flexible Disk"

### Disclaimer!
I have tried my best to make these as correct as they can be. But do note they are more than likely not 100% correct and accurate. I'm simply uploading them here on the off chance someone else can make use of them.
