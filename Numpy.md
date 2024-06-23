```python
import numpy as np
arr1=np.array([1,2,3,4,5])
print(arr1)
arr2=np.array([[1,2,3],[4,5,6]])
print(arr2)
```

    [1 2 3 4 5]
    [[1 2 3]
     [4 5 6]]
    


```python
pip install pandas
```

    Requirement already satisfied: pandas in c:\users\kashi\anaconda3\lib\site-packages (2.1.4)
    Requirement already satisfied: numpy<2,>=1.23.2 in c:\users\kashi\anaconda3\lib\site-packages (from pandas) (1.26.4)
    Requirement already satisfied: python-dateutil>=2.8.2 in c:\users\kashi\anaconda3\lib\site-packages (from pandas) (2.8.2)
    Requirement already satisfied: pytz>=2020.1 in c:\users\kashi\anaconda3\lib\site-packages (from pandas) (2023.3.post1)
    Requirement already satisfied: tzdata>=2022.1 in c:\users\kashi\anaconda3\lib\site-packages (from pandas) (2023.3)
    Requirement already satisfied: six>=1.5 in c:\users\kashi\anaconda3\lib\site-packages (from python-dateutil>=2.8.2->pandas) (1.16.0)
    Note: you may need to restart the kernel to use updated packages.
    


```python
import pandas as ps
```


```python
zeros=np.zeros((3,4))
print(zeros)
```

    [[0. 0. 0. 0.]
     [0. 0. 0. 0.]
     [0. 0. 0. 0.]]
    


```python
ones=np.ones((2,3))
print(ones)
```

    [[1. 1. 1.]
     [1. 1. 1.]]
    


```python
range_arr=np.arange(10,20,2)
print(range_arr)
```

    [10 12 14 16 18]
    


```python
r=np.random.rand(3,3)
print(r)
```

    [[0.83590596 0.74771032 0.9675345 ]
     [0.82535968 0.58275661 0.56380399]
     [0.55769928 0.78295974 0.43132657]]
    


```python
arr=np.array([1,2,3,4,5])
print(arr+2)
```

    [3 4 5 6 7]
    


```python
arr=np.array([1,2,3,4,5])
print(np.sqrt(arr))
```

    [1.         1.41421356 1.73205081 2.         2.23606798]
    


```python
print(np.exp(arr))
```

    [  2.71828183   7.3890561   20.08553692  54.59815003 148.4131591 ]
    


```python
print(np.log(arr))
```

    [0.         0.69314718 1.09861229 1.38629436 1.60943791]
    


```python
print(np.sin(arr))
```

    [ 0.84147098  0.90929743  0.14112001 -0.7568025  -0.95892427]
    


```python
  
```
