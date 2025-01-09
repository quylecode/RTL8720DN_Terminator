# TERMINATOR
Terminator is the first firmware running on RTL8720DN BW16 kit.
This firmware was designed for research purpose.


# Introduction

`Terminator` is a combination of the Arduino IDE along with the LVGL v8.3.0 library and several other libraries.

# Wirings
| **RTL8720DN BW16** | **ILI9341** |
| ------------------ | --------- |
| **GND**            | GND       |
| **3.3V**           | VDD       |
| **PA15**           | CS        |
| **3.3V**           | RESET     |
| **PA26**           | DC        |
| **PA12**           | MOSI      |
| **PA14**           | SCK       |
| **3.3V**           | LED       |
| **NULL**           | MISO      |
| **PB3**            | T_CLK     |
| **GND**            | T_CS      |
| **PA25**           | T_DIN     |
| **PA30**           | T_DO      |
| **PA27**           | T_IRQ     |

![terminator wirings](./image/wiring%20diagram.png)

# DOWNLOAD / UPLOADING

## Download firmware
Just clone this repository, this firmware is `km0_km4_image2.bin`

## Upload firmware
1. Clone this repository to your Local Machine (PC or Laptop, Windows only)
2. Into folder `Image_Tool`.
3. Execute the `ImageTool.exe` by double click on the file.
4. `Chip Select` choose `AmebaD(8721D)`.
5. In the section `Flash Download`, check the box with the address `0x08006000` and then click `Browse` to select firmware `km0_km4_image2.bin`.
6. In the section `Serial` select COM port RTL8720DN BW16 is connected.
7. Plug & press buttons on RTL8720DN BW16 to enter upload mode.
8. Press `Download` button to upload firmware.
9. Wait until the uploading completed
10. Press RST or disconnect the board from power then connect it back.

## Q&A

For any questions, go to my Tiktok account @quyle2304 for supporting.
