# Quantum Computing Learning with IBM Quantum & Qiskit

This repository documents my learning journey in **quantum computing** using **IBM Quantum** and the **Qiskit SDK**.  
It contains notes, Jupyter notebooks, and hands-on implementations of quantum computing concepts.

The purpose of this repository is:
- To organize my quantum computing learning
- To keep reproducible Qiskit experiments
- To help others set up a local Qiskit environment and learn along

---

## 🧩 Technologies Used
- Python
- Qiskit SDK
- Qiskit IBM Runtime
- Jupyter Notebook
- IBM Quantum Platform

---

## ⚙️ Local Environment Setup

### 1️⃣ Install Python
Check the supported Python versions on the Qiskit PyPI page.

Download Python from:
https://www.python.org/downloads/

> ⚠️ Qiskit supports **64-bit CPython only**

---

### 2️⃣ Create a Virtual Environment
From your project directory:

```bash
python -m venv .venv
``` 

### 3️⃣ Activate the Virtual Environment

Windows (PowerShell):

```bash
.venv\Scripts\Activate.ps1
```

Windows (Command Prompt):

```bash
.venv\Scripts\activate
```

Linux / macOS:

```bash
source .venv/bin/activate
```

You should now see (.venv) in your terminal.

### 4️⃣ Upgrade pip (Recommended)
```bash
pip install --upgrade pip
```
### 5️⃣ Install Qiskit

Install the Qiskit SDK:
```basg
pip install qiskit
```

If you plan to run jobs on IBM Quantum hardware:
```bash
pip install qiskit-ibm-runtime
```

For visualization support (recommended for notebooks):
```bash
pip install "qiskit[visualization]"
```
### 6️⃣ Install Jupyter Notebook
```bash
pip install jupyter
```
### 7️⃣ Run Jupyter Notebook

From the project directory:
```bash
jupyter notebook
```

Or open a specific notebook:
```bash
jupyter notebook notebook_1.ipynb
```
### 🔍 Verify Qiskit Installation

Check the installed Qiskit version:
```bash
import qiskit
qiskit.__version__
```

Verify that the version is 1.0 or greater:
```bash
from packaging.version import Version
Version(qiskit.__version__) >= Version("1.0")
```
### 🧪 Notes on Qiskit Versions

- Qiskit is under active development

- APIs may change due to deprecations

- Code examples in this repository were executed with the installed Qiskit version

- For users upgrading from Qiskit 0.x → 1.x:

- In-place upgrades are not supported

- Refer to the official Qiskit migration guide

### ☁️ Running on IBM Quantum Hardware (Optional)

- To run circuits on real quantum hardware:

   + Create an IBM Cloud account

   + Enable IBM Quantum

   + Save your API token using qiskit-ibm-runtime

Official documentation:
https://docs.quantum.ibm.com/

### 📚 Learning Resources

- IBM Quantum Learning Platform

- Qiskit Documentation

- Qiskit Tutorials and Textbook

### 🙏 Credits & Acknowledgments

This repository is based on learning materials, documentation, and examples provided by:

IBM Quantum
https://www.ibm.com/quantum

https://docs.quantum.ibm.com/

All credit for Qiskit, IBM Quantum systems, and official learning resources belongs to IBM.
This repository is maintained for educational and personal learning purposes.


