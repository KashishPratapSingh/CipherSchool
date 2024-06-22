```python
def add_number(a,b):
    return a+b
print(add_number(3,4))
```

    7
    


```python
def greet(name, message="hello"):
    return f"{message},{name}!"
print(greet("Bob"))
print(greet("Alice","Hi"))
```

    hello,Bob!
    Hi,Alice!
    


```python
def sum_all(*args):
    return sum(args)
print(sum_all(1,2,3,4))
```

    10
    


```python
def display_info(**kwargs):
    for key,value in kwargs.items():
        print(f"{key}:{value}")
display_info(name="john",age=30,city="new York")
```

    name:john
    age:30
    city:new York
    


```python
square=lambda x:x*x
print(square(5))
```

    25
    


```python
s=[1,2,3,4,5]
square=list(map(lambda x:x*x,s))
print(square)
```

    [1, 4, 9, 16, 25]
    


```python
n=[1,2,3,4,5,6]
even_number=list(filter(lambda x:x%2==0, n))
print(even_number)
```

    [2, 4, 6]
    


```python
try:
    s=10/0
except ZeroDivisionError:
    print("Cannot divide")
    
```

    Cannot divide
    


```python
number=int(input())
try:
    s=10/number
except ValueError:
    print("Invalid Value")
except ZeroDivisionError:
    print("Cannot divide")
else:
    print("Divide Successfull")
```

     4
    

    Divide Successfull
    


```python

```
