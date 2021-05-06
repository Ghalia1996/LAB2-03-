 # Comparison Operators #
You may be familiar with comparison operators from math class. Let’s make sure there aren’t any gaps in your knowledge.

- [x] Less than (<) — returns true if the value on the left is less than the value on the right, otherwise it returns false.
- [x] Greater than (>) — returns true if the value on the left is greater than the value on the right, otherwise it returns false.
- [x] Less than or equal to (<=) — returns true if the value on the left is less than or equal to the value on the right, otherwise it returns false.
- [x] Greater than or equal to (>=) — returns true if the value on the left is greater than or equal to the value on the right, otherwise it returns false.
- [x] Equal to (===) — returns true if the value on the left is equal to the value on the right, otherwise it returns false.
- [x] Not equal to (!==) — returns true if the value on the left is not equal to the value on the right, otherwise it returns false.

# Arithmetic Operators #
The Java programming language supports various arithmetic operators for all floating-point and integer numbers. These operators are + (addition), - (subtraction), * (multiplication), / (division), and % (modulo). The following table summarizes the binary arithmetic operations in the Java programming language.

| Operator  |      	Use     |  	Description|
|----------|:-------------:|------:|
| + | op1 + op2 | Adds op1 and op2; also used to concatenate strings |
| - |   op1 - op2   |   Subtracts op2 from op1|
| *|op1 * op2 |   Multiplies op1 by op2 |
| /| op1 / op2 |   Divides op1 by op2 |
| %|op1 % op2 |    Computes the remainder of dividing op1 by op2 |

# Bitwise operators #
operations can be performed on a bit level using bitwise operators.

Bitwise operations are contrasted by byte-level operations which characterize the bitwise operators' logical counterparts, the AND, OR and NOT operators. Instead of performing on individual bits, byte-level operators perform on strings of eight bits (known as bytes) at a time. The reason for this is that a byte is normally the smallest unit of addressable memory (i.e. data with a unique memory address).

This applies to bitwise operators as well, which means that even though they operate on only one bit at a time they cannot accept anything smaller than a byte as their input.

All of these operators are also available in C++, and many C-family languages.
![pic](https://techvidvan.com/tutorials/wp-content/uploads/sites/2/2019/12/types-of-bitwise-operators.jpg)

![pic](https://shashankmohabia.github.io/Blog/assets/images/Bitwise_2.png)

# JavaScript For Loops Explained with Examples # 
**Description
initialization - Run before the first execution on the loop. This expression is commonly used to create counters. Variables created here are scoped to the loop. Once the loop has finished its execution they are destroyed.
condition - Expression that is checked prior to the execution of every iteration. If omitted, this expression evaluates to true. If it evaluates to true, the loop’s statement is executed. If it evaluates to false, the loop stops.
final-expression - Expression that is run after every iteration. Usually used to increment a counter. But it can be used to decrement a counter too.
statement - Code to be repeated in the loop
any of these three expressions or the statement can be omitted. For loops are commonly used to count a certain number of iterations to repeat a statement. Use a break statement to exit the loop before the condition expression evaluates to false.**

# Syntax #
 >for ([initialization]; [condition]; [final-expression]) {
   // statement
}
 
# JavaScript While Loops Explained with Examples #
The while loop starts by evaluating the condition. If the condition is true, the statement(s) is/are executed. If the condition is false, the statement(s) is/are not executed and the while loop ends. while loops deserve some attention, since you will create an infinite loop if the false condition is never met. An infinite loop can crash your application or browser, so make sure all the while loops in your code are finite.

Here is the syntax for the while loop:
>Syntax:
while (condition) {
  statement(s);
} 