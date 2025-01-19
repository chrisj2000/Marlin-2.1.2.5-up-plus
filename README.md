# Marlin-2.1.2.5-up-plus
Marlin Project for Tiertime Up Plus 1 3d printer

using MKS Robin Nano v1.2 with uart enabled for tmc

Pin definitions to be added to end of file in src, pins, stm32f1, pins_MKS_ROBIN_NANO.h

#if HAS_TMC_UART

#define X_SERIAL_TX_PIN PA13

#define X_SERIAL_RX_PIN PA13


#define Y_SERIAL_TX_PIN PA1

#define Y_SERIAL_RX_PIN PA1


#define Z_SERIAL_TX_PIN PA6

#define Z_SERIAL_RX_PIN PA6


#define E0_SERIAL_TX_PIN PA3

#define E0_SERIAL_RX_PIN PA3


#define TMC_BAUD_RATE 19200

#endif // TMC2208 || TMC2209

![Screenshot 2025-01-19 185305](https://github.com/user-attachments/assets/37857a77-b8b5-4f63-bbb0-8fa91a94ad51)
![Screenshot 2025-01-19 185844](https://github.com/user-attachments/assets/70755d03-fe3a-47cf-a3c1-c72090430544)
