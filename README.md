# F767ZI CAN Bus Loopback Test (Backup Copy 2)

> [!NOTE]
> This folder is a preserved duplicate/backup archive of [`F767ZI_CANBUS_LOOPBACK_3`](file:///c:/Users/Rangga/Documents/Old%20Project%20Archive/F767ZI_CANBUS_LOOPBACK_3).

---

## 🎯 Overview

An embedded STM32CubeIDE project for the **NUCLEO-F767ZI** evaluation board demonstrating CAN bus internal loopback self-testing using the STM32 **bxCAN** peripheral and HAL driver.

- **MCU:** STM32F767ZIT6 (ARM Cortex-M7 @ 216 MHz)
- **Evaluation Board:** NUCLEO-F767ZI
- **IDE / Toolchain:** STM32CubeIDE / GCC ARM Embedded
- **Mode:** `CAN_MODE_LOOPBACK` (internal hardware loopback without external transceiver)

---

## ⚙️ CAN Settings Summary

- **Instance:** `CAN1`
- **Bit Timing:** Prescaler = 4, BS1 = 15TQ, BS2 = 2TQ, SJW = 1TQ
- **Filter Bank:** Filter 0, ID Mask (accepts all frames into FIFO0)
- **Test ID:** Standard ID `0x11`, DLC = 2 (`[0x03, 0x01]`)
- **Status LED:**
  - **Green LED (`LD1` / `PB0`):** Pass (`HAL_OK`)
  - **Blue/Red LED (`LD2` / `PB7`):** Fail / Error

For detailed instructions and file layout, refer to the primary project:
👉 [F767ZI_CANBUS_LOOPBACK_3 README](file:///c:/Users/Rangga/Documents/Old%20Project%20Archive/F767ZI_CANBUS_LOOPBACK_3/README.md)
