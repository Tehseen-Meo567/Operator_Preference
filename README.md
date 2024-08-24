# Operator Preference in Python
It's a surprise that Python don't use mathematic operator pereference. In Mathematics, we use preference in BODMAS (Bracket, Order, Division, Multiplication, Addition and Subtraction).

In comparison to it, In Python, operators have a specific order of precedence, which determines the order in which they are evaluated in an expression. Understanding this order is crucial for writing clear and correct code. Here's a breakdown of the operator precedence from highest to lowest:

# 1. Parentheses: 
### ( )
Used to group expressions and override the default precedence.
# 2. Exponentiation: 
### **
Used for raising a number to a power.
# 3. Unary Operators:
###  + (positive)
### - (negative)
### ~ (bitwise NOT)
Applied to a single operand.

>_**( All operators below are Evaluated from left to right)**_
# 4. Multiplication, Division, and Modulus:
### * (multiplication)
### / (division)
### // (floor division)
rounds down to the nearest integer
### % (modulus)
returns the remainder of division

# 5. Addition and Subtraction:
### + (addition)
### - (subtraction)

# 6. Bitwise Shifts:
### << (left shift)
shifts bits to the left
### >> (right shift)
shifts bits to the right
# 7. Bitwise AND: 
### &
performs bit-by-bit AND operation
# 8. Bitwise XOR:
### ^
performs bit-by-bit exclusive OR operation
# 9. Bitwise OR: 
### |
performs bit-by-bit OR operation
# 10. Membership Operators:
### in
Checks if a value is present in a sequence
### not in
Checks if a value is not present in a sequence
# 11. Identity Operators:
### is
Checks if two objects are the same object
### is not
Checks if two objects are not the same object

# 12. Conditional Operators:
### not (logical NOT)
reverses the logical value of an operand
### and (logical AND)
returns True if both operands are True
### or (logical OR)
returns True if at least one operand is True


