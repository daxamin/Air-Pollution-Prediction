# Air Pollution Prediction: Time-series clustering & ARIMA

### Link to Data
https://drive.google.com/drive/folders/1SnDNT0aDZ_vn4ily36M24nbel2Y-U1-8?usp=sharing

### How to run | Clone the whole repository

1. The code files are ipnb (IPython notebook) verion--Python3
2. You can open the project in any IDE that supports .ipnb Eg. Jupyter/Anaconda [Download here](https://www.anaconda.com/download/). You may need to download some libraries that are used in the programs. If you are using Jupyter/Anaconda, you can install the libraries - *conda install library_name*
3. The main programs for Month-wise clustering & state-wise clustering can be found in *'main'* folder.
4. Download the data from [here.](https://drive.google.com/drive/folders/1SnDNT0aDZ_vn4ily36M24nbel2Y-U1-8?usp=sharing)
5. Change the data folder location path as per your system. The change has to be made in 1st or 2nd cell of [MonthWiseClustering.ipynb](https://github.com/daxamin/Air-Pollution-Prediction/blob/master/main/MonthWiseClustering.ipynb) and [StateWiseClustering.ipynb](https://github.com/daxamin/Air-Pollution-Prediction/blob/master/main/StateWiseClustering.ipynb)
6. Point 5 applies to other files also, where data folder is being accessed.

### Repository Structure Description | Folder Name - Description

1. **Evaluation** - Includes programs developed for evaluation of different algorithms using libraries, mainly *scikit-learn.*
LSTM code for evaluating the behavior of our data is taken from https://machinelearningmastery.com.
2. **Reports** - Contains the intermediate reports, poster and final report.
3. **Main** - Contains four files.
    1. **CreateTimeSeries** - Pre-process the data and create time-series data ready to be fed into custering algorithms
    2. **Euclidean vs DTW** - Evaluating Euclidean distance and Dynamic Time Warping for two time-series'.
    3. **MonthWiseClustering** - Implementing K-Means with DTW on month-wise time-series data.
    4. **StateWiseClustering** - Implementing K-Means with DTW on state-wise time-series data.
4. **Preprocessing** - Pre-processing raw data 
5. **state Data** - Data produced by pre-processing, contains state-wise csv files.


![poster](https://user-images.githubusercontent.com/15925203/39090661-42c4fdfe-45b3-11e8-8683-743f3773a30a.png)
