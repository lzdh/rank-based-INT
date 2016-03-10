# rank-based-INT
Rank-based inverse normal transformation for python

Function for doing rank-based inverse normal transformation to a Pandas series in python.

```
Perform rank-based inverse normal transformation on pandas series.
If stochastic is True ties are given rank randomly, otherwise ties will
share the same value. NaN values are ignored.

Args:
    param1 (pandas.Series):   Series of values to transform
    param2 (Optional[float]): Constand parameter (Bloms constant)
    param3 (Optional[bool]):  Whether to randomise rank of ties

Returns:
    pandas.Series
```