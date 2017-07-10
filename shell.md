# Shell

## Stream redirections

```sh
cat foo.txt > bar.txt   # overwrite bar.txt with foo.txt content
cat foo.txt >> bar.txt  # append foo.txt content to end of bar.txt
cat . 2> bar.txt        # overwrite bar.txt with errors
cat . 2>> bar.txt       # append errors to end of bar.txt
```

## Get file by curl

```sh
curl -O -L -# <url>
```

## Aliases with sudo

```sh
alias sudo='sudo '
```

[source](http://askubuntu.com/a/22043)

## Init openconnect

```sh
sudo openconnect --user <username> --authgroup <usergroup> <server>
```

## Make file executable

```sh
chmod +x script.sh
```

## Mass replace

```sh
find . -type f -name '*.js' -exec sed -i='' 's/foo/bar/g' {} \;
```
