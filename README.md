# lex/yacc example

To compile, run the following commands:

```shell
$ yacc -dv mycalc.y
$ lex mycalc.l
$ gcc -o mycalc y.tab.c lex.yy.c
```

Usage:

```shell
$ ./mycalc
1 + 2 * 3
>>7.000000
```

# LICENSE

`mycalc.c` and `mycalc.y` are written by Kazuya Maebashi and those are available at
http://kmaebashi.com/programmer/devlang/yacclex.html
