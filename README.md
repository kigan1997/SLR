# SLR
Find Simple LR table from a Grammar
Input format:
line 1: the set of terminals(without EPSILON)
line 2: the set of non-terminals
line 3: start symbol(non-terminal)
line 4 and others: production rules(e.g. write E<space>TX for rule like E->TX); one in each line
Run program:
$ gcc slr.c -o slr
$ ./slr slr_input.txt
