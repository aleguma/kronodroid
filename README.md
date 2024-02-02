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

## Th raw data set is available (log files, extracted metadata and APKs)

Log files and raw data are available from my personal website: https://alegm.com. 
However, given the sensitive nature of the data (malware) the access is controlled and only granted to researchers and for research purposes. If you want access, please email me at alejandro.guerra@nyu.edu or mail@alegm.com to provide you personalized credentials for accessing the data files. 

Please remember to cite the original dataset paper when using any data related to KronoDroid (see below). Thank you so much!

If you have any issues or requests that I can be of any help with, email me.

## Important Information

The data set is released publicly for research purpose and with no other restriction than when using the dataset please cite the KronoDroid paper:
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

Note: I encourage to check the related papers I published using the dataset, they might be relevant for your work! Citation would also be greatly appreciated!

## Updates to the data set

I am working on improving the data set, adding more recent files, more data and API calls information. If you are interested, contact me!

I can share original log files of the system calls and other extracted information with the APK. I can also share part of the APK files if you need them. 

Do not hesitate to contact me if you need raw files of the dataset (large size): alejandro.guerra@nyu.edu
