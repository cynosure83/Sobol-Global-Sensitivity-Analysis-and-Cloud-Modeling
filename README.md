# Sobol-Global-Sensitivity-Analysis-and-Cloud-Modeling
1. Code Purpose
This code repository implements the three-tier "Modeling-Resolution-Assessment" framework proposed in the paper:
Generate orthogonal experimental samples for slope stability analysis
Construct a regularized XGBoost surrogate model for slope numerical simulation
Perform Sobol global sensitivity analysis (quantify single/interactive factor contributions)
Calculate cloud model digital features (Ex, En, He) to assess sensitivity index uncertainty
Reproduce all results of the Fujian post-failure red clay slope case study
2. Environment Requirements
Python 3.8+
bash
pip install xgboost salib numpy pandas matplotlib scipy
3. File Description
quick_test.py: Quick-test script for core framework validation
code/: Core algorithm implementation
data/samples.csv: samples used in the paper
data/test_data.csv: Small sample for quick test
results/: Output of sensitivity indices & cloud model parameters
4. Quick-Test Instructions
Step 1: Clone or download this repository
Step 2: Run the quick-test script directly
Step 3: Expected output
5. Full Case Reproduction
Run the example script for the Fujian slope case.
6. Citation
If you use this code, please cite the corresponding paper.
7. Contact
Author email: 42134489@qq.com
