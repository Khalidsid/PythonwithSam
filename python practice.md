write a python script to play a game. This project will help you to better work with python. Use the  python3 no special version, you will choose yourself.
The first function will get the number of attempts [1-25]. The value inputed will be only integer and between 1 and 25.

We will work together to finalize this project and at the end you will see that it will help you to better understand:

Random
Variables
Boolean
Input and Output
Integer
Char
String
Length
Print


```python
def get_attempts(x):
    input(int(x))
    if x in range(26):
        print(x)
```


```python
def test_get_attempts_1():
    assert(get_attempts(1) == 1)    
def test_get_attempts_25():
    assert(get_attempts(25) == 25)
def test_get_attempts_26():
    assert(get_attempts(26) == False)
def test_get_attempts_a():
    assert(get_attempts(a) == False)
```


```python
test_get_attempts_1()
```

    11
    1
    


    ---------------------------------------------------------------------------

    AssertionError                            Traceback (most recent call last)

    <ipython-input-31-0397510e60de> in <module>
    ----> 1 test_get_attempts_1()
    

    <ipython-input-29-35b758991031> in test_get_attempts_1()
          1 def test_get_attempts_1():
    ----> 2     assert(get_attempts(1) == 1)
          3 def test_get_attempts_25():
          4     assert(get_attempts(25) == 25)
          5 def test_get_attempts_26():
    

    AssertionError: 



```python

```


```python

```


```python

```
