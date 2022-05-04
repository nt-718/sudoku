# sudoku

cij = (i,j) i,j in 1...9
C = {1,...,9} cand in C
n = 1...9
linea = caj j in 1...9
columnb = cib i in 1...9
blockc = cij i,j = 
house = line + column + block

single
{cand - (all n in house)}
line single, column single, block single, house single

double
cij = {n1, n2}, ckl = {n1, n2} - cij s.t cij, ckl in the same line or column or block 
=> n1, n2 not in {line(column, block) - cij - ckl}
= delete n1, n2 from {line(column, block) - cij - ckl}
line or column or block = lcb

pointing pares


