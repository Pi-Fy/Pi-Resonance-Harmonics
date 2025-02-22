# Pi-Resonance-Harmonics
![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)
![Python Version](https://img.shields.io/badge/Python-3.8%2B-blue.svg)

Copyright (C) 2025 Richard Place

This project is distributed under the **GNU General Public License version 3 (GPL v3)**. By licensing this work under GPL v3, we ensure that it remains open source and accessible to the public, and that any modifications or derivative works are also distributed under the same license. This approach is intended to prevent exclusive commercialization, weaponization, or appropriation by any single entity or government.

For the full legal text, please refer to the [LICENSE](LICENSE) file in this repository.

## Installation

To set up the project and run the simulations, follow these steps:

1. **Clone the repository**:
git clone https://github.com/Pi-Fy/Pi-Resonance-Harmonics.git
cd Pi-Resonance-Harmonics

markdown
Copy

2. **Install required dependencies** (Python libraries used in the simulations):
pip install numpy scipy matplotlib qiskit


markdown
Copy

3. **Verify installation** by running:
python --version


csharp
Copy
and checking that Python is installed correctly.



## Usage

Once the dependencies are installed, you can run the simulations using the provided scripts.

Run the Fourier Spectrum Simulation
python scripts/fourier_analysis.py --input data/sample.csv --output figures/fourier_output.png

Run the Quantum Circuit Simulation
python scripts/quantum_circuit_sim.py

Run the Phase Evolution Plot
python scripts/phase_evolution.py

Results will be saved in the /figures/ directory





