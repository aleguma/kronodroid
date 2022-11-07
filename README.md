# About the Kronodroid Dataset

Android malware dataset designed to study and explore concept drift and cross-device detection issues. Created and maintained by Dr. Alejandro Guerra Manzanares during his Ph.D. studies. 

Features:

- Labeled (i.e., benign/malware samples)
- 289 dynamic features (i.e., system calls)
- 200 static features (i.e., permissions, intent filters, metadata)
- 4 distinct timestamps per data sample
- Covering most years of Android history - 2008-2020


Emulator data set is ready to download in CSV format (zip files under emulator folder). 
  - 28,745 malicious samples (209 malware families).
  - 35,256 benign samples.

Real Device data set is ready to download in CSV format (zip files under real device folder).  
  - 41,382 malware samples (240 malware families)
  - 36,755 benign apps.

Log files and raw data to be uploaded soon. 

The APK files cannot be shared due to restrictions from the original sources. However, the list hashes of all the data set samples can be extracted from each specific data set (i.e., "sha256" column in each CSV file). Then, the selected files can be gathered using the hash values from the original sources.

If you have any issues or requests that I can be of any help with, please email alejandro.guerra@taltech.ee 

## Important Information

The data set is released publicly and with no other restriction than when using the dataset please cite the KronoDroid paper:
https://www.sciencedirect.com/science/article/pii/S0167404821002236

LaTeX citation to the data set paper:

>@article{Kronodroid_Guerra, <br/>
title = {KronoDroid: Time-based Hybrid-featured Dataset for Effective Android Malware Detection and Characterization}, <br/>
journal = {Computers & Security}, <br/>
volume = {110}, <br/>
pages = {102399}, <br/>
year = {2021}, <br/>
issn = {0167-4048}, <br/>
doi = {https://doi.org/10.1016/j.cose.2021.102399}, <br/>
url = {https://www.sciencedirect.com/science/article/pii/S0167404821002236}, <br/>
author = {Alejandro Guerra-Manzanares and Hayretdin Bahsi and Sven Nõmm}} <br/>

More information and detailed explanation about the dataset and the additional scripts will be posted soon.

Contact: alejandro.guerra@taltech.ee

## Have you used the data set in your work?

If you have used KronoDroid in your work, send us the reference and we will include it in the [PUBLICATIONS LIST](https://github.com/aleguma/kronodroid/blob/b84216a4f3b68487ed8c11acb029024dda6164ad/publist.md).

## Updates

I am working on improving the data set, adding more recent files, more data and API calls information. If you are interested, contact me.
