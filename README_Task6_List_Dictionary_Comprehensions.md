# Task 6 -- List and Dictionary Comprehensions

## Objective

Learn Python list and dictionary comprehensions.

## List Comprehension

``` python
numbers = [1, 2, 3, 4, 5]
square = [i * i for i in numbers]
print(square)
```

### Even Numbers

``` python
even = [i for i in range(1,11) if i % 2 == 0]
print(even)
```

### Uppercase

``` python
names = ["ram","sita","hari"]
upper = [name.upper() for name in names]
print(upper)
```

## Dictionary Comprehension

``` python
square_dict = {i:i*i for i in range(1,6)}
print(square_dict)
```

``` python
marks = {name:100 for name in ["Ram","Sita","Hari"]}
print(marks)
```

## Filtering

``` python
greater = [i for i in [10,15,20,25,30] if i > 20]
print(greater)
```

## Transformation

``` python
double = [i*2 for i in [1,2,3,4]]
print(double)
```

## Conclusion

Comprehensions make Python code shorter, cleaner, and faster than
traditional loops.

> "Write less code, achieve more with Python."
