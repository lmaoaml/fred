This repo contains a python implementation of the Fusional Reduction algorithm (FRed) as described by Brasoveanu & Prince (2011).

The function FRed() takes as input a comparative tableau and returns the Maximally Informative Basis if a satisfying ranking can be assigned. If the tableau is unsatisfiable, the function will print 'unsat', and otherwise returns the MIB. FRed() expects a list (or other iterable) comprising lists of equal length containing only 'W', 'L', and 'e'.
