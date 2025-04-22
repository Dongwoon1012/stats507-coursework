# Environmental System Analysis with Temporal Fusion Transformer (TFT)
This repository contains the final project for Environmental System Analysis using deep learning-based time series prediction (TFT model).

---

## 📁 Project Structure

```
Final_project/
├── Code/
│   ├── ESA_TFT_SI_Jeju.ipynb         # TFT model training for Jeju station
│   ├── ESA_TFT_SI_West.ipynb         # TFT model training for West station
│   ├── ESA_TFT_SI_East.ipynb         # TFT model training for East station
│   └── ESA_TFT_SI_Inland.ipynb       # TFT model training for Inland station
├── Data/
│   ├── Jeju_Train.xlsx               # Jeju station training dataset
│   ├── Jeju_Test.xlsx                # Jeju station test dataset
│   ├── West_Train.xlsx
│   ├── West_Test.xlsx
│   ├── East_Train.xlsx
│   ├── East_Test.xlsx
│   ├── Inland_Train.xlsx
│   └── Inland_Test.xlsx
├── requirements.txt                 # Project dependencies
└── README.md                        # This file
```

---

## ⚙️ Setup Instructions

Follow the steps below to clone the repository, set up the environment, install dependencies, and run the notebooks.

### 1. Clone the Repository

```bash
git clone https://github.com/Dongwoon1012/stats507-coursework.git
cd stats507-coursework/Final_project

conda create -n tft_env python=3.9 -y
conda activate tft_env

pip install -r requirements.txt

jupyter notebook
