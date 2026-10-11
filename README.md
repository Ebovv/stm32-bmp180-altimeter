# STM32 BMP180 Altimeter

An STM32-based relative altitude measurement project using a BMP180
barometric pressure sensor and an SSD1306 OLED display.

## Hardware

- STM32F103CBT6
- BMP180 barometric pressure sensor
- SSD1306 OLED display
- Buzzer

## Features

- Reads altitude data from the BMP180 sensor.
- Uses the initial altitude reading as a reference.
- Displays relative altitude change on the OLED.
- Activates a buzzer when the measured altitude change drops below -30 m.

## Development Environment

- STM32CubeIDE
- STM32 HAL
- I2C communication

## Third-Party Libraries

- BMP180 driver: [eepj/stm32-bmp180](https://github.com/eepj/stm32-bmp180)
- SSD1306 OLED driver: Based on code obtained from [ControllersTech](https://controllerstech.com/oled-display-using-i2c-stm32/).

Please refer to the original projects and their applicable license terms.

## Notes

This project displays altitude change relative to the initial reading,
not absolute altitude.
