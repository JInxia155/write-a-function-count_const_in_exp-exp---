# write-a-function-count_const_in_exp-exp---
write a function count_const_in_exp : exp ->

Download Link : https://programming.engineering/product/write-a-function-count_const_in_exp-exp/

Problem

Using the type exp found in common.ml and described above, write a function count_const_in_exp : exp -> int that counts the number of occurrences of constants there are in an expression. The same constant occurring in twice in the expression is counted twice.

Throughout this assignment you may use any library functions you wish.

# let rec count_const_in_exp exp = …

val count_const_in_exp : Common.exp -> int =

# count_const_in_exp (BinOpAppExp (CommaOp,

BinOpAppExp (CommaOp, ConstExp (FloatConst 7.3), ConstExp UnitConst),

BinOpAppExp (ConsOp,

BinOpAppExp (CommaOp, ConstExp (IntConst 4), ConstExp (StringConst “a”)),

BinOpAppExp (ConsOp,

BinOpAppExp (CommaOp, ConstExp (IntConst 6), ConstExp (StringConst “b”)),

ConstExp NilConst))));;

– : int = 7
Solution
