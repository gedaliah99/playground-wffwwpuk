# PYTHON: The Map() Function

In Python, there is a built-in function in the standard library called ```map()```.

The ```map()``` function is useful for iterating through a list/array.

Let's explore this cool function:

## Exploring the Map() Function

The ```map()``` function executes a specified function for each item in an iterable. The item is sent to the function as a parameter.

Here's an example:
```python runnable
string = "1 2 3 4"

a, b, c, d = map(int, string.split(" "))
```

Let's dive deeper:

First we create a variable ```string``` with a string of numbers (1-4) separated by spaces.

Let's look at the part to the right of the equals symbol: ```map(int, string.split(" "))```.

1. We have split the string into an array of string values by splitting at every occurence of a space.
2. We then iterate through each value in the array and convert each value to an integer.
3. Then we call the 4 values ```a```, ```b```, ```c``` and ```d``` respectively.

This is handy, right?

You can also do this with ```str```, ```float```, etc...

## Program: The Map() Function in Action!
Now that we've explored it, let's implement it in a program.
```python runnable
string = "1 2 3 4 5"

# Our values are: 1.0, 2.0, 3.0, 4.0 and 5.0
a, b, c, d, e = map(float, string.split(" "))

print(int(a*b*c*d*e))
```
The result should be ```120```.

## Try it for yourself!
Give it a go and explore the ```map()``` function.
```python runnable
variable = ""

x = map(arg1, arg2)

```

Happy Coding,
@Code-Parser