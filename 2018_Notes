# 2018 Notes

## PyData 2018

### [pandas: Integer NA as a first class citizen](https://www.youtube.com/watch?v=gxvTVxlvH9w)
 * By: Jeff Reback (Two Sigma)
 * Extension Arrays - Specification of how external arrays interface with pandas
  * First class data dtypes
  * Decouple memory management and processing from pandas (and numpy)
 * 0.24 - First class dtypes
  * Sparse
  * Integer NA
   * dtype='Int64' (capitalized!)
   * Uses `IntegerArray` instead of numpy array
   * has values and a mask
    ```python
    s.values        # IntegerArray([1, 2, nan], dtype='Int64'
    s.values._data  # array([1, 2, 1])
    s.values._mask  # array([False, False, True])
    ```
 
