# uci-wifi-dataset
Wi-Fi signals dataset (original and modified) by UCI ML Repository
The original dataset can be downloaded from: https://archive.ics.uci.edu/ml/datasets/Hybrid+Indoor+Positioning+Dataset+from+WiFi+RSSI%2C+Bluetooth+and+magnetometer#

## Original vs. modified
Original dataset file: dataset.csv

Modified dataset file: dataframe.csv

In modified dataset certain columns have been removed: 'meastimestamp','meas_x','meas_y','meas_z','gpslatitude','gpslongitude','gpsaltitude'

Bluetooth measurements have been removed as well.

AP names have been replaced with generic (ap1, ap2, ap3, ...) names.
## Features dataset
features.csv is a dataset that will be used for machine learning.
We created generic fetures from original dataset.
