# 📡 AM Modulation & Demodulation Simulator

A Python-based graphical simulator for studying **Amplitude Modulation (AM)** and **Demodulation** concepts used in Analog Communication Systems.

This project was developed as an educational tool for Electronics & Communication Engineering (ECE) students to visualize message signals, carrier signals, AM waveforms, recovered signals, and frequency spectrum analysis.

---

## 🚀 Features

- ✅ Generate Message Signal
- ✅ Generate Carrier Signal
- ✅ Perform AM Modulation
- ✅ Perform AM Demodulation using Envelope Detection (Hilbert Transform)
- ✅ FFT Spectrum Analysis
- ✅ Bandwidth Calculation
- ✅ Export Signal Data to CSV
- ✅ User-Friendly GUI using Tkinter
- ✅ Real-Time Waveform Visualization using Matplotlib

---

## 🖥️ Technologies Used

- Python 3.x
- Tkinter
- NumPy
- SciPy
- Matplotlib
- CSV Module

---

## 📂 Project Structure

```text
AM-Modulation-Demodulation-Simulator/
│
├── am_simulator_clean.py
├── README.md
├── requirements.txt
└── screenshots/
    ├── gui.png
    ├── modulation.png
    └── fft_analysis.png
```

---

## 📖 Theory

### Amplitude Modulation (AM)

Amplitude Modulation is a communication technique in which the amplitude of a high-frequency carrier signal is varied according to the instantaneous amplitude of the message signal.

### Mathematical Expression

\[
s(t)=A_c\left[1+\mu\frac{m(t)}{A_m}\right]\cos(2\pi f_c t)
\]

Where:

- \(A_c\) = Carrier Amplitude
- \(A_m\) = Message Amplitude
- \(f_c\) = Carrier Frequency
- \(f_m\) = Message Frequency
- \(\mu\) = Modulation Index

### Bandwidth of AM Signal

\[
BW = 2f_m
\]

---

## ⚙️ Installation

### 1. Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/AM-Modulation-Demodulation-Simulator.git
```

### 2. Enter Project Directory

```bash
cd AM-Modulation-Demodulation-Simulator
```

### 3. Install Required Packages

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
python am_simulator_clean.py
```

---

## 📊 Output

The simulator displays:

- Message Signal
- Carrier Signal
- AM Modulated Signal
- Recovered Signal
- FFT Spectrum

The application also calculates the bandwidth of the AM signal.

---

## 💾 Export Feature

Users can save generated signal data as a CSV file for further analysis in:

- Microsoft Excel
- MATLAB
- Python
- GNU Octave

---

## 🎯 Educational Applications

This project can be used for:

- Analog Communication Laboratory
- Communication Systems Course
- Mini Projects
- Academic Demonstrations
- Signal Processing Visualization

---

## 🔮 Future Improvements

- Add DSB-SC Modulation
- Add SSB Modulation
- Add Frequency Modulation (FM)
- Add Noise (AWGN Channel)
- Add Signal-to-Noise Ratio (SNR) Analysis
- Add Real-Time Animation
- Add Dark Theme Interface

---

## 👨‍💻 Author

**Anurag Mukherjee**

Electronics & Communication Engineering Student

---

## 📜 License

This project is released under the MIT License.

Feel free to use, modify, and distribute this project for educational purposes.
