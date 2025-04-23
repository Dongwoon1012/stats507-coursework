# Environmental System Analysis with Temporal Fusion Transformer (TFT)
This repository contains the final project for Environmental System Analysis using deep learning-based time series prediction (TFT model).

---

## 📁 Project Structure

```
Final_project/
├── Code/
│   ├── ESA_TFT_SI_Jeju.ipynb         # TFT model for Jeju station
│   ├── ESA_TFT_SI_West.ipynb         # TFT model for West station
│   ├── ESA_TFT_SI_East.ipynb         # TFT model for East station
│   └── ESA_TFT_SI_Inland.ipynb       # TFT model for Inland station
├── Data/
│   ├── Jeju_Train.xlsx               # Jeju station training dataset
│   ├── Jeju_Test.xlsx                # Jeju station test dataset
│   ├── West_Train.xlsx               # West station training dataset
│   ├── West_Test.xlsx                # West station test dataset
│   ├── East_Train.xlsx               # East station training dataset
│   ├── East_Test.xlsx                # East station test dataset
│   ├── Inland_Train.xlsx             # Inland station training dataset
│   └── Inland_Test.xlsx              # Inlang station test dataset
├── requirements.txt                  # Project dependencies
└── README.md                         # This file
```

---

## ⚙️ Setup Instructions

Follow the steps below to clone the repository, set up the environment, install dependencies, and run the notebooks.

### 1. Clone the Repository

```bash
git clone https://github.com/Dongwoon1012/stats507-coursework.git
cd stats507-coursework/Final_project
```
> 💡 **Note:** If you see an error like `'git' is not recognized as an internal or external command`,  
> Git may not be installed. You can fix this by running the following in Anaconda Prompt:

```bash
conda install git -y
```
> Or download Git for Windows from: https://git-scm.com/download/win


### 2. Create and Activate Conda Environment

```bash
conda create -n tft_env python=3.9 -y
conda activate tft_env
```

### 3. Install Required Packages

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Run the Code for Each Station
After launching the Jupyter Notebook, open and run the following notebooks located in the Code/ directory:

- 'ESA_TFT_SI_Jeju.ipynb' – Jeju station model
- 'ESA_TFT_SI_West.ipynb' – West station model
- 'ESA_TFT_SI_East.ipynb' – East station model
- 'ESA_TFT_SI_Inland.ipynb' – Inland station model

Make sure to run each notebook from start to finish to train the TFT model and generate results for each station.
