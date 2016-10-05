Reproduction:

`meteor run`

Should eventually crash with

```
Error: Cannot find module '../core-js/symbol/iterator'
```

Moving `babel-runtime` from `devDependencies` to `dependencies` seems to fix it.

