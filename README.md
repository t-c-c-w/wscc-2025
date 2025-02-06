# Fifth Winter School of Computational Chemistry

Welcome to the official repository for the **Fifth Winter School of Computational Chemistry**! This repository contains essential scripts, installation guides, and documentation for running computational chemistry jobs efficiently using **ORCA**, **Python**, and **Bash scripts** within **VSCode**.

## 📌 Overview
This repository is designed to help participants set up their computational environment and execute chemistry-related scripts smoothly. It includes:
- ORCA installation and setup
- Python scripts for data processing and automation
- Bash scripts for job execution
- Documentation on using **VSCode** as an IDE for running calculations

## 📦 Installation Guide
### 1️⃣ Prerequisites
Before proceeding, ensure you have the following installed:
- **VSCode** (Download: [here](https://code.visualstudio.com/))
- **ORCA** (Download: [here](https://orcaforum.kofo.mpg.de/))
- **Python (≥3.8)** (Download: [here](https://www.python.org/downloads/))
- **Bash (for Linux/Mac or Git Bash for Windows)**

### 2️⃣ Setting Up the Environment
#### ORCA Setup
1. Download and extract ORCA.
2. Add ORCA’s directory to your system’s `PATH`.
3. Set environment variables (`ORCA_PATH` and `LD_LIBRARY_PATH` on Linux/Mac).

#### Python Setup
```bash
pip install -r requirements.txt
```
This will install all required dependencies for the Python scripts.

### 3️⃣ Configuring VSCode
We recommend using **VSCode** due to its extensive extensions and strong community support. Install the following extensions:
- **Python** (for running Python scripts)
- **Bash Debug** (for debugging shell scripts)
- **Remote - SSH** (for submitting jobs on HPC clusters)

## 🚀 Running the Scripts
### Running ORCA Calculations
```bash
orca input_file.inp > output_file.out
```
### Running Python Scripts
```bash
python script.py
```
### Running Bash Scripts
```bash
bash run_job.sh
```

## 🤓 Enjoy the Quantum Chemistry Ride!
Remember, in quantum chemistry:
> *If the wavefunction isn’t real, then neither is your data!* 😆

Happy computing! 🚀🔬
