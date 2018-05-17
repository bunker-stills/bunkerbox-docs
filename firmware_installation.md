# Fimware Installation

The BunkerBox industrial controller utilizes the RED Brick microcontroller from TinkerForge. More information on the RED Brick can be found at https://www.tinkerforge.com/en/doc/Hardware/Bricks/RED_Brick.html#red-brick.

The RED Brick utilizes an RTOS running Debian Linux, and full instructions for installing the OS can be found at https://www.tinkerforge.com/en/doc/Hardware/Bricks/RED_Brick.html#red-brick-images.

To install the firmware, you will need the following items:

- A Micro-SD card with at least 8GB of space.
- A USB 2.0 Mini-B cable.

To install the Linux operating system:

1. Download the Etcher SD card flashing software from https://etcher.io/.
1. Download the latest RED Brick Image from https://www.tinkerforge.com/en/doc/Downloads.html#downloads-red-images.
1. Unzip the Red Brick Image. This should result in a file that looks something like `red_image_1_11_full.img`. You may need to install a separate program that extracts 7z files.
1. Insert a blank Micro-SD card into your computer.
1. Open the Etcher application.
1. Click the "Select image" button in Etcher and choose the `.img` file you extracted earlier.
1. Make sure the center of the Etcher screen shows your Micro-SD card— if it doesn't click the "Change" button to select it.
1. Click the "Flash!" button.
1. The flashing process may take 10-15 minutes depending on the speed of your computer and Micro-SD card.
1. Once the flashing process is done, eject the Micro-SD card from your computer, make sure the RED Brick is turned off, and insert the Micro-SD card into the RED Brick.
