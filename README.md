# LTspice Circuit Netlist Generator for ML Fault Dataset

A Python-based interactive tool that automatically generates **LTspice circuit netlists (.cir)** and **schematic files (.asc)** for common analog circuits.

This tool is designed to help:
- Students learning circuit simulation
- Researchers generating datasets for ML-based fault detection
- Engineers who want fast LTspice circuit creation
- ECE/VLSI students building strong resume projects

The script supports **healthy and faulty circuit variants**, enabling automated dataset generation for AI/ML models.

---

## Project Overview

Creating datasets for circuit fault detection is time-consuming because each circuit must be manually drawn and modified.

This tool automates the process by:
1. Asking the user for circuit parameters
2. Generating LTspice netlists automatically
3. Creating schematic files
4. Allowing fault injection
5. Saving simulation-ready files

The generated files can be directly opened in LTspice.

Source code: :contentReference[oaicite:1]{index=1}

---

## Key Features

- Interactive command-line interface
- Generates LTspice compatible netlists (.cir)
- Automatically creates schematic files (.asc)
- Supports multiple analog circuit types
- Built-in fault injection for ML dataset creation
- Supports unit parsing (1k, 10uF, 5mH etc.)
- Can automatically open LTspice
- Easily extensible architecture

---

## Supported Circuits

The tool currently supports the following circuits:

### Passive Circuits
- RC Low Pass Filter
- RC High Pass Filter
- Voltage Divider

### RLC Circuits
- Series RLC Circuit
- Parallel RLC Circuit
- RLC Band Pass Filter
- RLC Band Stop Filter

### Power Electronics
- Half Wave Rectifier

### Custom Circuit
- User-defined LTspice netlist

---

## Why this Project is Useful

This project is especially useful for:

### Machine Learning Dataset Generation
Fault detection models require large datasets of:
- Normal circuit behavior
- Faulty circuit behavior

This tool allows easy creation of datasets by injecting faults such as:
- Open circuit
- Short circuit
- Parameter deviation

---

# LTspice Circuit Netlist Generator for ML Fault Dataset

A Python-based interactive tool that automatically generates **LTspice circuit netlists (.cir)** and **schematic files (.asc)** for common analog circuits.

This tool is designed to help:
- Students learning circuit simulation
- Researchers generating datasets for ML-based fault detection
- Engineers who want fast LTspice circuit creation
- ECE/VLSI students building strong resume projects

The script supports **healthy and faulty circuit variants**, enabling automated dataset generation for AI/ML models.

---

## Project Overview

Creating datasets for circuit fault detection is time-consuming because each circuit must be manually drawn and modified.

This tool automates the process by:
1. Asking the user for circuit parameters
2. Generating LTspice netlists automatically
3. Creating schematic files
4. Allowing fault injection
5. Saving simulation-ready files

The generated files can be directly opened in LTspice.

---

## Key Features

- Interactive command-line interface
- Generates LTspice compatible netlists (.cir)
- Automatically creates schematic files (.asc)
- Supports multiple analog circuit types
- Built-in fault injection for ML dataset creation
- Supports unit parsing (1k, 10uF, 5mH etc.)
- Can automatically open LTspice
- Easily extensible architecture

---

## Supported Circuits

The tool currently supports the following circuits:

### Passive Circuits
- RC Low Pass Filter
- RC High Pass Filter
- Voltage Divider

### RLC Circuits
- Series RLC Circuit
- Parallel RLC Circuit
- RLC Band Pass Filter
- RLC Band Stop Filter

### Power Electronics
- Half Wave Rectifier

### Custom Circuit
- User-defined LTspice netlist

---

## Why this Project is Useful

This project is especially useful for:

### Machine Learning Dataset Generation
Fault detection models require large datasets of:
- Normal circuit behavior
- Faulty circuit behavior

This tool allows easy creation of datasets by injecting faults such as:
- Open circuit
- Short circuit
- Parameter deviation

---

🔧 **LTspice Circuit Netlist Generator (Python Tool)**

I developed a Python-based automation tool that generates **LTspice circuit files (.cir & .asc)** for analog circuits and helps create datasets for **fault detection using Machine Learning**.

This project demonstrates my interest in **Circuit Design, Simulation Automation, and AI-based fault detection systems**.

---

## Key Feature – LTspice Auto Launch

The script automatically detects LTspice installation and can directly open generated circuits.

Supported install paths:

```
C:\Program Files\ADI\LTspice
C:\Program Files\LTC\LTspiceXVII
```

---

## Installation Requirements

* Python 3.7+
* LTspice (optional but recommended)

---

## How to Use

### Step 1 – Clone Repository

```
git clone https://github.com/Arpit192005/ltspice-Circuit-Generator.git
cd ltspice-netlist-generator
```

### Step 2 – Run Script

```
python ltspice_generator.py
```

---

## Usage Workflow

### Step 1 – Select Circuit Type

Example:

```
Select circuit type:
[1] RC Low-Pass Filter
[2] RC High-Pass Filter
[3] RLC Band-Pass Filter
...
```

---

### Step 2 – Enter Component Values

Example:

```
Resistance R [default: 1k]:
Capacitance C [default: 1u]:
Source amplitude [default: 5]:
```

---

### Step 3 – Optional Fault Injection

```
Inject fault? (y/N)
```

This allows generation of faulty circuits for ML datasets.

---

### Step 4 – Generated Files

```
rc_lowpass.cir
rc_lowpass.asc
```

---

### Step 5 – Open Automatically in LTspice

```
Open in LTspice now? (y/N)
```

---

## Example Output (RC Low Pass Filter Netlist)

```
V1 Vin 0 SINE(0 5 1k)
R1 Vin Vout 1k
C1 Vout 0 1u
.tran 1us 10ms
```

---

## Skills Demonstrated

* Analog Circuit Design
* LTspice Simulation Automation
* Python Programming
* Fault Injection Techniques
* Dataset Generation for ML
* ECE/VLSI Workflow Understanding

---

If you are working on **circuit simulation automation, ML-based fault detection, or EDA tools**, I would love to connect and discuss ideas.

#ECE #VLSI #Python #LTspice #MachineLearning #Electronics #Automation #EngineeringProjects

