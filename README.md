# DeLIVR Estimator

The DeLIVR Estimator is a Python-based tool that leverages deep learning for instrumental variable regression, designed to uncover complex causal relationships in data. This project aims to provide an easy-to-use interface for both academic researchers and data scientists.
## Installation
We go to the files Stage1_DeLiVR.ipynb and Stage2_DeLiVR.ipynb and click on the Open in Colab button. Then we store these two files in google colab.
![alt text](image/usage.png?raw=true "Title")
We download the data files under the data folder and upload them to the google drive.
## Usage
We opened the file Stage1_DeLiVR.ipynb first, and click runall under the Runtime button. The generate data method will simulated the data that will be tested in the DeLiVR estimator. We store these data into Google Drive. For example, for the Simulated Data with g(x) being cubic function, we save s1_Z, s2_Z, s1_X, s2_X, Y into the s1_Z_3.csv, s2_Z_3.csv, s1_X_3.csv, s2_X_3.csv, Y_3.csv files respectively. We used data s1_Z, s1_X, s2_Z to fit a linear model in stage 1 and obtained the files s2_X_hat_3.csv, which will be used in stage 2 estimation later.
![alt text](image/usage2.png?raw=true "Title")
We opened the file Stage1_DeLiVR.ipynb first, and click runall under the Runtime button. We will use s2_X_hat_3.csv and  Y_3.csv  that we obtained earlier to fit a deep learning model in stage 2.
![alt text](image/usage3.png?raw=true "Title")
## Features
Supports various types of relationships (linear, quadratic, cubic)
Implements deep learning for accurate estimation
User-friendly command-line interface

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your enhancements.
