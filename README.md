
# Calculator
 #### This library stores the implementation of a simple calculator based on the Reverse Polish Notation.
 #### The expression is translated from the infix record to the postfix record and calculated.

 # Functions
 #### From infix to postfix
`toPostfix(Expression)` returns postfix version of the expression
 #### Calculate postfix expression
 `calculate(Expression)` calculates result of the expression
 #### Get priority of the operator
`priority(Operator)` returns operators priority
 #### Brackets
`checkBrackets(Expression)` checks the correct placement of brackets
 #### Add zeros(auxiliary function)
 `addZeros(Expression)` adds zeros to the unzry cons in the expression
 
 # Exceptions 
 #### EmptyStackException. 
 It comes out when an expression is entered incorrcetly. For example, unnecessary operator.
 #### ArithmeticException
 Occures due to division by zero.