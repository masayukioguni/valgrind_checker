valgrind_checker
================

## example

```sh
git clone [git-repo-url] valgrind_checker
cd valgrind_checker
gcc main.c
valgrind -v  --leak-check=full ./a.out 2>&1 | tee results/darwin.log
```
