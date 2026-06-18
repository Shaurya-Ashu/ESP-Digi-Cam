# ESP-Digi-Cam
 It's a mini digicam powered by ESP32 cam module with
 an integrated TFT display of 1.8 inch and USB‑C powered / programming enclosed inside a 3D Printed custom case.
 with wifi sharing of img's.
# Zine
<img width="583" height="829" alt="Frame 3-2" src="https://github.com/user-attachments/assets/7783bfb8-39ca-43ae-aed5-b7f2f635f8bb" />

# Why not to build this 

 * If you already have one
 * If you are building one
 * If you don't like camera
 * IDK , i am runing out of reasons not to build it

# Schematics


<img width="2274" height="1154" alt="image" src="https://github.com/user-attachments/assets/2bb45283-8d0f-418c-883f-45df2c96a699" />


Brains/Camera:
 ESP32 CAM best and simplest for this project 

USB-C:
 an external type - c port for programing and power

UART-USB Converter:
 I have used FT232RL to convert UART to USB so that we can program the ESP32 CAM

Display:
 A 1.8 inch tft display 128 x 160 pix connected with spi interface to ESP32 CAM

Battery:
 I have added a charging module so if you want to iuntigrate a battery in it you can .

# PCB 
it is a very simple 2 layered PCB designed in EasyEDA connecting all the parts together.

Top Layer

 <img width="759" height="468" alt="Screenshot 2026-06-14 at 3 21 17 PM" src="https://github.com/user-attachments/assets/e184bc0c-ffc0-402e-91ce-6685e5b3f893" />



Bottom Layer

<img width="757" height="461" alt="Screenshot 2026-06-14 at 3 21 30 PM" src="https://github.com/user-attachments/assets/7c453073-c0b5-4051-b059-6a003baa3f1a" />


# CAD

so I've designed a 3D printed case for this digicam in Fusion 360.
it is simple 2 part case with different parts for switches.

<img width="2880" height="1226" alt="Untitled_2026-Jun-14_05-26-15PM-000_CustomizedView51561765880_png_alpha" src="https://github.com/user-attachments/assets/76b23df4-5512-4b41-bd81-a50722cf96f5" />
<img width="2880" height="1226" alt="Untitled_2026-Jun-14_06-01-42PM-000_CustomizedView3772994715_png_alpha" src="https://github.com/user-attachments/assets/a5c4ec59-9bfa-4bd7-8376-fd907ec85d33" />

<img width="1920" height="1080" alt="Untitled" src="https://github.com/user-attachments/assets/c154f966-d60f-4c85-97c4-d63f1b570a9b" />

# Assembly

The top part is screwed in the PCB & And the bottom part is just plug in.
Before packing the PCB we need to put on the button caps in their place.

<img width="1000" height="1000" alt="SCREW M2" src="https://github.com/user-attachments/assets/325e83fe-bf1f-4ff0-9113-1dc96c210929" />
<img width="328" height="512" alt="Screenshot 2026-06-14 at 9 49 44 PM" src="https://github.com/user-attachments/assets/1f1d0aa7-5e45-4688-b2e4-c2a142b264a1" />

If you want to add battery, you can include it between the display and the PCB

# Firmware 

It will show you the live footage and if you click the picture, it will be shown on your phone on the web portal
As I missed a very important part in developing this project that the in-built SD card reader in the ESP32 cam model is connected with the same pins as the SPI connection of TFT display.




