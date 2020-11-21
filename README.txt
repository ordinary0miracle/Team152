1. DESCRIPTION - Describe the package in a few paragraphs
	pandas - pandas is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool, built on top of the Python programming language.
	sklearn - Scikit-learn is a machine learning library for the Python programming language.It features various classification, regression and clustering algorithms including support vector machines, random forests, gradient boosting, k-means and DBSCAN, and is designed to interoperate with the Python numerical and scientific libraries NumPy and SciPy.
	numpy - NumPy is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays. 
	statistics - This module provides functions for calculating mathematical statistics of numeric (Real-valued) data.
	matplotlib - Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python.
	seaborn - Seaborn is a Python data visualization library based on matplotlib.
	torch - PyTorch is a Python package that provides two high-level features: Tensor computation (like NumPy) with strong GPU acceleration. Deep neural networks built on a tape-based autograd system.
	warnings - Warning messages are typically issued in situations where it is useful to alert the user of some condition in a program, where that condition (normally) doesn’t warrant raising an exception and terminating the program.
	pmdarima - Pmdarima (originally pyramid-arima, for the anagram of 'py' + 'arima') is a statistical library designed to fill the void in Python's time series analysis capabilities.


2. INSTALLATION - How to install and setup your code
   The zip file contains state_full_abbr.csv and us-states.csv we used in the project.
   There's another dataset with large size (weekly_housing_market_data_most_recent.tsv), we uploaded it to Google drive, it can be access from: https://drive.google.com/file/d/1p984YVIDL1lErup3fFUZ4lACHAbG7oUe/view
   First install Anaconda https://www.anaconda.com/products/individual
   Then use Conda terminal to create new enviroment using commands:
   conda env create --file environment.yml 
   Manually install pmdarima by 'pip3 install pmdarima'

3. EXECUTION
   Execute the ipynb files in the following order (you have to complete the execution before you move to next file): 
	House Data - Data Processing.ipynb
	team152.ipynb
	SARIMA.ipynb
	LSTM.ipynb
	final_result_lstm_sarima.ipynb
	clustering.ipynb

	note: state_full_abbr.csv, us-states.csv and weekly_housing_market_data_most_recent.tsv should be in the same folder

The files are also available on Github
https://github.com/ordinary0miracle/Team152
