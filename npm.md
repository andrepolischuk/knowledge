# npm

## Update global modules

```sh
npm -g outdated --parseable=true | cut -d : -f 4 | xargs -n 1 npm -g install
```

## Bump version with custom tag prefix

You can use `v-1.0.0` instead of default `v1.0.0`:

```sh
npm version major --tag-version-prefix=v-
```

## Deprecate package

```sh
npm deprecate <package>[@version] <message>
```

[source](https://docs.npmjs.com/cli/deprecate)
