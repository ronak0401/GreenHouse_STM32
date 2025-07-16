# GreenHouse_STM32 🌱

A STM32-based greenhouse temperature monitoring and control system.

This project reads temperature using a DHT11 sensor, displays it on a 2-digit 7-segment display, and activates a cooling fan using an L298N motor driver if the temperature exceeds a threshold.

## 🧠 Features
- Real-time temperature reading with DHT11
- Multiplexed display using 7-segment common anode LEDs
- Fan control logic using L298N
- Timer-based refresh using STM32 TIM2 interrupt

## 🔧 Hardware Used
- STM32F407VG (or compatible STM32 board)
- DHT11 temperature and humidity sensor
- 2-digit common-anode 7-segment display
- L298N motor driver (for DC fan or exhaust control)
- Power supply & jumper wires

## 🛠️ Software Used
- STM32CubeMX
- Keil uVision (with .uvprojx project file)
- HAL drivers for GPIO, Timers

## 📁 Project Structure

## Author Ronak Agarwal,Rahil Khan
![WhatsApp Image 2025-07-01 at 15 43 24_1eeda267](https://github.com/user-attachments/assets/48a673fa-de49-4417-8a9c-6189fe32c857)


