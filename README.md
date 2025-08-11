# Calculator
A basic calculator which uses postfix notation to solve the numericals


It uses stacks to store operands and operators separately and then via postfix notation continuously solve them.

Postfix Notation

If an operand with greater precedence is found than the one at the top of the stack, then we just push the operand at the top of the operand stack.
If an operand with lower or equal precedence is encountered than the one at the top of the stack, then we just coninuously pop the top of the stack and evaluate till the codition is falsified
