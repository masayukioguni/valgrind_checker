valgrind_result
================

## example

```sh
git clone [git-repo-url] valgrind_result
cd valgrind_result
gcc main.c
valgrind -v  --leak-check=full ./a.out 2>&1 | tee results/darwin.log
```
