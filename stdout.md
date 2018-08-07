#Redirect stdout to one file and stderr to another file:

```shell
command > out 2>error
Redirect stderr to stdout (&1), and then redirect stdout to a file:
```

```shell
command >out 2>&1
Redirect both to a file:
```
```shell
command &> out
```
