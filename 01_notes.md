# Basic Math Operations

Follow PEMDAS

## Integers versus Floats

- **Integer** = a whole number, ex: `10`
- **Float** = a number with a decimal, ex: `10.10`

If you perform an operation with a float, the output will also be a float, even if there is no remainder.

## Addition

The `+` symbol is used for adding numbers, both integers and floating point values. This operation is known as addition.

It is worth noting that the `+` symbol can also be used to concatenate strings.

```python
7+9 
# 16

20+47
# 67

27.5 + 9.4 + 2
# 38.9

'Hello ' + 'Oliver!'
# 'Hello Oliver!'
```

## Subtraction

The `-` operator performs basic subtraction operations and cannot be used on strings.

```python
10 - 7
# 3
```

## Multiply

The `*` operator performs basic multiplication operations. It is the only operator that can be used on a mix of integers and strings, resulting in string concatenation.

```python
6 * 2
# 12

"Hello Oliver! " * 3
# 'Hello Oliver! Hello Oliver! Hello Oliver! '
```

## Power Of

This function outputs the value of int1 raised to the power of int2. Note that it cannot be used on strings.

```python
100 ** 2
# 100

2 ** 4
# 16
```

## Divide

Using `/` will return a float, while using `//` will return the quotient without any remainder.

```python
10 / 5
# 2.0

10 // 2
# 2

10.5 // 3
# 3.0
```

## Quotient (Modulo Operator)

This function returns the remainder of a division operation.

```python
50 % 4
# 2

50 % 5
# 0
```