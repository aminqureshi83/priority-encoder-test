# Priority Encoder in Verilog

## 📌 Overview

This project implements a parameterized priority encoder in Verilog. The design supports configurable width and MSB/LSB priority selection.

## ⚙️ Features

* Parameterized design (WIDTH)
* Configurable priority (MSB / LSB)
* Synthesizable Verilog (FPGA compatible)
* Testbench with waveform verification

## 🧪 Simulation

Simulation is performed using Icarus Verilog and GTKWave.

### Run Commands

```bash
iverilog -o priority_encoder.vvp src/priority_encoder.v tb/priority_encoder_tb.v
vvp priority_encoder.vvp
gtkwave dump.vcd
```

## 📊 Waveform Output

![Waveform](docs/waveform.png)

## 🛠️ Tools Used

* Icarus Verilog
* GTKWave

## 🎯 Applications

* Digital systems design
* FPGA-based signal processing
* Control logic design

## 👨‍💻 Author

Amin Qureshi
