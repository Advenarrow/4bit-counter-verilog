# 4-bit Synchronous Counter — Verilog HDL

A 4-bit synchronous up counter designed and simulated using Verilog HDL.
Built as part of my VLSI/RTL Design learning journey.

## 📁 Files

| File | Description |
|------|-------------|
| `counter.v` | RTL design — main Verilog module |
| `counter_tb.v` | Testbench for simulation |
| `counter.vvp` | Compiled simulation output (Icarus Verilog) |
| `counter.vcd` | Value Change Dump file for waveform viewing |
| `output_image.png` | GTKWave waveform screenshot |

## 🛠️ Tools Used

- **Icarus Verilog** — HDL compilation and simulation
- **GTKWave** — Waveform visualization
- **VS Code** — Code editor

## ▶️ How to Simulate
```bash
iverilog -o counter counter.v counter_tb.v
vvp counter
gtkwave counter.vcd
```

## 📊 Waveform Output

![GTKWave Output](output_image.png)

## 👤 Author

**Akash M**
- GitHub: [@Advenarrow](https://github.com/Advenarrow)
- LinkedIn: [Akash M](https://linkedin.com/in/akash-m-4b6b0a27a)
- B.E. Electronics and Communication Engineering
- Government College of Engineering Tirunelveli
