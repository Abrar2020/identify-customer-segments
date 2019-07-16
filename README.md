# Machine Learning Nanodegree
# Unsupervised Learning
## Project: Identify Customer Segments

### Install

This project requires **Python 3.x** and the following Python libraries installed:

- [scikit-learn](https://scikit-learn.org/)
- [NumPy](https://www.numpy.org/)
- [matplotlib](http://matplotlib.org/)
- [pandas](https://pandas.pydata.org/)
- [seaborn](https://seaborn.pydata.org/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)


### Code

The notebook file `identify_customer_segments.ipynb` contains all the code utilized for data cleaning and processing, dimensionality reduction, and clustering.  In addition, detailed descriptions of the cluster analysis process and findings are described in the markdown cells in the notebook.  This is the only file needed by the user. 

### Run

In a terminal or command window, navigate to the top-level project directory `identify-customer-segments/` (that contains this README) and run one of the following commands:

```bash
ipython notebook identify_customer_segments.ipynb
```  
or
```bash
jupyter notebook identify_customer_segments.ipynb
```

This will open the iPython Notebook software and project file in your browser.

### Data

The data set consists of three files: `Udacity_AZDIAS_Subset.csv`, `Udacity_CUSTOMERS_Subset.csv`, and `AZDIAS_Feature_Summary.csv`.  The first two contain the main data for the general and customer populations respectively while the third file provides information about the type of information (categorical, quantitative, etc) each feature contains as well as the missing value codes.  There are 85 features in total with 891,221 observations in the `Udacity_AZDIAS_Subset.csv` file and 191,652 observations in the `Udacity_CUSTOMERS_Subset.csv` file.   Due to the terms and conditions in which the data is distributed through Udacity, the data set is not provided in this repository. 

## License

MIT &copy; Ryan Schumm