# 2018 Notes

## PyData NYC Oct 2018

**pandas: Integer NA as a first class citizen**
<br/>_Jeff Reback (Two Sigma)_<br/>
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=gxvTVxlvH9w
<br/>&nbsp;&nbsp;https://github.com/jreback/pydata_nyc-2018

 - Extension Arrays - Specification of how external arrays interface with pandas
   - First class data dtypes
   - Decouple memory management and processing from pandas (and numpy)
 - 0.24 - First class dtypes
   - Integer NA
     - dtype='Int64' (capitalized!)
     - Uses `IntegerArray` instead of numpy array
     - has values and a mask
```python
    s.values        # IntegerArray([1, 2, nan], dtype='Int64'
    s.values._data  # array([1, 2, 1])
    s.values._mask  # array([False, False, True])
```
 
