# Mitigation of Algorithmic Bias and Ensuring Fairness

This repository contains a project that develops an AI model to detect and mitigate algorithmic bias in datasets, ensuring fairer outcomes across diverse demographics. The project demonstrates bias measurement using the Disparate Impact Ratio (DIR) and bias mitigation using a re-weighting (resampling) technique on the UCI Adult dataset.

## Project Structure



    ````bash
    BiasMitigationProject/ 
    ├── LICENSE # License file (MIT License) 
    ├── .gitignore # Files and directories to be ignored by Git 
    ├── README.md # This file 
    ├── requirements.txt # Python dependencies 
    ├── notebooks/ # Jupyter Notebook with code and explanations 
        │ └── Bias_Mitigation.ipynb 
    └── paper/ # LaTeX source for the research paper 
        └── paper.tex


## Setup Instructions

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Ibnbuba-A360/BiasMitigationProject.git
   cd BiasMitigationProject
   
2. **Create Anaconda Virtual Environment**
    ```bash
    conda create -n bias_mitigation_env python=3.8
    conda activate bias_mitigation_env
   
3. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
   
4. **Run The Jupyter Notebook**
    ```bash
    jupyter notebook notebooks/Bias_mitigation.ipynb




