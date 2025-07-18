# LED Chaser Circuit (555 Timer + CD4017) – KiCad Project

A classic LED chaser circuit designed using **KiCad**, powered by a 555 timer and CD4017 decade counter IC. It lights up a series of LEDs one-by-one in sequence, creating a "running light" or "Knight Rider" effect.

---

## 🎯 What This Project Does

- Generates a continuous sequence of LED flashes (like chasing lights)
- Uses simple and easily available ICs: 555 Timer & CD4017
- Adjustable speed using a timing resistor/capacitor combo
- Designed as a **KiCad project** with proper PCB layout and schematic
- Great for learning KiCad, PCB design, or digital electronics

---

## 📦 Features

- 10 output LEDs (can be reduced as needed)
- 555 Timer in **astable mode** for clock generation
- CD4017 Decade Counter to handle sequencing
- Clean PCB layout with labeled connectors and components
- Optional trimmer resistor to control LED chasing speed

---

## 🧰 Components Used

| Component        | Quantity |
|------------------|----------|
| 555 Timer IC     | 1        |
| CD4017 IC        | 1        |
| LEDs             | 10       |
| 1kΩ Resistors    | 10       |
| 10kΩ potentiometer   | 1        |
| 100nF Capacitor  | 1        |
| 10µF Capacitor   | 1        |
| Power Source (5V–9V) | 1    |

---

## 🚀 How to Use

1. **Open the project** in KiCad 7.x or newer.
2. View/edit the schematic in the `.kicad_sch` file.
3. Open the `.kicad_pcb` file to view or modify the PCB layout.
4. Export Gerber files if you want to fabricate the board.
5. Assemble the board using through-hole components.
6. Power it up and enjoy the chasing LED effect!

## 🔧 Tuning the Speed

You can control how fast the LEDs chase using the **10k potentiometer** connected to the 555 timer. The values used are:

---

## 💡 Educational Value

This is a beginner-friendly project that introduces:
- Basic timer circuits
- Counter IC operation
- Sequential logic
- KiCad schematic and PCB design

Perfect for hobbyists, students, or anyone getting started with PCB design!

---

## 🙏 Credits

Circuit concept inspired by the classic LED chaser project found in many electronics books. This version was fully re-created in KiCad by **Shiva Projects** for educational use.

---

## 📄 License

Open-source hardware. You are free to modify, improve, or manufacture the board for personal or educational use.

---
images/PCB 3D view.png
