# Loops and Conditions - Relational and Logical Operators ! 
In the C programming language there a number of operators that allow us to construct expressions whose value depends on some condition between the values of the operands. The following set of four operators, known as the relational operators, are basic examples.  
like...  
Operating defenitions!   
+ >	Greater than  
+ >=	Greater than or equal to  
+ <=	Less than or equal to  
+ <	Less than

As well as the relational operators, the C programming language also provides two equality operators!  
+ Operator	Meaning  
+ ==	Is equal to  
+ !=	Is not equal to

# our last words for today ! 
This output says that 3 is less than -4, which is apparently wrong. What has happened is that the "<" operator has two operands, one of type int and the other of type unsigned int , in this case the arithmetic conversion rules require the signed operand to be converted to unsigned by bit pattern preservation before the comparison. The normal representation of negative numbers involves setting high order bits to indicate this fact so unsigned comparison will see the value with the high order bits set as the larger. This can be even more confusing with the char data type, since the signed or unsigned nature of char is not always obvious.


