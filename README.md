Can other people see my code??
test test test
Pull Request + Comment???
# PHYS 434 A Au 25: Advanced Laboratory: Computational Data Analysis

**Lab Sections (B143)**  
Tuesday (AA) 1:30-4:20  
**Instructor:** Linda Zhenyu Jin (<lindajin@uw.edu>)

## Course Overview

This repository contains laboratory notebook templates and datasets for Physics 434.

## Getting Started

### Option 1: Local Setup (VS Code)

1. **Clone this repository:**
   ```bash
   git clone https://github.com/Klinjin/Au25_Phys434_Data_Analysis_Lab.git
   cd Au25_Phys434_Data_Analysis_Lab
   ```

2. **Set up conda environment:**
   
   First, install Conda: https://conda.io/projects/conda/en/latest/user-guide/install/index.html

   ```bash
   conda create --name phys434 python=3.12.8
   conda activate phys434
   pip install -r requirements.txt
   ```
   
   *Optional: To deactivate and remove the environment later:*
   ```bash
   conda deactivate
   conda env remove --name phys434
   ```

3. **Open in VS Code:**
   - Install the Python and Jupyter extensions in VS Code
   - Open the repository folder in VS Code
   - Click on any `.ipynb` file to start working with notebooks

### Option 2: Local Setup (Browser Terminal)

1. **Clone and navigate to repository:**
   ```bash
   git clone https://github.com/Klinjin/Au25_Phys434_Data_Analysis_Lab.git
   cd Au25_Phys434_Data_Analysis_Lab
   ```

2. **Install dependencies and start Jupyter:**
   ```bash
   pip install pandas matplotlib numpy scipy jupyter
   jupyter notebook
   ```

3. **Access notebooks:**
   - Your browser will open automatically
   - Navigate to the notebook files (`.ipynb`) to start working

### Option 3: Google Colab

1. **Open in Colab:**
   
   **Lab 1**  
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Klinjin/Au25_Phys434_Data_Analysis_Lab/blob/main/lab_1_template.ipynb)

2. **Mount Google Drive (run this in the first cell):**
   
   **Important:** Google Colab's memory is ephemeral - your work will be lost when the session ends. Either download your file in the end or mount your Google Drive to save your edits and outputs permanently.
   
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   %cd /content/drive/MyDrive/
   ```

---

*Last updated: September 2025*
