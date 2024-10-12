# RP2040 Motion Logger

## Overview
The RP2040 Motion Logger is a custom microcontroller board based on the RP2040 chip, designed for motion data logging and versatile IoT applications. This compact board (0.9 x 2.48 inches) integrates a wide range of features, making it a powerful tool for projects requiring motion sensing, storage, and connectivity.

### Key Features:
- **Microcontroller**: RP2040 with dual ARM Cortex M0+ processors
- **Motion Sensor**: ICM-42688-P IMU for 6-axis motion tracking
- **Storage**: 128 Mbit Quad SPI Flash Memory and SD Card connector
- **Power Options**: USB Type-C connector or 1S LiPo/Li-ion battery
- **Battery Management**: Onboard charger for 1S LiPo/Li-ion batteries
- **LEDs**: Addressable RGB LED for user indications, plus power status LEDs for both 3.3V and 5V
- **Connectors**:
  - TC2030 JTAG Connector for programming and debugging
  - Dual sets of pin headers including UART, I2C, SPI, ADC, and GPIO pins
- **Power Supply**: 3.3V buck converter supporting up to 2A current
- **Additional Features**: Reset and Bootloader buttons, ESD protection, USB Power, Battery Power, and 3.3V Power pins on headers

### Power Options:
The RP2040 Motion Logger can be powered either via the USB Type-C connector or a 1S LiPo/Li-ion battery, allowing for flexible deployment options. 

### Programming Options:
You can program the board through the USB Type-C connector or the TC2030 JTAG Connector using the SWDIO and SWCLK pins.

## Getting Started
1. **Power Up**: Connect the board via USB Type-C or connect a 1S LiPo/Li-ion battery.
2. **Programming**: Use either the USB connection or JTAG connector with an appropriate debugger to flash your code.
3. **Bootloader Mode**: Hold down the Bootloader button while connecting the board to USB to enter bootloader mode.
4. **Data Logging**: Use the IMU and available storage to log motion data, or extend functionality via UART, I2C, SPI, and ADC pins.

## Hardware Pinout
- **UART**: TX, RX
- **I2C**: SDA, SCL
- **SPI**: MISO, MOSI, SCK, SS
- **ADC**: 4 ADC-capable pins
- **GPIO**: Multiple general-purpose pins for digital I/O
- **Power Pins**: USB Power, Battery Power, 3.3V Power

## Advertisement: PCBWay - PCB Manufacturing and Assembly
This project was proudly sponsored by **PCBWay**, a leading PCB manufacturer and assembler. They provided high-quality PCB manufacturing and assembly services, ensuring that the RP2040 Motion Logger board was produced to the highest standards. Here’s why PCBWay is a great choice for PCB production:

- **Exceptional Quality**: The PCBs produced by PCBWay have excellent build quality, with precise soldering and thorough assembly.
- **Fast Service**: PCBWay offers quick turnaround times, so your project can stay on track.
- **Comprehensive Services**: From prototyping to mass production, PCBWay provides services for all stages of PCB development, including multi-layer PCBs, advanced PCBs, flexible PCBs, and assembly services.
- **Affordable Pricing**: PCBWay offers competitive pricing without compromising quality.
  
![PCBWay](https://www.pcbway.com/ad/resource/logo/logo3.png)

If you’re looking for a reliable partner to bring your PCB projects to life, check out PCBWay [here](https://www.pcbway.com). With their extensive capabilities and top-notch customer support, PCBWay is the ideal choice for makers, engineers, and businesses alike.

## Testing and Quality Assurance
The RP2040 Motion Logger has been thoroughly tested and is fully functional. All components, including the IMU, flash memory, and power circuitry, work as expected. PCBWay's manufacturing and assembly have been excellent, with perfect solder joints and overall build quality.

## License
This project is open-source, licensed under the MIT License. Feel free to modify and distribute as per the license terms.

## Contributing
Contributions are welcome! Please fork the repository, make your changes, and submit a pull request. 

