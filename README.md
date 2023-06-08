This repository contains code related to the development of the paper "Pro-Social Preferences Improve Climate Risk Management in Subsistence Farming Communities", currently under review. There are four main files:

1) RiskTransferSimulations.ipynb: This contains the code to run the main evolutionary game theory (EGT) model that is described in the paper. Users can run the model in Python 3 (an open-source software) by sequentially executing the blocks of code in this file. This file contains two versions of the model - the Expected Values and Financial Restrictions Models. Expected Values simulate farmer strategy decisions in the absence of any financial restrictions, whereas Financial Restrictions account for farmers' savings and ability to afford strategies. Results from either model can be saved by un-commenting the np.save command at the end of the cell block. Note that users may need to install specific packages that are imported in the first block of code; this can be doing using pip install as described[here] (https://pip.pypa.io/en/stable/cli/pip_install/).

2) CVFS_Data_Analysis_FarmIncomes.ipynb: This file contains code to analyze the Chitwan Valley Family Survey data that was used to parmaeterize income distributions and farm income correlation for the EGT model. It calls the CVFS_Data_001.tsv file, also saved in this repository.

3) Ethiopia_Data_Analysis.ipynb: This file contains code to analyze data from the Borena Index-Based Livestock Insurance survey, which is used in the paper to parameterize income correlation parameters.

4) Drought_Analysis.ipynb: This analyzes data from the Standardized Evapotranspiration Index database, which is used to parameterize the probability of extreme events in the scenarios described in the paper.


