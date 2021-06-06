# Loops and iteration

### What is the difference between loop and iteration?

_Loop refers to the code... iteration refers to the process in which the content of loop is executed once.. so 1 iteration refers to 1 time execution of loop._

### The statements for loops provided in JavaScript are:
1. for statement
2. do...while statement
3. while statement
4. labeled statement
5. break statement
6. continue statement
7. for...in statement
8. for...of statement


***for statement***

for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement

  - The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
  - The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. If the value of condition is false, the for loop terminates. (If the condition expression is omitted entirely, the condition is assumed to be true.)
  - The statement executes. To execute multiple statements, use a block statement ({ ... }) to group those statements.
- If present, the update expression incrementExpression is executed.
Control returns to Step 2.

*** is used when know how many of iteration.***


***while statement***

while (condition)

  statement

  _If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop._

*** is used when don't know how many of iteration.***