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

The flower image dataset consists of 8,256 images. Each image is resized and cropped to dimensions of 224x224 which equates to 50,176 features with 102 different classes of flower. The class label for an image is equal to the lowest directory name in which the image is stored. The cat_to_name.json file contains a map that translates a class label to a flower name. 

## License

MIT &copy; Ryan Schumm