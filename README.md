# race01
## LEGEND
Hey you!You, another one which goes to be The One.To be a part of the Matrix you should think like the Matrix.You need to decode each byte of the Matrix.You need to be a Matrix.
## DESCRIPTION
Create a program that decodes all valid variations of an encrypted math expression.The program takes four arguments:• integer operands:operand1andoperand2• operationoperation• result of the math operationresultYour encoder must support four math operations: addition+ , subtraction- , multiplication*  and division/ . Operands and the result may consist of hidden digits marked by?character. One digit per one? . The program must not print zeros if they are before afull number.
Need to find out which digits are hidden by?  in order to maintain a mathematicalexpression valid. The program must output all valid variations (one per line).Valid expressions in output must be sorted in ascending order ofoperand1. Operands,operations, equal sign and the result in output are separated by a singlespacecharacter.Error handling. The program prints errors to the standard error streamstderr:• if the number of arguments is not equal to 4, the program printsusage: ./part_of_the_matrix [operand1] [operation] [operand2] [result]• in case of invalid operation the program printsInvalid operation: <value>• in case of invalid operands the program printsInvalid operand: <value>• in case of invalid operation the program printsInvalid result: <value>
