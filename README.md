# PCA Analysis for Handwritten Digits Differentiation

This notebook analyzes a dataset of handwritten digits to determine which digits are most differentiated using Principal Component Analysis (PCA). The primary goal of the notebook is to graphically represent the principal components, evaluating PCA for both 2 and 3 dimensions.

## Dataset Description

The dataset consists of handwritten digit samples collected from 44 different writers. A total of 250 samples were collected from each writer, with 30 writers' samples used for training, cross-validation, and writer-dependent testing. The remaining 14 writers' samples were used for writer-independent testing. The data was collected using a WACOM PL-100V pressure-sensitive tablet with a wireless stylus. The tablet sends 𝑥 and 𝑦 tablet coordinates and pressure level values of the pen at fixed time intervals of 100 milliseconds.

Participants were asked to write 250 digits in random order inside boxes of 500x500 pixel resolution on the tablet. The first ten digits were ignored as most writers were not familiar with this type of input device. Participants were monitored only during the initial screens. Each screen contained five boxes with the digits to be written displayed above. Participants were instructed to write only inside these boxes.

Source of data: [Dataset Link]()

## Objective

The objective of this notebook is to use Principal Component Analysis (PCA) to determine which handwritten digits are most differentiated. This is achieved by evaluating the principal components of the dataset and graphically representing them. Specifically, the notebook performs PCA for dimensions of 2 and 3 and visualizes the results using three-dimensional plots.

## Used Libraries
The notebook utilizes several Python libraries for data analysis and visualization. The main libraries used are:

* numpy: Used for mathematical operations on arrays.
* pandas: Used for tabular data manipulation.
* matplotlib.pyplot and seaborn: Used for creating plots.
* sklearn.preprocessing.StandardScaler: Used for data standardization before PCA.
* sklearn.decomposition.PCA: Used for performing Principal Component Analysis.
* mpl_toolkits.mplot3d and mpl_toolkits.mplot3d.Axes3D: Used for creating three-dimensional plots.

## Usage

To run the notebook and view the PCA analysis results, simply execute each cell of the notebook sequentially. The results will be displayed as both two-dimensional and three-dimensional plots.

## Contributions

If you wish to contribute to this notebook by adding new analyses or improvements, you are encouraged to do so. You can fork the repository and submit a pull request with your modifications.
