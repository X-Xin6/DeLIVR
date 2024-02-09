# DeLIVR Estimator

The DeLIVR Estimator is a Python-based tool that leverages deep learning for instrumental variable regression. This project aims to the performance of DeLiVR and provide an easy-to-use interface for academic researchers.
## Installation
1. Navigate to Stage1_DeLiVR.ipynb and Stage2_DeLiVR.ipynb on GitHub.
2. Click on the Open in Colab button.
3. Download the data files from the data folder.
4. Upload these files to Google Drive for use in Colab notebooks.
![alt text](image/usage.png?raw=true "Title")

## Usage
### Step 1: Data Generation and Fit Stage1 model
- Open Stage1_DeLiVR.ipynb and execute all cells to simulate data, where "3" in filenames like s1_Z_3.csv denotes a cubic relationship.
- Save the generated data (s1_Z_3.csv, s2_Z_3.csv, etc.) to your Google Drive for analysis.
- ![alt text](image/usage2.png?raw=true "Title")
### Step 2: Stage2 Model Training and Evaluation
- Proceed with Stage2_DeLiVR.ipynb, using s2_X_hat_3.csv and Y_3.csv from Stage 1.
![alt text](image/usage3.png?raw=true "Title")
## Features
- Handles various types of relationships (linear, quadratic, cubic)
## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.
