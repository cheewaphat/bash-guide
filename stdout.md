#Redirect stdout to one file and stderr to another file:

```sh
> file redirects stdout to file
1> file redirects stdout to file
2> file redirects stderr to file
&> file redirects stdout and stderr to file
```

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
