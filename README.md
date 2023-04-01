# Clustering Stocks 

This project is a demonstration of how to cluster stocks values using a Self-Organizing Map (SOM) algorithm, a K-Means algorithm. Moreover, we will see how to solve the lack of dimensionality problem by using Principal Component Analysis (PCA) and Neural Network Encoder.

To do this, we will use real stock prices from the S&P 600 companies over the last 5 years.

We will also see if there is a correlation between the clusters and the sectors of the companies.

The project is inspired by __**[this Kaggle notebook](https://www.kaggle.com/code/izzettunc/introduction-to-time-series-clustering)**__, which provides an introduction to time series clustering with a SOM algorithm. We've adapted the notebook to work with historical stock prices and added additional preprocessing and cleaning steps to ensure accurate clustering.

## Requirements

To run the notebook, you'll need to install the following Python packages:

- [yfinance](https://pypi.org/project/yfinance/)
- [pandas](https://pandas.pydata.org/)
- [requests](https://requests.readthedocs.io/en/master/)
- [bs4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [matplotlib](https://matplotlib.org/)
- [scikit-learn](https://scikit-learn.org/stable/)
- [minisom](https://pypi.org/project/MiniSom/)
- [numpy](https://numpy.org/)
- [torch](https://pytorch.org/)
- [tslearn](https://tslearn.readthedocs.io/en/stable/index.html)


You can install these packages using pip by running the following command in your terminal (using requirements.txt):

```bash
pip install -r requirements.txt
```

## Getting Started

To get started with the project, first clone the repository to your local machine:

```bash
git clone https://github.com/MaximeSzymanski/StocksClustering.git
```


Then, open the notebook in Jupyter Notebook:

```bash
jupyter notebook 
```

This should open a browser window displaying the project files. Click on **clustering_stocks.ipynb** to launch the notebook.




