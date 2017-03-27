# git

## Pretty log

```sh
git log --graph --oneline --all --decorate --date-order
```

## Interactive patch selection

```sh
git commit -p -v
```

[@rauchg](https://twitter.com/rauchg/status/778297310694416384)

## Lines of code written today

```sh
git diff --shortstat "@{0 day ago}"
```

[@innovati](https://twitter.com/innovati/status/707386314530930689)

## Ignore file mode

```sh
git config core.fileMode false
```

## Setup gpg key for signing

```sh
git config --global user.signingkey <key>
```

[source](https://git-scm.com/book/en/v2/Git-Tools-Signing-Your-Work)

## Sign all commits with gpg

```sh
git config --global commit.gpgsign true
```

[source](http://stackoverflow.com/questions/10077996/sign-git-commits-with-gpg/20628543#20628543)

## Minimal git status

```sh
git status --short --branch
```
