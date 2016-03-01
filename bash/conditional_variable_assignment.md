# Conditional Variable Assignment

You substitute an empty variable for a default value with `:-`.

```bash
$ echo ${email:-test@example.com}
test@example.com
$ email=foo@bar.com # Now we'll set email so it is not empty
$ echo ${email:-test@example.com}
foo@bar.com
```
