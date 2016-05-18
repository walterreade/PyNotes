## PyData 2016 - Amsterdam

### Presentations


**The PyData map: Presenting a map of the landscape of PyData tools** (_Peader Coyle_)
<br/>https://www.youtube.com/watch?v=QgjkgNVXSjQ
<br/>http://bit.ly/pydatakeynotespringcoil
<br/>https://peadarcoyle.wordpress.com/2016/03/02/a-map-of-the-pydata-stack/

- Get on board with Python 3!
- The PyData Stack comments ...
 - `pandas assign` - create a new column, e.g., `df.assign(ln_A_plus_1=lambda x: np.log(x.A)+1)`
 - `xarray` - Labeled heterogenous data (`numpy` arrays plus labels), e.g., weather forecasting data
 - `blaze` - Query data on different storage systems
 - `bcolz` - Columnar data store, high-performance compression, in- and out-of-memory operations [tabular]
 - `dask` - Out-of-memory calculations (usually good 10 Gb to 1 Tb) [array]
 - `Arrow / Ibis` - Better SQL integration with `pandas` API and better columnar data structures for dealing with HDFS, etc.
 - `spaCy` - NLP
- Itertools
 - http://jmduke.com/posts/a-gentle-introduction-to-itertools
 
 

### Tutorials
