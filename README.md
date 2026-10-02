# ESP32 CYD — Cheap Yellow Display

Schematic and PCB design for the **ESP32 Cheap Yellow Display (CYD)**, made in EasyEDA Standard.

I started this project to make it easier to work on the CYD hardware and explore improvements such as Li-Po battery support, USB-C, and a few other changes. I'm sharing it here on GitHub to keep the design files together and make it easier for others to build on the project.

You can also find and edit the project on [EasyEDA / OSHWLab](https://oshwlab.com/mariusmym/esp32_cyd_cheap_yellow_display).

> **Work in progress:** I haven't tested this design yet. If you decide to build it, please double-check the schematic and PCB routing before ordering boards.

## Hardware

The design includes an ESP32-WROOM-32, an ILI9341 display interface, an XPT2046 touch controller, a CH340C USB-to-serial interface, a microSD card connector, an RGB LED, and BOOT / RESET buttons.

Li-Po support and USB-C are improvements I'd like to explore as the project develops (if I will ever have the time to do it).

## Files

```text
ESP32_CYD/
├── README.md
├── SCHEMATIC/   # EasyEDA schematic source and PDF
├── PCB/         # Editable EasyEDA PCB design
├── GERBER/      # Gerber and drill files for PCB fabrication
├── BOM/         # Bill of materials
├── PNP/         # Pick-and-place files for assembly
└── Images/      # Board images, 3D renders, and photos
```

To view or modify the design online, open the [EasyEDA project](https://oshwlab.com/mariusmym/esp32_cyd_cheap_yellow_display) and select **Open in Editor** under the schematic or PCB.

If you're having boards assembled, use the Gerber, BOM, and pick-and-place files from the same revision.

## 3D-Printed Case

You can find the case files on [MakerWorld](https://makerworld.com/en/models/564905-esp32-2432s028-usb-c-case-cyd-cyd2usb#profileId-1126410). Check the fit and connector positions against the board version you're using before printing.

## Ideas and Improvements

Found a mistake or made an improvement? Feel free to open an issue or a pull request. I'd also love to hear from you if you build and test the board.

Make it better and share your work!

## License

This project is shared under **CC BY-SA 4.0**.
