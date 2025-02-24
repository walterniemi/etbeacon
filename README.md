# 🛰️ The E.T. Beacon: A Gravitational-Wave Technosignature – Jupyter Code & Data

This repository provides the **full Jupyter Notebook-based analysis pipeline** for:

> **"The E.T. Beacon: A Gravitational-Wave Technosignature"**  
> *Submitted to Nature Astronomy (Manuscript ID: NATASTRON-25020154)*  

## 🚀 **How to Run This in Jupyter**

### **Step 1: Clone the Repository**
Open a terminal (or use Jupyter's built-in terminal) and run the pipeline:

Step 2: Set Up Your Environment
Make sure you have Jupyter Notebook and the required dependencies installed.
If you haven't installed Jupyter yet, run:

Then, install the necessary Python libraries:

Step 3: Launch Jupyter Notebook
Start Jupyter Notebook in the repo directory:

Step 4: Run the Notebooks in Order
🔹 Primary Analysis Notebooks:
notebooks/1-load_data.ipynb – Load LIGO HDF5 strain data
notebooks/2-bandpass_filter.ipynb – Apply frequency filtering (1285-1295 Hz)
notebooks/3-fft_analysis.ipynb – Compute FFT & identify structured peaks
notebooks/4-wavelet_analysis.ipynb – Perform Morlet wavelet transform
notebooks/5-prime_lattice_analysis.ipynb – Identify prime-structured frequency gaps
notebooks/6-compare_across_LIGO_runs.ipynb – Multi-run consistency check
notebooks/7-visualize_pi_wraparound.ipynb – The π/2 & 3π/2 wavelet phase evolution

```sh
git clone https://github.com/yourusername/ET-Beacon-Code.git
cd ET-Beacon-Code

pip install jupyterlab

pip install numpy scipy matplotlib h5py sympy

jupyter notebook

