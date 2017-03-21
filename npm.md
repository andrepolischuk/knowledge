# npm

## Update global modules

```sh
npm -g outdated --parseable=true | cut -d : -f 4 | xargs -n 1 npm -g install
```
