# Python Operators

### Arithmetic operators
As the name implies, arithmetic operators are for doing arithmetic; addition, subtraction, multiplication, division and others.

| Operator       | Description     | Example       |
| ---------------|:---------------:| -------------:|
| +              | Addition        | 1 + 1 = 2     |
| -              | Subtraction     | 10 - 1 = 9    |
| *              | Multiplication  | 3 * 5 = 15    |
| /              | Division        | 10 / 5 = 2    |
| %              | Modulus         | 11 % 5 = 1    |
| //             | Floor Divison   | 11 // 5 = 2   |

* The *modulus* is the remainder after divison. So, for example, 11 % 5 is 1 because if you divide 11 by 2 you get 5 remainder 1. That 1 is called the modulus
* The *exponent* is ** becuase you can't type a small number in code. It just means "raised to the power of" in the sense that 3**2 is 3 to the power of 2
* *Floor Division*, indicated by //, is integer division in that anything after the decimal is trucated (ignored). For example, in regular division 9 / 5 is 1.8. But 9 // 5 is just 1 because .8 is ignored, it doesn't even round up the 1 to 2.

### Comparison operators
Comparison operators evalute decisions based the facts of a comparison. The operators Python offers to help you write code that makes descisions are listed in the table below:

| Operator       | Meaning                  |
| ---------------| ------------------------:|
| <              | Less Than                |
| <=             | Less than or equal to    |
| >              | Greater than             |
| >=             | Greater than or equal to |
| ==             | Equal to                 |
| !=             | Not equal to             |
| is             | Object identity          |
| is not         | Negated Object identity  |

### Boolean operators
The Boolean operators work with Boolean values (True or False) and are used to determine if one or more things is True or False.

| Operator       | Code Example    | What it Determines       |
| ---------------|:---------------:| ------------------------:|
| or             | x or y          | Either x or y is true    |
| and            | a and y         | Both x or y is true      |
| not            | not x           | x is not full            |