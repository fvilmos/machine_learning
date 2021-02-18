# Cactus detection

This is the solution for the Cactus detection competition from [Kaggle](https://www.kaggle.com/)

To repoduce, please follow the steps:
1. install necessary packages
pip install tensorflow
pip install scipy
pip install glob2
pip install numpy
pip install PIL
pip instal matplotlib
pip install jupyter
pip install notebook

2. Download the database from: https://www.kaggle.com/c/aerial-cactus-identification/data
Extract content to "data" folder, see strcture below

3. Run the notebook. Will (re)generate the .h5 file - which holds the network weights and the .csv file - holding the predicted walus from the nework. 

```
├── cactus_detection.ipynb
├── data
├── k_cactus.h5
├── README.md
└── submission.csv

```
/Enjoy.
