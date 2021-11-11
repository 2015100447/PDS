# PDS
Datasets del curos de PDS para no estar subiendo el dataset cada vez que se utilice colab.
import pandas as pd
url = 'https://raw.githubusercontent.com/pydata/pydata-book/master/ch09/stock_px.csv'
df = pd.read_csv(url,index_col=0,parse_dates=[0])
