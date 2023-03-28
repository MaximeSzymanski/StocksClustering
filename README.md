# Clustering Stocks with a Self-Organizing Map (SOM)

This project demonstrates how to cluster stocks based on their daily price variation using a Self-Organizing Map (SOM) algorithm. The SOM is a type of artificial neural network that can learn the underlying structure of high-dimensional data and group similar data points together.

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



