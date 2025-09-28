# Secret Key Generation from Wireless Channel State Information (CSI)

This repository demonstrates how **Channel State Information (CSI)** can be 
used in wireless security applications. The notebook provides a hands-on 
tutorial covering channel reciprocity analysis, filtering, and secret key 
generation techniques.  

## Features
- **Reciprocity Analysis**: Evaluate correlation between access point (AP) 
  and station (STA) CSI data across time lags.
- **Noise Reduction**: Apply Savitzky-Golay filtering to smooth CSI data and 
  enhance reciprocity.
- **Key Generation**: Use 4-level quantization to generate cryptographic keys 
  from CSI data.
- **Evaluation**: Check key agreement with a 10% error threshold and compute 
  the Key Generation Rate (KGR).
- **Visualization**: Plots for correlation vs. lag and key similarity distribution.

## Repository Structure
- `csi_key_generation.ipynb` : Main Jupyter Notebook.  
- `requirements.txt` : List of Python dependencies.
  
## Installation
Clone the repository and install the required dependencies:

```bash
git clone https://github.com/xMohammadAsimx/csi-key-generation.git
cd csi-key-generation
pip install -r requirements.txt
```

## Disclaimer
The `.csv` files used in this project cannot be provided due to licensing and course material restrictions.  

To run the notebook, please:  
- Provide your own CSI dataset (e.g., `ap.csv`, `sta.csv`), or  
- Adapt the code to generate synthetic/sample data.  

This repository is intended as a **tutorial and research guide** only.
