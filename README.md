# 📡 AM Modulation & Demodulation Simulator

A modern Python-based GUI simulator for studying **Amplitude Modulation (AM)** and **Demodulation** concepts used in Analog Communication Systems.

Designed for Electronics & Communication Engineering (ECE) students, this simulator provides real-time visualization of:

- Message Signal
- Carrier Signal
- AM Modulated Signal
- Envelope Detection
- Recovered Message Signal
- Power Analysis
- Bandwidth Calculation

---

## 🚀 Features

### 📊 Signal Generation
- Generate Message Signal
- Generate Carrier Signal
- Generate AM Modulated Signal
- Adjustable parameters:
  - Message Frequency (fm)
  - Carrier Frequency (fc)
  - Message Amplitude (Am)
  - Carrier Amplitude (Ac)
  - Modulation Index (μ)

### 📈 Real-Time Visualization
- Interactive waveform plots
- Dynamic updates using sliders
- Engineering-style graphs

### 📡 Demodulation
- Envelope Detection
- Butterworth Low-Pass Filtering
- DC Offset Removal
- Recovered Message Signal Display

### ⚡ Signal Analysis
- Modulation Index Calculation
- Carrier Power
- Sideband Power
- Total Power
- Bandwidth Calculation

### 💾 Export Options
- Export Modulation Graphs as PNG
- Export Demodulation Graphs as PNG
- Save Signal Data as CSV

### 🎨 Modern GUI
- Dark Theme Interface
- Interactive Controls
- Responsive Layout
- Professional Engineering Dashboard

---

## 🧮 AM Equation

\[
s(t)=A_c[1+\mu\cos(2\pi f_m t)]\cos(2\pi f_c t)
\]

Where:

| Symbol | Description |
|----------|-------------|
| Ac | Carrier Amplitude |
| μ | Modulation Index |
| fm | Message Frequency |
| fc | Carrier Frequency |

---

## 📚 Theory Covered

### Amplitude Modulation (AM)

Amplitude Modulation is a technique where the amplitude of a high-frequency carrier signal is varied according to the instantaneous amplitude of the message signal.

### Modulation Index

\[
\mu = \frac{A_m}{A_c}
\]

- μ < 1 → Under Modulation
- μ = 1 → Perfect Modulation
- μ > 1 → Over Modulation

### Bandwidth

\[
BW = 2f_m
\]

### Carrier Power

\[
P_c=\frac{A_c^2}{2}
\]

### Total Power

\[
P_t=P_c\left(1+\frac{\mu^2}{2}\right)
\]

---

## 🛠️ Technologies Used

- Python 3.x
- Tkinter
- NumPy
- SciPy
- Matplotlib

---

## 📦 Installation

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/am-modulation-simulator.git
cd am-modulation-simulator
```

### 2. Install Dependencies

```bash
pip install numpy scipy matplotlib
```

### 3. Run Application

```bash
python am_simulator.py
```

---

## 📂 Project Structure

```text
AM-Modulation-Simulator/
│
├── am_simulator.py
├── README.md
├── requirements.txt
├── screenshots/
│   ├── modulation.png
│   └── demodulation.png
└── exports/
```

---

## 📷 Screenshots

### Signal Parameters

Add screenshot here:

```text
screenshots/parameters.png
```

### Modulation Window

Add screenshot here:

```text
screenshots/modulation.png
```

### Demodulation Window

Add screenshot here:

```text
screenshots/demodulation.png
```

---

## 🎯 Educational Applications

This simulator can be used for:

- Analog Communication Laboratory
- Communication Systems Projects
- ECE Mini Projects
- Engineering Demonstrations
- Classroom Teaching
- Self-Learning of AM Concepts

---

## 🔬 Future Enhancements

- Frequency Modulation (FM)
- Phase Modulation (PM)
- DSB-SC Simulation
- SSB Simulation
- Spectrum Analyzer
- FFT Visualization
- Noise Analysis
- SDR Integration

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push to branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 📄 License

MIT License

Copyright (c) 2026

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files to deal in the Software without restriction.

---

## 👨‍💻 Author

**Anurag Mukherjee**

Electronics & Communication Engineering Student

Focused on:
- Analog Communication
- Signal Processing
- Embedded Systems
- Python Development
- Electronics Simulations

---

⭐ If you found this project useful, consider giving it a star on GitHub.
