>>> from coards import parse
>>> a = [1, 2, 3]
>>> units = 'days since 1998-03-01 12:00:00'
>>> b = [parse(value, units) for value in a]
>>> print b
[datetime.datetime(1998, 3, 2, 12, 0), datetime.datetime(1998, 3, 3, 12, 0), datetime.datetime(1998, 3, 4, 12, 0)]
