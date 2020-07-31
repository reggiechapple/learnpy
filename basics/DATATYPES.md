# Data Types in Python

## Numbers
Numbers in Python must start with a number digit, (0-9); a dot (period), which is decimal; or a hypen (-) used as a negative sign for negative numbers

| Number         | Okay?           | Reason                                                               |
| ---------------|:---------------:| --------------------------------------------------------------------:|
| 1              | Good            | A whole number (integer)                                             |
| 1.1            | Good            | A number with a decimal point                                        |
| 1234567.89     | Good            | A large number with a decimal point and no comma                     |
| -2             | Good            | A negative number, as indicated by the starting hypen                |
| .99            | Good            | A number that starts with a decimal point because it's less than one |

### *Integers*
An *integer* is any whole number, positive or negative. There is no limit to its size. Numbers like 0, -1, and 999999999 are all perfectly valid integers. From your perspective, an integer is just any valid number that doesn't contain a decimal point.

### *Floats*
A *floating point number*, often called a *float* for short, is just any valid number that contains a decimal point. Again, there is no size limit, 1.1, -1.1, 123456.789012345 are all perfectly valid floats.
If you happen to work with very large scientific numbers, you can put an *e* in a number to indicate the power of 10. For example, 243e1000 is a valid number, and will be treated as a float even if there's no decimal point.

## Words (strings)
Names, addresses, and all other kinds of text you see every day would be a *string* in Python (and for computers in general). It's called a *string* because it's a string of characters (letters, spaces, punctuation marks, maybe some numbers).
A string must always be enclosed in quotation marks. You can use either double quotation marks(") or single ('). All the following are valid strings:
```python
"Hi there, I am a string"
'Hello world'
"123 Oak Tree Lane"
```
