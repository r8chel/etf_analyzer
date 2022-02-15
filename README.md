# ETF Analyzer Web App


This jupyter notebook creates a financial database and web application by using SQL, Python, and the Voilà library to analyze the performance of a hypothetical fintech ETF.

The database is contained in the accompanying 'etf.db' file

The application analyzes the daily returns of the ETF stocks both individually and as a whole. 

#### Analyze a Single Asset in the ETF

Using SQL queries with Python, Pandas, and hvPlot we analyze the performance of a single asset from the ETF.

#### Analyze the ETF Portfolio

Build the ETF portfolio by using SQL joins to combine all the data for each asset and then evaluate its performance.

#### Deploy the Notebook as a Web Application

<video width="320" height="240" controls>
  <source src="voila_etf_analyzer.mov" type="video/mp4" alt="Screen Recording of ETF Analyzer deployed with Voila">
</video>

<br>

##Technologies

This notebook requires:

![Jupyter Logo](https://docs.jupyter.org/en/latest/_static/jupyter.svg)
<br>This notebook requires Jupyter lab
<br>Installation:
```
pip install jupyterlab
````

This applications uses pandas<br>
![pandas Logo](https://pandas.pydata.org/docs/_static/pandas.svg)

```
pip install pandas
```

This application uses NumPy<br>
```
pip install numpy
```

This application uses hvPlot<br>
```
pip install hvplot
```

This application uses SQLAlchemy<br>
```
pip install SQLAlchemy
```

This application uses Voila<br>
```
conda install -c conda-forge voila
```


## Contributors

Brought to you by Rachel Bates.

---

## License

MIT
