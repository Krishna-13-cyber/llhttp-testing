# llhttp-testing
Test repo for investigating llhttp

Command
```
clang -Os -g3 -Wall -Wextra -Wno-unused-parameter api.c test.c libllhttp.a -I/llhttp/build -I/llhttp/build/c/llhttp.c -o main

./main
```