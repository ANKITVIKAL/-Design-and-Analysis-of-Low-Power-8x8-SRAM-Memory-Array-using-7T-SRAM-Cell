# -Design-and-Analysis-of-Low-Power-8x8-SRAM-Memory-Array-using-7T-SRAM-Cell# Low Power 8x8 SRAM Array using 7T SRAM Cell

This project presents the **design and analysis of a low power 8x8 SRAM memory array** using a **7T SRAM cell architecture**. 


Traditional SRAM designs use 6T (transistor) cells. This project investigates a 7T SRAM cell architecture that reduces static power consumption by adding an extra NMOS transistor between the inverters. The entire design was implemented and simulated using **Cadence** with the **gpdk 90nm technology**.

## 🔧 Components Designed

- **7T SRAM Cell**
- **Precharge Circuit**
- **Write Driver**
- **Sense Amplifier**
- **3:8 Row Decoder**
- **8x8 Memory Array**

## 🧪 Simulation Details

- **Technology Used**: 90nm GPDK (Cadence)
- **Supply Voltage**: 0.7V
- **Temperature**: 27°C
- **Read Access Time**: 10.1ns
- **Write Access Time**: 10.5ns
- **Leakage Power**: 2.34nW (cell), 9.36nW (total)

## 📊 Results

| Parameter                 | Value      |
|--------------------------|------------|
| Array Size               | 8x8 (128 bits) |
| Supply Voltage           | 0.7V       |
| Leakage Power (Cell)     | 2.34 nW    |
| Total Leakage Power      | 9.36 nW    |
| Read Access Time         | 10.1 ns    |
| Write Access Time        | 10.5 ns    |


