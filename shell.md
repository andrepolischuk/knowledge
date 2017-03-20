# Shell

## Stream redirections

Overwrite bar.txt with foo.txt content

```sh
cat foo.txt > bar.txt
```

Append foo.txt content to end of bar.txt

```sh
cat foo.txt >> bar.txt
```

Overwrite bar.txt with errors

```sh
cat . 2> bar.txt
```

Append errors to end of bar.txt

```sh
cat . 2>> bar.txt
```
