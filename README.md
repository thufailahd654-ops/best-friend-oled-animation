# best-friend-oled-animation
An animated display project for 128x64 SSD1306 OLED using Arduino. Plays a 294-frame animation stored in PROGMEM

## Hardware
- Arduino (Uno / Nano / ESP32)
- SSD1306 OLED 128x64 (I2C, address 0x3C)

## Wiring (I2C)
| OLED | Arduino |
|------|---------|
| VCC  | 3.3V / 5V |
| GND  | GND |
| SDA  | A4 (Uno) / GPIO21 (ESP32) |
| SCL  | A5 (Uno) / GPIO22 (ESP32) |

## Libraries Required
- Adafruit GFX Library
- Adafruit SSD1306

Install via Arduino Library Manager.

## How It Works
- 294 bitmap frames stored in PROGMEM (flash memory)
- Each frame is 128x64px (1-bit)
- Frame delay: 70ms (~14 FPS)
- Loops continuously

## Part of Rawbotics
Learn robotics. Build along.
[@rawbotics.io](https://instagram.com/rawbotics.io)
