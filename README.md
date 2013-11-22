valgrind_checker
================

valgrind_checker

* example * 
>>> gcc main.c
>>> valgrind -v  --leak-check=full ./a.out 2>&1 | tee results/darwin.log
