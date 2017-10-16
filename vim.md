# vim

## Resources

* [Cheat sheet](https://vim.rtorr.com)

## Reload buf when focusing

```viml
autocmd FocusGained,BufEnter * :silent! !
```

## Man

Go to man page for word under cursor:

```viml
K
```

## Exit to normal mode

Use instead of `esc`:

```viml
C-c
```

## Show invisible spaces in list mode

Since 7.4.710:

```viml
set listchars=space:·
```

[source](https://github.com/vim/vim/commit/adf123f0d55bbbe59dc139ede876431349446dd3)

## Faster ctrlp search

```viml
let g:ctrlp_user_command = 'ag %s -l --nocolor -g ""'
```

* [ag](https://github.com/ggreer/the_silver_searcher)
* [ctrlp](https://github.com/ctrlpvim/ctrlp.vim)

## Git commit message rulers

```viml
autocmd FileType gitcommit set colorcolumn=51,73
```

## Interactive replace

By `c` flag:

```viml
:%s/foo/bar/gc
```
