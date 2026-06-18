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
