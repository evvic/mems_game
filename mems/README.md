# MEMS Integration

Integrating the **MPU-9250** with the **Arduino Uno Rev 3** via the I2C protocol

## Documents

- [MPU-9250 Register Map](https://invensense.tdk.com/wp-content/uploads/2015/02/RM-MPU-9250A-00-v1.6.pdf)
    - Use the register map to determine what address to start reading bytes from the IC
    - We care about the accelerometer / gyroscope and that block of data starts at __0x3B__

## I2C

- Being done through the [Wire.h](https://www.arduino.cc/reference/en/language/functions/communication/wire/) library built into Arduino IDE

## Circuit Diagram

[share circuit diagram here]