# MULTIPLEX-Droplet-Platform

**MULTIPLEX-Droplet-Platform** is a four-channel, fully automated microdroplet screening system designed for photocatalytic reaction optimization.  
The platform integrates parallel reaction channels, programmable control via LabVIEW, and LED-based photochemical activation, enabling efficient and precise screening of chemical reactions under microliter-scale conditions.

---

## 🌟 Key Features

- **Four-channel parallel droplet reaction system**
- **Fully automated reagent control and flow switching**
- **Integrated LED array for photocatalysis**
- **User-friendly LabVIEW interface for real-time monitoring and control**

---

## 🛠 Installation Requirements

To run this system, please ensure the following environment is properly configured:

- **NI LabVIEW 2023 Q1 (64-bit)** or newer  
  Download: [NI official site](https://www.ni.com/)  
- **NI Modbus Library**  
  Install via **VIPM** (VI Package Manager):  
  [ni_lib_modbus_library](https://www.vipm.io/package/ni_lib_modbus_library/)

---

## 🚀 Getting Started

1. **Open the LabVIEW project file**:  
   `MULTIPLEX-project.lvproj`

2. **Edit your sample information**:  
   Fill in the details in `sample test.txt` (e.g., sample ID, volume, conditions).

3. **Launch the main interface**:  
   Run `4 channel - main interface.vi` inside the LabVIEW project.  
   This interface allows you to control all four channels simultaneously, monitor system status, and execute your droplet screening workflow.

---


