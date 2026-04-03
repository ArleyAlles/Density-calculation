# Density Calculation using Equations of State (EoS)

This repository provides a Python-based tool for calculating the density of fluid mixtures using various Equations of State. Ideal for thermodynamics and reservoir engineering simulations. Further explanation about the code can be found inside the **.ipynb** file

## Quick Start Guide

Follow these steps to set up the environment and run the notebook:

### 1. Prerequisites
Ensure you have **Git** and **Python (3.8+)** installed:
* [Download Git](https://git-scm.com/install/)
* [Download Python](https://www.python.org/downloads/)


### 2. Clone the repository:
```bash
git clone https://github.com/ArleyAlles/Density-calculation.git
```


### 3. Virtual Environment Setup
Create and activate a virtual environment to keep dependencies isolated:
* **Linux/macOS**:

    ```
    python3 -m venv .venv
    ```
    ```
    source .venv/bin/activate
    ``` 
* **Windows**:
    ```
    python -m venv .venv
    ```
    ```
    .venv\Scripts\activate
    ```

### 4. Install Dependencies:
```bash
pip install -r requirements.txt
```

### 5. Configure Jupyter kernel:
```bash
python -m ipykernel install --user --name=density_eos --display-name "Python (Density EoS)"
```

### 6. Run the Notebook:
* Using Jupyter notebook:
```bash
jupyter notebook
```
* Using Jupyter lab:
```bash
jupyter lab
```

### 7. Select the Kernel

Once the notebook is open, go to **Kernel > Change Kernel** and select **"Python (Density EoS)"**.

---

**Note:** If you have already completed the setup, you only need to:

1. Enter the repository folder;

2. Activate the environment;

3. Run step 6.