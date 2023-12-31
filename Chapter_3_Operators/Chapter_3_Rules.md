## Rules

# Numeric Promotion Rules
1. If two values have different data types, Java will automatically  promote one of the values to the larger of the two data types.
2. If one of the values is integral and the other is floating-point, Java will automatically promote the integral value to the floating-point value’s data type. 
3. Smaller data types, namely, byte , short , and char , are first promoted to int any time they’re used with a Java binary arithmetic operator, even if neither of the operands is int .
4. After all promotion has occurred and the operands have the same data type, the resulting value will have the same data type as its promoted operands.

# The equality operators are used in one of three scenarios:
- Comparing two numeric or character primitive types. If the numeric values are of different data types, the values are automatically promoted. For example, 5 == 5.00 returns true since the left side is promoted to a double .
- Comparing two boolean values
- Comparing two objects, including null and String values

## Logical Operators
- AND is only true if both operands are true.
- Inclusive OR is only false if both operands are false .
- Exclusive OR is only true if the operands are different.

