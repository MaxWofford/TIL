# Backticks

Everything between backticks is evaluated by the shell before the rest of the
command.  This is similar to using executing coded in a subshell with `$()`,
however backticks cannot be nested.

For example:
```bash
$ readlink -f python
/usr/bin/python
$ readlink -f `which python`
/usr/bin/python2.7
```
