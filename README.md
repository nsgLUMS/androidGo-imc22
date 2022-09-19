# Causal Impact of Android Go on Mobile Web Performance

In this repository, we release the dataset and code for carrying out the analysis and generating figures used in the ACM Internet Measurement Conference (IMC) 2022 paper, "Causal Impact of Android Go on Mobile Web Performance"

This repository contains the following files:

1. "imc22_dataset.csv": contains the dataset of 600 page loads
	- 300 page loads are under Android Go (100 each for No MP, Low MP, and High MP)
	- 300 page loads are under Android non-Go (100 each for No MP, Low MP, and High MP)

2. "camera-ready-data-analysis-android-go-paper.ipynb": this jupyter notebook contains code for analysis and generating figures in the paper

3. "android_devices.xlsx": contains results for page loads across two Android devices

4. "android_versions.xlsx": contains results for page loads across two Android versions

5. "public_imc22_replicationCode.rmd": R code for generating results involving the Heckman Selection model
	- it uses the csv file "df_orig_w_crashed_column_empty.csv" as input
