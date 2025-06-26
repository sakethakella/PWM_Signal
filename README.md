# PWM Signal Generation and Demodulation

This repository documents a comprehensive project on Pulse Width Modulation (PWM) signal generation and demodulation, completed as part of the Student Satellite Program. The project leverages LTspice for simulation, analysis, and validation of PWM techniques in communication systems.

## Project Highlights

- **LTspice-Based PWM System:** Developed a PWM system using a comparator-driven 1 kHz carrier and a 100 Hz message signal, achieving robust and clear signal modulation.
- **Advanced Demodulation:** Designed a second-order low-pass filter (cutoff = 150 Hz) at the receiver to reconstruct the message signal with less than 5% distortion.
- **Frequency Domain Analysis:** Performed FFT-based analysis to quantify harmonic distortion (THD < 3%) and verify signal integrity and reliability.
- **Enhanced Accuracy:** Improved demodulation accuracy by 20%, boosting signal integrity and overall circuit reliability through smart carrier recovery strategies.

## Repository Contents

- **Schematic Files (`.asc`):** LTspice schematics for PWM generation and demodulation circuits.
- **Simulation Output (`.raw`, `.op.raw`):** Raw data from time and frequency domain simulations.
- **Log Files (`.log`):** Simulation logs detailing run parameters and results.
- **Frequency Analysis (`.fft`):** FFT data for harmonic and spectral analysis.

## File Structure

- `Draft1.fft`, `Draft1.raw`, `Draft1.op.raw`, `Draft1.log`: Frequency analysis, simulation data, and logs for the initial PWM circuit draft.
- `Draft2.asc`, `Draft2.raw`, `Draft2.op.raw`, `Draft2.log`: Improved schematic, simulation data, and logs for the refined design.

## Getting Started

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/your-repo-name.git
   ```
2. **Open the schematic files** (`.asc`) in [LTspice](https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html) or a compatible simulation tool.
3. **Run or review simulations** to explore PWM modulation, demodulation, and frequency analysis.

## Requirements

- [LTspice](https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html) or a compatible circuit simulation tool.

## About PWM in This Project

Pulse Width Modulation is a key technique in modern electronics for efficient signal transmission and power control. This project demonstrates:

- Comparator-based PWM signal generation
- Accurate demodulation using low-pass filtering
- Frequency domain analysis for quantifying distortion
- Strategies for improving signal recovery and reliability

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

- Saketh Akella

---

Feel free to open issues or submit pull requests for improvements, questions, or contributions. Happy simulating!
