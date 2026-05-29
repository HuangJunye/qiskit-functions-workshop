# Qiskit Functions Workshop

## Qiskit Functions Overview

| Function Category | Vendor Name | Function Name | Guide | Tutorial |
|---|---|---|---|---|
| Circuit Function | Algorithmiq | TEM | [algorithmiq-tem.ipynb](guides/algorithmiq-tem.ipynb) | [simulate-kicked-ising-tem.ipynb](tutorials/simulate-kicked-ising-tem.ipynb) |
| Circuit Function | Qedma | QESEM | [qedma-qesem.ipynb](guides/qedma-qesem.ipynb) | [qedma-2d-ising-with-qesem.ipynb](tutorials/qedma-2d-ising-with-qesem.ipynb) |
| Circuit Function | Q-CTRL | Performance Management | [q-ctrl-performance-management.ipynb](guides/q-ctrl-performance-management.ipynb) | [quantum-phase-estimation-qctrl.ipynb](tutorials/quantum-phase-estimation-qctrl.ipynb), [transverse-field-ising-model.ipynb](tutorials/transverse-field-ising-model.ipynb) |
| Application Function | ColibriTD | QUICK-PDE | [colibritd-pde.ipynb](guides/colibritd-pde.ipynb) | [colibritd-pde.ipynb](tutorials/colibritd-pde.ipynb) |
| Application Function | Global Data Quantum | Quantum Portfolio Optimizer | [global-data-quantum-optimizer.ipynb](guides/global-data-quantum-optimizer.ipynb) | [global-data-quantum-optimizer.ipynb](tutorials/global-data-quantum-optimizer.ipynb) |
| Application Function | Kipu Quantum | Iskay Quantum Optimizer | [kipu-optimization.ipynb](guides/kipu-optimization.ipynb) | [solve-market-split-problem-with-iskay-quantum-optimizer.ipynb](tutorials/solve-market-split-problem-with-iskay-quantum-optimizer.ipynb) |
| Application Function | Multiverse Computing | Singularity Machine Learning | [multiverse-computing-singularity.ipynb](guides/multiverse-computing-singularity.ipynb) | [sml-classification.ipynb](tutorials/sml-classification.ipynb) |
| Application Function | Q-CTRL | Optimization Solver | [q-ctrl-optimization-solver.ipynb](guides/q-ctrl-optimization-solver.ipynb) | [solve-higher-order-binary-optimization-problems-with-q-ctrls-optimization-solver.ipynb](tutorials/solve-higher-order-binary-optimization-problems-with-q-ctrls-optimization-solver.ipynb) |
| Application Function | Qunova | HI-VQE Chemistry | [qunova-chemistry.ipynb](guides/qunova-chemistry.ipynb) | [qunova-hivqe.ipynb](tutorials/qunova-hivqe.ipynb) |

> **Note:** These guide and tutorial files are sourced from the official [Qiskit documentation repository](https://github.com/Qiskit/documentation).

## Setup

### Prerequisites

- Python 3.10 or later
- pip package manager
- **IBM Quantum Account:** An IBM Quantum Platform account (Flex or Premium plan) or TechZone account for workshop access
- **Qiskit Functions Access:** Request access from your instructor (Junye) or administrator 

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/HuangJunye/qiskit-functions-workshop.git
   cd qiskit-functions-workshop
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Add virtual environment to Jupyter:**
   ```bash
   pip install ipykernel
   python -m ipykernel install --user --name qiskit-functions-workshop --display-name "Python (Qiskit Functions Workshop)"
   ```

### Running the Notebooks

#### Option 1: JupyterLab (Recommended)

1. **Install JupyterLab:**
   ```bash
   pip install jupyterlab
   ```

2. **Launch JupyterLab:**
   ```bash
   jupyter lab
   ```

3. **Select the kernel:** When you open a notebook, select the "Python (Qiskit Functions Workshop)" kernel from the kernel selector in the top-right corner.

4. **Navigate** to the `guides/` or `tutorials/` folder and open any `.ipynb` file.

#### Option 2: Visual Studio Code

1. **Install VS Code extensions:**
   - [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
   - [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)

2. **Open the repository in VS Code:**
   ```bash
   code .
   ```

3. **Select the kernel:** Open any `.ipynb` file and click the kernel selector in the top-right corner. Choose "Python (Qiskit Workshop)".

4. **Run cells:** Execute cells individually or use "Run All" to execute the entire notebook.

#### Option 3: Classic Jupyter Notebook

1. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

2. **Select the kernel:** When you open a notebook, select the "Python (Qiskit Functions Workshop)" kernel from the "Kernel" menu.

3. **Navigate** to the `guides/` or `tutorials/` folder and open any `.ipynb` file.

